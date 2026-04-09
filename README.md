# 🤖 AI Dev Team by Jeyson

Time completo de agentes de IA para criação, manutenção e automação de projetos reais de software — Powered by GitHub Copilot.

## 👥 Agentes do Time

| # | Agente | Papel |
|---|--------|-------|
| 00 | 🧠 Orchestrator | Orquestra o fluxo entre todos os agentes |
| 01 | 🎯 Product Owner | Requisitos, backlog e critérios de aceite |
| 02 | 🔄 Scrum Master | Cerimônias ágeis, impedimentos e fluxo |
| 03 | 🏛️ Architect | Decisões de arquitetura e design de sistema |
| 04 | ⚙️ Tech Lead | Liderança técnica e revisão de código |
| 05 | 💻 Backend Dev | Desenvolvimento de APIs e serviços backend |
| 06 | 🎨 Frontend Dev | Desenvolvimento de interfaces e UX |
| 07 | 🗄️ DBA | Performance de banco de dados e modelagem |
| 08 | 🛠️ Engineer | Engenharia de sistemas e infraestrutura |
| 09 | 🧪 QA Engineer | Testes, validações e qualidade |
| 10 | 🚀 DevOps | CI/CD, pipelines e automação |
| 11 | 🔒 DevSecOps | Segurança integrada ao desenvolvimento |
| 12 | 🛡️ SRE | Confiabilidade e disponibilidade |
| 13 | 💰 FinOps | Gestão e otimização de custos |
| 14 | 🔴 Red Team | Pentest e simulação de ataques |
| 15 | 🔵 Blue Team | Defesa, monitoramento e resposta |
| 16 | 🖌️ Designer | Design gráfico, identidade visual e UX/UI |
| 17 | 📣 Marketing | Estratégia de marketing e posicionamento |
| 18 | 💼 Sales | Estratégias de vendas e apresentação de valor |
| 19 | 📱 Mobile Developer | Desenvolvimento de apps mobile iOS e Android |
| 20 | 🤖 Data Scientist | Análise de dados e modelos de machine learning |
| 21 | ☁️ Cloud Engineer | Infraestrutura e arquitetura cloud |
| 22 | ✍️ Tech Writer | Documentação técnica e base de conhecimento |
| 23 | 📋 Project Manager | Planejamento e gestão de projetos |
| 24 | 🛠️ Support Engineer | Suporte técnico N1, N2 e N3 |

## 🔄 Fluxo de Trabalho

🎯 PO → 🔄 SM → 🏛️ Architect → ⚙️ Tech Lead
                                      ↓
                    💻 Backend + 🎨 Frontend + 🗄️ DBA
                                      ↓
                              🧪 QA (Gate 1)
                                      ↓
                    🔒 DevSecOps + 🔴 Red Team (Gate 2)
                                      ↓
                              🔵 Blue Team (Gate 3)
                                      ↓
                              🚀 DevOps Deploy
                                      ↓
                         🛡️ SRE + 💰 FinOps (Gate 4)
                                      ↓
                    🖌️ Designer + 📣 Marketing + 💼 Sales
                                      ↓
                             ✅ ENTREGA APROVADA

## 🚦 Critérios de Saída (Definition of Done)

Cada agente só libera para o próximo quando:
- ✅ 100% dos critérios de aceite atendidos
- ✅ Zero erros críticos
- ✅ Zero vulnerabilidades de segurança críticas
- ✅ Padrões globais de mercado atendidos
- ✅ Revisão aprovada pelo Tech Lead

## 🔁 Como Usar em Outros Projetos

1. Clone ou referencie este repositório
2. Copie a pasta `agents/` para seu projeto
3. Configure o `.github/copilot-instructions.md` apontando para os agentes desejados
4. Use os workflows de validação automática

## 📁 Estrutura do Repositório
```
ai-dev-team-by-jeyson/
├── .github/
│   ├── copilot-instructions.md
│   └── workflows/
├── agents/
│   ├── 00-orchestrator/
│   ├── 01-product-owner/
│   ├── 02-scrum-master/
│   ├── 03-architect/
│   ├── 04-tech-lead/
│   ├── 05-backend-dev/
│   ├── 06-frontend-dev/
│   ├── 07-dba/
│   ├── 08-engineer/
│   ├── 09-qa-engineer/
│   ├── 10-devops/
│   ├── 11-devsecops/
│   ├── 12-sre/
│   ├── 13-finops/
│   ├── 14-red-team/
│   ├── 15-blue-team/
│   ├── 16-designer/
│   ├── 17-marketing/
│   ├── 18-sales/
│   ├── 19-mobile-developer/
│   ├── 20-data-scientist/
│   ├── 21-cloud-engineer/
│   ├── 22-tech-writer/
│   ├── 23-project-manager/
│   └── 24-support-engineer/
├── standards/
│   ├── acceptance-criteria.md
│   ├── definition-of-done.md
│   ├── security-standards.md
│   └── code-quality-standards.md
└── workflows/
    └── agent-pipeline.md
```
---
> Criado por [@jeysonlr](https://github.com/jeysonlr) — Powered by GitHub Copilot 🤖
