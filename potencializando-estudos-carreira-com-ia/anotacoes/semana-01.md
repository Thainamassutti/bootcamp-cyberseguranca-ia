# 📝 Diário de Bordo - Semana 01

> **Instrução:** Use este arquivo para registrar seus estudos diários da **Semana 1**.  
> Para as semanas seguintes, basta **duplicar** este arquivo e renomear para `semana-02.md`, `semana-03.md`, etc., ajustando os tópicos conforme o [`cronograma.md`](../cronograma.md).

---

## 📋 Informações Gerais

- **Tema da Semana:** Fundamentos de Hardware e Sistemas Operacionais
- **Período:** `[DD/MM/AAAA]` a `[DD/MM/AAAA]`
- **Status:** 🟡 Em Andamento <!-- 🔴 Não iniciado | 🟡 Em Andamento | 🟢 Concluído -->
- **Horas Totais Dedicadas:** `00h00`

---

## 🎯 Objetivos da Semana

- [ ] Compreender os componentes internos de um computador e seu fluxo de funcionamento.
- [ ] Entender o papel do Windows na gestão de hardware e processos.
- [ ] Dominar a criação de usuários locais e permissões de segurança.
- [ ] Aprender técnicas iniciais de troubleshooting para problemas de lentidão e travamentos.

---

## 📖 Registro Diário de Estudos

### 🔹 Dia 1: Componentes do Computador
- **Conceitos aprendidos:**
  - *CPU:* (registre aqui suas anotações sobre núcleos, threads, clock)
  - *Memória RAM vs. Armazenamento (SSD / HDD):*
  - *Placa-mãe e Fonte de alimentação:*
- **Comandos / Ferramentas utilizadas:**
- **Dificuldades encontradas & Como resolvi:**

---

### 🔹 Dia 2: Montagem Lógica, Periféricos e Drivers
- **Conceitos aprendidos:**
  - *BIOS / UEFI e processo de POST:*
  - *Drivers de dispositivos e Gerenciador de Dispositivos:*
- **Comandos / Ferramentas utilizadas:**
- **Dúvidas pendentes:**

---

### 🔹 Dia 3: Instalação, Remoção de Programas e Configurações do Windows
- **Conceitos aprendidos:**
  - *Painel de Controle clássico vs. Configurações (`Win + I`):*
  - *Desinstalação limpa de softwares e inicialização:*
- **Comandos / Atalhos testados:**
- **Observações:**

---

### 🔹 Dia 4: Gerenciamento de Usuários e Permissões
- **Conceitos aprendidos:**
  - *Contas locais vs. Contas Microsoft:*
  - *Grupos locais (Administradores vs. Usuários Padrão):*
  - *Permissões NTFS básicas:*
- **Prática realizada:**
  - [x] Criado usuário local de teste `usuario-suporte`
  - [x] Ajustadas permissões de leitura/escrita na pasta `C:\Dados`

---

### 🔹 Dia 5: Gerenciador de Tarefas e Serviços do Windows
- **Conceitos aprendidos:**
  - *Abas de Desempenho e Inicialização no Gerenciador de Tarefas:*
  - *Console de Serviços (`services.msc`): Inicialização Automática, Manual e Desativada:*
- **Comandos / Atalhos:**
  - `taskmgr`, `services.msc`, `resmon` (Monitor de Recursos)
- **Descobertas práticas:**

---

### 🔹 Dia 6: Diagnóstico de Problemas Comuns
- **Cenários investigados:**
  1. *PC Lento:* (Causas identificadas: disco 100%, muitos apps ao inicializar, falta de RAM)
  2. *Programa travando:* (Finalização forçada, verificação de logs no Visualizador de Eventos `eventvwr`)
  3. *Falta de espaço em disco:* (Limpeza de disco `cleanmgr`, exclusão de temporários `%temp%`)
- **Ações tomadas e resultados:**

---

### 🔹 Dia 7: Revisão Geral da Semana
- **Resumo consolidado:**
- **Pontos fortes:**
- **Pontos a reforçar:**

---

## 🧪 Laboratório Prático da Semana

### 1. Criação de Usuário e Permissões
- **Passo a passo executado:**
  1. Abrir `compmgmt.msc` (Gerenciamento do Computador) ou `lusrmgr.msc`.
  2. Criar novo usuário `teste_suporte` sem privilégios administrativos.
  3. Definir senha e desmarcar obrigatoriedade de troca (ou configurar conforme política).
- **Evidências / Comentários:**

### 2. Análise de Processos com Alto Consumo
- **Ferramenta utilizada:** Monitor de Recursos (`resmon`) e Gerenciador de Tarefas.
- **Processo analisado:**
- **Conclusão:**

---

## 💡 Dicas e Atalhos Úteis Aprendidos

| Atalho / Comando | Função |
| :--- | :--- |
| `Ctrl + Shift + Esc` | Abre o Gerenciador de Tarefas diretamente |
| `Win + R` | Abre a caixa de diálogo "Executar" |
| `services.msc` | Gerenciador de Serviços do Windows |
| `lusrmgr.msc` | Gerenciador de Usuários e Grupos Locais |
| `devmgmt.msc` | Gerenciador de Dispositivos |
| `eventvwr.msc` | Visualizador de Eventos do Windows |
| `cleanmgr` | Utilitário de Limpeza de Disco |
