# 🤖 AI Dev Team by Jeyson

Time completo de agentes de IA para criação, manutenção e automação de projetos reais de software — Powered by GitHub Copilot.

## 👥 Agentes do Time

| # | Agente | Papel |
|---|--------|-------|
| 00 | <a href="agents/00-orchestrator/README.md">🧠 Orchestrator</a> | Orquestra o fluxo entre todos os agentes |
| 01 | <a href="agents/01-product-owner/README.md">🎯 Product Owner</a> | Requisitos, backlog e critérios de aceite |
| 02 | <a href="agents/02-scrum-master/README.md">🔄 Scrum Master</a> | Cerimônias ágeis, impedimentos e fluxo |
| 03 | <a href="agents/03-architect/README.md">🏛️ Architect</a> | Decisões de arquitetura e design de sistema |
| 04 | <a href="agents/04-tech-lead/README.md">⚙️ Tech Lead</a> | Liderança técnica e revisão de código |
| 05 | <a href="agents/05-backend-dev/README.md">💻 Backend Dev</a> | Desenvolvimento de APIs e serviços backend |
| 06 | <a href="agents/06-frontend-dev/README.md">🎨 Frontend Dev</a> | Desenvolvimento de interfaces e UX |
| 07 | <a href="agents/07-dba/README.md">🗄️ DBA</a> | Performance de banco de dados e modelagem |
| 08 | <a href="agents/08-engineer/README.md">🛠️ Engineer</a> | Engenharia de sistemas e infraestrutura |
| 09 | <a href="agents/09-qa-engineer/README.md">🧪 QA Engineer</a> | Testes, validações e qualidade |
| 10 | <a href="agents/10-devops/README.md">🚀 DevOps</a> | CI/CD, pipelines e automação |
| 11 | <a href="agents/11-devsecops/README.md">🔒 DevSecOps</a> | Segurança integrada ao desenvolvimento |
| 12 | <a href="agents/12-sre/README.md">🛡️ SRE</a> | Confiabilidade e disponibilidade |
| 13 | <a href="agents/13-finops/README.md">💰 FinOps</a> | Gestão e otimização de custos |
| 14 | <a href="agents/14-red-team/README.md">🔴 Red Team</a> | Pentest e simulação de ataques |
| 15 | <a href="agents/15-blue-team/README.md">🔵 Blue Team</a> | Defesa, monitoramento e resposta |
| 16 | <a href="agents/16-designer/README.md">🖌️ Designer</a> | Design gráfico, identidade visual e UX/UI |
| 17 | <a href="agents/17-marketing/README.md">📣 Marketing</a> | Estratégia de marketing e posicionamento |
| 18 | <a href="agents/18-sales/README.md">💼 Sales</a> | Estratégias de vendas e apresentação de valor |
| 19 | <a href="agents/19-mobile-developer/README.md">📱 Mobile Developer</a> | Desenvolvimento de apps mobile iOS e Android |
| 20 | <a href="agents/20-data-scientist/README.md">🤖 Data Scientist</a> | Análise de dados e modelos de machine learning |
| 21 | <a href="agents/21-cloud-engineer/README.md">☁️ Cloud Engineer</a> | Infraestrutura e arquitetura cloud |
| 22 | <a href="agents/22-tech-writer/README.md">✍️ Tech Writer</a> | Documentação técnica e base de conhecimento |
| 23 | <a href="agents/23-project-manager/README.md">📋 Project Manager</a> | Planejamento e gestão de projetos |
| 24 | <a href="agents/24-support-engineer/README.md">🛠️ Support Engineer</a> | Suporte técnico N1, N2 e N3 |

## 🔄 Fluxo de Trabalho
```
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
```
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
