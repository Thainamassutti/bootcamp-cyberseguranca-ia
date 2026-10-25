# 📅 Cronograma de Estudos - 30 Dias (Semanas 1 a 4)

Este roteiro organiza os 30 dias de estudos do plano de **Suporte em Infraestrutura de TI**.  
Use as caixas de seleção `[ ]` para marcar o seu progresso diário.

---

## 📌 Semana 1 - Fundamentos de Hardware e Sistemas Operacionais

> **Objetivo da Semana:** Compreender como um computador funciona internamente, como o Windows é administrado e como solucionar problemas básicos de hardware e software.

### 🗓️ Roteiro Diário

- [ ] **Dia 1: Componentes do Computador**
  - CPU, Memória RAM, SSD vs. HDD, Placa-mãe (chipset, soquete), Fonte de alimentação (potência, PFC ativo).
- [ ] **Dia 2: Montagem Lógica e Periféricos**
  - Fluxo de inicialização (BIOS/UEFI, POST), barramentos, periféricos de entrada/saída e instalação/atualização de drivers.
- [ ] **Dia 3: Administração de Aplicativos e Sistema Windows**
  - Instalação e desinstalação segura de programas, Painel de Controle clássico vs. Configurações modernas do Windows.
- [ ] **Dia 4: Gerenciamento de Usuários e Permissões**
  - Criação de contas locais, tipos de contas (Administrador vs. Padrão), controle de acesso (UAC) e permissões NTFS básicas.
- [ ] **Dia 5: Gerenciador de Tarefas e Serviços**
  - Monitoramento de desempenho (CPU, Memória, Disco, Rede), finalização de processos travados e gerenciamento de serviços (`services.msc`).
- [ ] **Dia 6: Diagnóstico de Problemas Comuns (Troubleshooting)**
  - Identificação de causas para: PC lento, programas congelando/travando e esgotamento de espaço em disco (limpeza de disco, arquivos temporários).
- [ ] **Dia 7: Revisão Geral e Síntese**
  - Revisão de todos os conceitos da semana e consolidação das anotações em [`anotacoes/semana-01.md`](anotacoes/semana-01.md).

### 🛠️ Prática Obrigatória da Semana 1
- [ ] Criar uma nova conta de usuário local sem privilégios administrativos.
- [ ] Alterar permissões de uma pasta e testar o acesso com a nova conta.
- [ ] Utilizar o Gerenciador de Tarefas e o Monitor de Recursos para identificar processos que consomem mais CPU/memória.

---

## 📌 Semana 2 - Redes de Computadores

> **Objetivo da Semana:** Entender como dispositivos se comunicam em uma rede corporativa, a arquitetura TCP/IP e dominar comandos de diagnóstico.

### 🗓️ Roteiro Diário

- [ ] **Dia 8: Conceitos Fundamentais de Redes**
  - Topologias, redes LAN, WAN, MAN, Internet, Intranet e equipamentos básicos (switches, roteadores, access points).
- [ ] **Dia 9: Endereçamento IP e Sub-redes**
  - Estrutura do IPv4 (classes públicas vs. privadas RFC 1918), máscaras de rede (`/24`, `255.255.255.0`) e broadcast.
- [ ] **Dia 10: Gateway Padrão e Sistema de Nomes (DNS)**
  - O papel do Gateway de rede no roteamento e como o DNS resolve nomes de domínio em endereços IP.
- [ ] **Dia 11: DHCP (Distribuição Automática de IP)**
  - Processo DORA (Discover, Offer, Request, Acknowledge), escopos de rede, tempo de concessão (lease time) e reservas de IP.
- [ ] **Dia 12: Portas e Protocolos de Rede**
  - Portas conhecidas e suas funções: HTTP (80), HTTPS (443), FTP (20/21), SSH (22), RDP (3389), DNS (53), DHCP (67/68).
- [ ] **Dia 13: Comandos de Diagnóstico e Resolução de Falhas**
  - Utilização prática de:
    - `ipconfig` / `ipconfig /all` / `ipconfig /flushdns` / `ipconfig /renew`
    - `ping` (latência e perda de pacotes)
    - `tracert` (análise de saltos e rotas)
    - `nslookup` (consultas a servidores DNS)
- [ ] **Dia 14: Exercícios Práticos e Revisão**
  - Laboratório de troubleshooting de rede e consolidação das anotações em `anotacoes/semana-02.md`.

### 🛠️ Prática Obrigatória da Semana 2
- [ ] Descobrir o IP local, gateway e servidor DNS da sua estação.
- [ ] Testar consultas usando servidores DNS públicos (como `8.8.8.8` e `1.1.1.1`) via `nslookup`.
- [ ] Interpretar uma saída completa de `tracert` até um site externo.
- [ ] Simular um problema de falta de conexão (desativar placa/alterar IP para inválido) e diagnosticar o erro.

---

## 📌 Semana 3 - Linux Básico e Serviços de Rede

> **Objetivo da Semana:** Aprender os fundamentos do Linux para servidores/estações de trabalho e compreender a função dos principais serviços de infraestrutura corporativa.

### 🗓️ Roteiro Diário

- [ ] **Dia 15: Introdução ao Linux e Árvore de Diretórios**
  - Filosofia do sistema, distribuições (foco em Ubuntu/Debian), hierarquia do FHS (`/`, `/etc`, `/var`, `/home`, `/bin`, `/usr`).
- [ ] **Dia 16: Navegação e Manipulação via Terminal**
  - Comandos fundamentais: `pwd`, `ls -la`, `cd`, `mkdir -p`, `rmdir`, `cp`, `mv`, `rm`.
- [ ] **Dia 17: Manipulação de Arquivos e Permissões**
  - Criação de arquivos (`touch`, `nano`/`vim`), leitura (`cat`, `less`, `head`, `tail`) e sistema de permissões rwx (`chmod`, `chown`).
- [ ] **Dia 18: Gestão de Usuários, Grupos e Privilégios**
  - Comandos: `useradd`, `adduser`, `passwd`, `usermod`, `groupadd` e elevação com `sudo`.
- [ ] **Dia 19: Servidores: Físicos vs. Virtuais**
  - Conceito de servidor, arquitetura cliente-servidor, servidores bare-metal vs. máquinas virtuais (hipervisores Tipo 1 e Tipo 2).
- [ ] **Dia 20: Serviços Corporativos de Rede**
  - Como servidores Linux/Windows fornecem serviços essenciais: servidor DNS local, servidor DHCP corporativo e compartilhamento de arquivos (Samba / SMB, NFS).
- [ ] **Dia 21: Conceitos de Active Directory e Domínio Corporativo**
  - O que é um domínio Windows, Controladores de Domínio (DC), objetos (usuários, grupos, computadores), OUs (Unidades Organizacionais) e GPOs (Políticas de Grupo).

### 🛠️ Prática Obrigatória da Semana 3
- [ ] Instalar o Ubuntu Server ou Desktop em uma máquina virtual (usando VirtualBox).
- [ ] Criar usuários e grupos no Linux via terminal e atribuir permissões de leitura/escrita específicas a uma pasta.
- [ ] Compartilhar uma pasta na rede local ou transferir arquivos entre a máquina física e a VM.

---

## 📌 Semana 4 - Suporte Técnico na Prática & Projeto Final

> **Objetivo da Semana:** Desenvolver o raciocínio de diagnóstico sistemático, postura de atendimento a usuários, documentação técnica e integração de todos os conhecimentos em um laboratório final.

### 🗓️ Roteiro Diário

- [ ] **Dia 22: Metodologia de Diagnóstico (Troubleshooting)**
  - O ciclo de resolução: Coletar informações → Isolar o problema → Formular hipóteses → Testar solução → Prevenir reincidência.
- [ ] **Dia 23: Incidentes Práticos: Problemas de Conexão**
  - Resolução de "Sem acesso à internet", conflito de IP, falha de DNS, cabo desconectado, problemas de Wi-Fi e DHCP inativo.
- [ ] **Dia 24: Incidentes Práticos: Usuário Sem Acesso a Sistemas**
  - Conta bloqueada por tentativas de senha, permissões de pastas de rede negadas, expiração de credenciais e MFA/2FA.
- [ ] **Dia 25: Incidentes Práticos: Computador Lento e Sobrecarga**
  - Softwares em inicialização automática, disco em 100%, infecções básicas por malware/adware, desfragmentação/trim.
- [ ] **Dia 26: Incidentes Práticos: Problemas de Impressora**
  - Impressora offline, spooler de impressão travado (`spoolsv.exe`), reinstalação de drivers e impressoras de rede por IP.
- [ ] **Dia 27: Incidentes Práticos: Configurações Incorretas de Rede**
  - Gateway incorreto, proxy configurado por engano no navegador, firewall local bloqueando portas corporativas.
- [ ] **Dia 28: Documentação Técnica e Base de Conhecimento (KB)**
  - Como redigir artigos de base de conhecimento (KB), registrar históricos de chamados e criar procedimentos operacionais padrão (POP).
- [ ] **Dia 29: Simulação de Chamados e Atendimento**
  - Resolução de cenários simulados de Helpdesk com registro formal de abertura, análise, resolução e encerramento.
- [ ] **Dia 30: Execução e Apresentação do Projeto Final**
  - Montagem e teste do laboratório integrador completo.

---

## 🏆 Projeto Final Integrador (Dia 30)

O projeto final consolida todas as competências das 4 semanas em um ambiente controlado:

1. **Ambiente Windows:** Máquina física ou VM configurada com usuário padrão e políticas básicas.
2. **Ambiente Linux (VM):** Servidor Linux instalado no VirtualBox operando na mesma rede virtual.
3. **Testes de Conectividade:** Comunicação validada entre as máquinas (`ping`, resolução de nomes, análise de portas abertas).
4. **Criação e Gestão de Usuários:** Contas criadas em ambos os sistemas com controle de acessos restrito.
5. **Relatório Técnico do Procedimento:** Documentação detalhada dos passos, testes e telas geradas, armazenada na pasta `anotacoes/`.
