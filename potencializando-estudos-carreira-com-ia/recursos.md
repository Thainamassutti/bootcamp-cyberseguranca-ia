# 📚 Recursos e Materiais de Estudo por Semana

Compilado de cursos, documentações oficiais, canais recomendados e ferramentas de apoio para cada etapa do plano de 30 dias.

---

## 📌 Semana 1: Fundamentos de Hardware e Sistemas Operacionais

### 🎓 Cursos e Guias Principais
- **[Curso de Hardware - Curso em Vídeo](https://www.youtube.com/playlist?list=PLHz_AreHm4dn1JHgN9wpbIUhzZnykk5wv)**
  - *Descrição:* Curso completo e didático ministrado por Gustavo Guanabara, cobrindo placas-mãe, processadores, memórias, barramentos e montagem.
- **[Bóson Treinamentos - Hardware e Montagem de Computadores](https://www.youtube.com/@bosontreinamentos)**
  - *Descrição:* Aulas aprofundadas sobre arquitetura de computadores, tipos de barramentos, fontes de alimentação e compatibilidade.
- **[Microsoft Learn - Windows Fundamentals / Fundamentos do Windows](https://learn.microsoft.com/pt-br/training/paths/explore-windows-fundamentals/)**
  - *Descrição:* Trilha gratuita da Microsoft sobre o funcionamento do Windows, arquitetura de sistemas e recursos de segurança.
- **[Microsoft Learn - Administração do Windows](https://learn.microsoft.com/pt-br/training/windows/)**
  - *Descrição:* Módulos focados no gerenciamento de contas de usuários, permissões NTFS, serviços e ferramentas administrativas.

### 🛠️ Ferramentas Recomendadas
- **Gerenciador de Tarefas (`taskmgr`) & Monitor de Recursos (`resmon`):** Nativos do Windows para diagnóstico de consumo de hardware.
- **CPU-Z / HWMonitor:** Ferramentas para visualização detalhada de componentes de hardware e temperaturas.

---

## 📌 Semana 2: Redes de Computadores

### 🎓 Cursos e Guias Principais
- **[Cisco Networking Academy (NetAcad) - Cursos Gratuitos de Redes](https://www.netacad.com/pt-br/courses/networking)**
  - *Descrição:* Cursos introdutórios gratuitos da Cisco (como *Networking Basics* ou *Networking Devices and Initial Configuration*) com certificado.
- **[Curso Redes de Computadores para Iniciantes - Bóson Treinamentos](https://www.youtube.com/playlist?list=PLucm8g_ezqNq-48i_iPswiT6q_Xh949eB)**
  - *Descrição:* Série completa e prática cobrindo modelo OSI, arquitetura TCP/IP, máscaras de sub-rede, portas e roteamento.
- **[Microsoft Learn - Fundamentos de Rede e TCP/IP](https://learn.microsoft.com/pt-br/training/modules/network-foundations/)**
  - *Descrição:* Documentação e exercícios guiados sobre endereçamento IPv4, Gateway padrão, resolução DNS e protocolo DHCP.

### 🛠️ Ferramentas & Prática
- **Terminal do Windows (CMD / PowerShell):**
  - Comandos fundamentais: `ipconfig /all`, `ping`, `tracert`, `nslookup`, `netstat -ano`.
- **Cisco Packet Tracer (Opcional):**
  - Simulador oficial gratuito para montagem de topologias de rede corporativa.

---

## 📌 Semana 3: Linux Básico e Serviços de Rede

### 🎓 Cursos e Guias Principais
- **[Curso Linux - Curso em Vídeo](https://www.youtube.com/playlist?list=PLHz_AreHm4dlIXleu2wKSqyQSpufjMuHg)**
  - *Descrição:* Excelente introdução ao mundo Linux, terminal Bash, estrutura de diretórios e comandos básicos.
- **[Linux Journey (linuxjourney.com)](https://linuxjourney.com/)**
  - *Descrição:* Plataforma interativa e gratuita para aprender comandos do terminal, sistema de arquivos, permissões (`chmod`/`chown`) e processos.
- **[Documentação Oficial do Ubuntu Server](https://ubuntu.com/server/docs)**
  - *Descrição:* Guia de referência para instalação, configuração de interfaces de rede e pacotes no Ubuntu.
- **[Microsoft Learn - Visão Geral do Active Directory Domain Services (AD DS)](https://learn.microsoft.com/pt-br/windows-server/identity/ad-ds/get-started/virtual-dc/active-directory-domain-services-overview)**
  - *Descrição:* Fundamentos de domínios corporativos, estrutura de floresta/árvore, OUs, contas de serviço e políticas de grupo (GPO).

### 🛠️ Ferramentas & Laboratório
- **[Oracle VM VirtualBox](https://www.virtualbox.org/)**: Software gratuito e de código aberto para virtualização local.
- **[Ubuntu Desktop / Server ISO](https://ubuntu.com/download)**: Imagem ISO para criar sua máquina virtual de testes.

---

## 📌 Semana 4: Suporte Técnico na Prática & Troubleshooting

### 🎓 Metodologias e Resolução de Problemas
- **Metodologia de Troubleshooting CompTIA / ITIL:**
  1. Identificar o problema (questionar o usuário, reproduzir o sintoma).
  2. Estabelecer uma teoria de causa provável.
  3. Testar a teoria para confirmar a causa raiz.
  4. Estabelecer e implementar um plano de ação.
  5. Verificar funcionalidade total do sistema e aplicar medidas preventivas.
  6. Documentar descobertas, ações realizadas e resultados.
- **[Microsoft Sysinternals Suite](https://learn.microsoft.com/pt-br/sysinternals/)**: Ferramentas avançadas de diagnóstico técnico da Microsoft (Process Explorer, Autoruns, TCPView).
- **Simulação de Helpdesk & Atendimento:**
  - Prática de comunicação empática, alinhamento de expectativas e elaboração de relatórios técnicos claros e objetivos.

---

## 🌟 Dicas Extras para Potencializar seus Estudos

1. **Pratique o Método Feynman:** Após estudar um tópico (ex: como funciona o DNS), tente explicar o conceito em voz alta de forma simples, como se estivesse explicando para um usuário leigo.
2. **Monte seu Laboratório Pessoal:** Crie pequenas falhas intencionais na máquina virtual (como errar o IP do gateway ou bloquear uma porta) e tente diagnosticar usando apenas o terminal.
3. **Mantenha suas Anotações Atualizadas:** Documente na pasta [`anotacoes/`](anotacoes/) os erros que encontrar e a forma exata como os resolveu. Essa será a sua primeira base de conhecimento profissional!
