# 🤖 Instruções de Uso — AI Dev Team by Jeyson

Este repositório contém um time completo de agentes de IA para uso no GitHub Copilot Chat.
Cada agente possui um papel, responsabilidades e critérios de saída bem definidos.

---

## 🚀 Como Usar no GitHub Copilot Chat

### Modo 1 — Agente Único
Use quando quiser acionar um agente específico para uma tarefa pontual.

**Prompt base:**
```
Aja como o [Nome do Agente] descrito em agents/[pasta]/README.md deste repositório.
Sua tarefa é: [descreva a tarefa].
Siga todas as responsabilidades e critérios de saída definidos no seu README.
```

**Exemplos práticos:**
```
Aja como o Agente 05 - Backend Dev descrito em agents/05-backend-dev/README.md.
Sua tarefa é: criar uma API REST em Node.js para gerenciamento de usuários.
Siga todas as responsabilidades e critérios de saída definidos no seu README.
```

```
Aja como o Agente 09 - QA Engineer descrito em agents/09-qa-engineer/README.md.
Sua tarefa é: criar um plano de testes para a API de usuários recém desenvolvida.
Siga todas as responsabilidades e critérios de saída definidos no seu README.
```

---

### Modo 2 — Fluxo Completo (Orquestrado)
Use quando quiser acionar o time completo para uma demanda de ponta a ponta.

**Prompt base:**
```
Aja como o Agente 00 - Orchestrator descrito em agents/00-orchestrator/README.md deste repositório.
Orquestre o time completo para atender a seguinte demanda: [descreva a demanda].
Siga o fluxo de trabalho definido, acionando cada agente na ordem correta e validando os gates.
```

**Exemplo prático:**
```
Aja como o Agente 00 - Orchestrator descrito em agents/00-orchestrator/README.md.
Orquestre o time completo para atender a seguinte demanda:
Precisamos de um sistema de autenticação com JWT para uma aplicação web.
Siga o fluxo de trabalho definido, acionando cada agente na ordem correta e validando os gates.
```

---

## 👥 Agentes Disponíveis e Prompts Prontos

| # | Agente | Prompt Rápido |
|---|--------|---------------|
| 00 | 🧠 Orchestrator | `Aja como o Agente 00 - Orchestrator e orquestre o time para: [demanda]` |
| 01 | 🎯 Product Owner | `Aja como o Agente 01 - Product Owner e escreva as histórias de usuário para: [funcionalidade]` |
| 02 | 🔄 Scrum Master | `Aja como o Agente 02 - Scrum Master e planeje a sprint para: [objetivo]` |
| 03 | 🏛️ Architect | `Aja como o Agente 03 - Architect e defina a arquitetura para: [sistema]` |
| 04 | ⚙️ Tech Lead | `Aja como o Agente 04 - Tech Lead e faça a revisão técnica de: [código/decisão]` |
| 05 | 💻 Backend Dev | `Aja como o Agente 05 - Backend Dev e desenvolva: [API/serviço]` |
| 06 | 🎨 Frontend Dev | `Aja como o Agente 06 - Frontend Dev e desenvolva: [interface/componente]` |
| 07 | 🗄️ DBA | `Aja como o Agente 07 - DBA e modele o banco de dados para: [sistema]` |
| 08 | 🛠️ Engineer | `Aja como o Agente 08 - Engineer e projete a infraestrutura para: [sistema]` |
| 09 | 🧪 QA Engineer | `Aja como o Agente 09 - QA Engineer e crie o plano de testes para: [funcionalidade]` |
| 10 | 🚀 DevOps | `Aja como o Agente 10 - DevOps e configure o pipeline CI/CD para: [projeto]` |
| 11 | 🔒 DevSecOps | `Aja como o Agente 11 - DevSecOps e faça a análise de segurança de: [código/sistema]` |
| 12 | 🛡️ SRE | `Aja como o Agente 12 - SRE e defina os SLOs e plano de confiabilidade para: [serviço]` |
| 13 | 💰 FinOps | `Aja como o Agente 13 - FinOps e analise e otimize os custos de: [infraestrutura]` |
| 14 | 🔴 Red Team | `Aja como o Agente 14 - Red Team e simule ataques e vulnerabilidades em: [sistema]` |
| 15 | 🔵 Blue Team | `Aja como o Agente 15 - Blue Team e defina a estratégia de defesa para: [sistema]` |
| 16 | 🖌️ Designer | `Aja como o Agente 16 - Designer e crie o design e identidade visual para: [produto]` |
| 17 | 📣 Marketing | `Aja como o Agente 17 - Marketing e crie a estratégia de marketing para: [produto]` |
| 18 | 💼 Sales | `Aja como o Agente 18 - Sales e crie o pitch de vendas para: [produto]` |
| 19 | 📱 Mobile Developer | `Aja como o Agente 19 - Mobile Developer e desenvolva: [tela/funcionalidade mobile]` |
| 20 | 🤖 Data Scientist | `Aja como o Agente 20 - Data Scientist e analise os dados de: [conjunto de dados]` |
| 21 | ☁️ Cloud Engineer | `Aja como o Agente 21 - Cloud Engineer e projete a arquitetura cloud para: [sistema]` |
| 22 | ✍️ Tech Writer | `Aja como o Agente 22 - Tech Writer e documente: [sistema/API/processo]` |
| 23 | 📋 Project Manager | `Aja como o Agente 23 - Project Manager e gerencie o projeto de: [demanda]` |
| 24 | 🛠️ Support Engineer | `Aja como o Agente 24 - Support Engineer e resolva o chamado: [problema]` |

---

## 💡 Dicas de Uso

- **Seja específico** na descrição da tarefa para obter respostas mais precisas
- **Referencie o README** do agente no prompt para o Copilot ter contexto completo
- **Use o Orchestrator** para demandas complexas que envolvem múltiplos agentes
- **Valide os gates** antes de avançar para o próximo agente no fluxo
- **Combine agentes** para tarefas que exigem múltiplas perspectivas

---

## 🔗 Referências

- <a href="https://github.com/jeysonlr/ai-dev-team-by-jeyson">Repositório principal</a>
- <a href="https://github.com/jeysonlr/ai-dev-team-by-jeyson/blob/main/README.md">README principal</a>
- <a href="https://github.com/jeysonlr/ai-dev-team-by-jeyson/tree/main/agents">Pasta de agentes</a>