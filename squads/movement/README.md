---
id: movement-readme
squad: movement
version: "2.0.0"
---

# Movement Squad — MMOS

> **Sistema Operacional de Movement Marketing**
> Cultura + Identidade + Narrativa + Comunidade + Ativação + Impacto

---

## O que é o Movement Squad?

O Movement Squad é o sistema responsável por criar, orquestrar e medir **movimentos de marketing** —
não campanhas pontuais. Um movimento é um sistema vivo de identidade coletiva, narrativa compartilhada,
rituais replicáveis e ação coordenada que gera impacto mensurável no negócio.

## Por que Movement e não Campaign?

| Campanha | Movimento |
|----------|-----------|
| Início e fim definidos | Ciclos de renovação contínuos |
| Empurra mensagem | Puxa participação |
| Audiência passiva | Comunidade ativa |
| Métricas de vaidade | Prova de impacto real |
| Controlada centralmente | Distribuída e remixável |

## Os 7 Agentes

| Agente | Papel |
|--------|-------|
| **Movement Chief** | Orquestra, prioriza, aprova, define "não-fazer" |
| **Movement Architect** | Desenha o sistema (engine, loops, coerência) |
| **Fenomenólogo** | Observa e captura sinais culturais, tensões, linguagem |
| **Identitário** | Cria identidade coletiva, fronteiras, símbolos |
| **Estrategista de Ciclo** | Escolhe timing, cadência, escalada |
| **Manifestador** | Transforma tese em artefatos replicáveis |
| **Analista de Impacto** | Mede, valida, aprende, retroalimenta |

## Princípios

1. **evidence-over-belief** — Sinais reais, não achismo
2. **movement-not-campaign** — Movimento sustentável, não campanha pontual
3. **community-first** — Comunidade gera movimento, não o contrário
4. **prove-or-kill** — Sem prova de impacto = pivotar ou matar
5. **tension-is-fuel** — Tensão cultural é o motor do movimento

## Ciclo Principal (RalphLooping)

```
Pesquisar → Criar → Lançar → Medir → Aprender → Atualizar → Repetir
```

## Estrutura

```
squads/movement/
├── agents/          — 7 agentes AI com HRM
├── checklists/      — Quality gates (~95+ arquivos)
├── frameworks/      — Metodologias (~80+ arquivos)
├── reference/       — Base intelectual (~90+ arquivos)
├── templates/       — Entregáveis padronizados (~50+ arquivos)
├── tasks/           — Tarefas executáveis (~65+ arquivos)
├── workflows/       — Fluxos ponta-a-ponta (~20 arquivos)
├── voice/           — Tom e linguagem (~22+ arquivos)
├── phrases/         — Biblioteca de frases (~18 arquivos)
├── swipe/           — Swipe files (~37+ arquivos)
├── data/            — Research + registries + metrics (~45+ arquivos)
├── docs/            — Documentação (~18 arquivos)
├── lib/             — Componentes reutilizáveis (~38+ arquivos)
├── scripts/         — Automação (~12 arquivos)
├── archive/         — Histórico (~20+ arquivos)
├── authority/       — Thought leadership (~13 arquivos)
├── projects/        — Templates de projeto (~40+ arquivos)
├── ARCHITECTURE.md  — Arquitetura completa
├── config.yaml      — Cérebro de roteamento
└── README.md        — Este arquivo
```

## Como Usar

1. **Comece por** `ARCHITECTURE.md` para entender o sistema
2. **Consulte** `config.yaml` para ver o roteamento task→agent→framework→checklist→template
3. **Execute tasks** seguindo os workflows numerados em `workflows/`
4. **Valide** com os checklists correspondentes em `checklists/`
5. **Registre** em `data/registries/` e meça em `data/metrics/`

## Cross-Squad

O Movement Squad integra com 5 squads:

- **Brand Squad** — Identidade, posicionamento, guidelines
- **Copy Squad** — Slogans, headlines, tom/voz
- **Storytelling Squad** — Narrativa pública, founder story
- **Traffic Squad** — Amplificação, hooks, métricas
- **Design Squad** — Identidade visual, artefatos, templates

Detalhes completos em `config.yaml` seção `cross_squad`.

## Documentação

Guias completos em `docs/`:
- `docs/getting-started.md` — Como começar
- `docs/agent-roles-guide.md` — Papéis dos agentes
- `docs/workflow-guide.md` — Como executar workflows
- `docs/glossary.md` — Vocabulário do squad
