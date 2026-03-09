---
id: movement-architecture
squad: movement
version: "2.0.0"
updated: "2026-03-09"
---

# ARCHITECTURE — Movement Squad (MMOS)

> **Sistema Operacional de Movement Marketing:**
> Cultura + Identidade + Narrativa + Comunidade + Ativação + Impacto

---

## 1. VISÃO GERAL

O Movement Squad é o sistema responsável por criar, orquestrar e medir **movimentos** — não campanhas.
Um movimento é um sistema vivo de identidade coletiva, narrativa compartilhada, rituais replicáveis e
ação coordenada que gera impacto mensurável no negócio.

### 1.1 Diferença Fundamental

| Campanha | Movimento |
|----------|-----------|
| Tem início e fim | Tem ciclos de renovação |
| Empurra mensagem | Puxa participação |
| Audiência passiva | Comunidade ativa |
| Métricas de vaidade | Prova de impacto |
| Controlada centralmente | Distribuída e remixável |

### 1.2 Princípios Inegociáveis

1. **evidence-over-belief** — Sinais reais, não achismo. Toda tese precisa de prova.
2. **movement-not-campaign** — Movimento sustentável, não campanha pontual.
3. **community-first** — Comunidade gera movimento, não o contrário.
4. **prove-or-kill** — Sem prova de impacto = pivotar ou matar.
5. **tension-is-fuel** — Tensão cultural é o motor do movimento.

---

## 2. OS 7 PILARES

```
┌─────────────────────────────────────────────────────────────┐
│                    MOVEMENT ENGINE                           │
├──────────┬──────────┬──────────┬──────────┬────────────────┤
│  CULTURA │IDENTIDADE│ SISTEMA  │  TIMING  │ MANIFESTAÇÃO   │
│  (Radar) │ (Nós/Eles)│ (Loops) │ (Ciclos) │ (Artefatos)   │
│          │          │          │          │                │
│ Fenomeno-│Identitá- │Architect │Estrateg. │ Manifestador   │
│ logo     │rio       │          │de Ciclo  │                │
├──────────┴──────────┴──────────┴──────────┴────────────────┤
│              ATIVAÇÃO (Chief + Architect)                    │
├─────────────────────────────────────────────────────────────┤
│           PROVA (Analista de Impacto)                       │
└─────────────────────────────────────────────────────────────┘
```

| # | Pilar | Agente Responsável | Domínio |
|---|-------|--------------------|---------|
| 1 | Cultura (sinais e tensões) | Fenomenólogo | Etnografia, linguagem, fricções |
| 2 | Identidade (nós/eles, símbolos) | Identitário | Pertencimento, fronteiras, códigos |
| 3 | Sistema (loops, rituais, artefatos) | Architect | Engine, coerência, escalabilidade |
| 4 | Timing (ciclos e cadência) | Estrategista de Ciclo | Janelas, momentum, sazonalidade |
| 5 | Manifestação (assets e kits) | Manifestador | Manifesto, slogans, memes, rituais |
| 6 | Ativação (comunidade + distribuição) | Chief + Architect | Lançamento, canais, criadores |
| 7 | Prova (impacto e causalidade) | Analista de Impacto | Métricas, experimentos, ROI |

---

## 3. FLUXO PRINCIPAL — RalphLooping

```
    ┌──────────────────────────────────────────────┐
    │              RALPHLOOPING (KAIZEN)            │
    │                                              │
    │   Pesquisar → Criar → Lançar → Medir →      │
    │   Aprender → Atualizar → Repetir             │
    │                                              │
    └──────────────────────────────────────────────┘
         │          │         │        │
         ▼          ▼         ▼        ▼
    ┌────────┐ ┌────────┐ ┌───────┐ ┌────────┐
    │ Radar  │ │Criação │ │Ativa- │ │Impacto │
    │Cultural│ │Artefat.│ │ção    │ │Medição │
    └────────┘ └────────┘ └───────┘ └────────┘
```

### 3.1 Ciclo Detalhado

1. **PESQUISAR** — Fenomenólogo + Ciclo capturam sinais, tensões, linguagem
2. **CRIAR** — Architect + Identitário + Manifestador transformam sinais em tese, identidade e artefatos
3. **LANÇAR** — Chief + Architect ativam via comunidade, criadores, distribuição
4. **MEDIR** — Impacto valida com métricas, coortes, experimentos
5. **APRENDER** — Insights viram playbooks, checklists, frameworks updates
6. **ATUALIZAR** — Decision log, registries, config.yaml evoluem
7. **REPETIR** — Próximo ciclo começa com radar enriquecido

---

## 4. DIAGRAMA DE DEPENDÊNCIA

```
config.yaml (cérebro de roteamento)
    │
    ├──► agents/ (7 agentes HRM)
    │       │
    │       ├──► tasks/ (65+ tarefas)
    │       │       │
    │       │       ├──► workflows/ (20 fluxos)
    │       │       │
    │       │       └──► templates/ (50+ entregáveis)
    │       │
    │       ├──► frameworks/ (80+ metodologias)
    │       │
    │       └──► checklists/ (95+ quality gates)
    │
    ├──► data/
    │       ├── research/ (radar cultural)
    │       ├── registries/ (memória operacional)
    │       └── metrics/ (prova de impacto)
    │
    ├──► voice/ + phrases/ (linguagem e tom)
    │
    ├──► swipe/ + swipe-sources/ (repertório)
    │
    ├──► reference/ (base intelectual)
    │
    ├──► lib/ (componentes reutilizáveis)
    │
    ├──► docs/ (documentação)
    │
    ├──► scripts/ (automação)
    │
    ├──► projects/ (templates de projeto)
    │
    ├──► archive/ (histórico)
    │
    └──► authority/ (thought leadership)
```

### 4.1 Fluxo de Roteamento (config.yaml)

```
Task → Agents (quais e em qual ordem)
     → Frameworks (quais são obrigatórios)
     → Checklists (qual quality gate passa)
     → Templates (qual template gera output)
     → Registries (onde registrar em data/)
     → Metrics (quais métricas confirmam vida)
```

---

## 5. OS 7 AGENTES

### 5.1 Papéis e Limites (anti-caos)

| Agente | Papel | Limites |
|--------|-------|---------|
| **Movement Chief** | Orquestra, prioriza, aprova, define "não-fazer" | Decide escopo, não executa criação |
| **Movement Architect** | Desenha o sistema (engine, loops, coerência) | Garante coerência, não faz conteúdo |
| **Fenomenólogo** | Observa, captura, descreve sinais culturais | Observa, não opina — dados, não achismo |
| **Identitário** | Cria identidade coletiva + fronteiras + símbolos | Não faz "branding genérico" |
| **Estrategista de Ciclo** | Escolhe timing, cadência, escalada | Evita "lançar no vazio" |
| **Manifestador** | Transforma tese em artefatos replicáveis | Materializa, não estrategiza |
| **Analista de Impacto** | Mede, valida, aprende, retroalimenta | Mata vaidade cedo |

### 5.2 Estrutura HRM de Cada Agente

Cada arquivo de agente (`agents/*.md`) contém 9 seções obrigatórias:

1. **ROLE DEFINITION** — Identidade, expertise, domínio de autoridade, o que NÃO faz
2. **SYSTEM PROMPT** — Instruções core, constraints, guardrails, idioma pt-BR
3. **CHAIN-OF-THOUGHT** — Framework de decisão, protocolo step-by-step, árvore lógica
4. **FEW-SHOT EXAMPLES** — 3+ exemplos (cenário comum, edge case, cross-squad)
5. **OUTPUT FORMAT** — Template primário, variantes por tipo de task
6. **DECISION HEURISTICS** — Matriz de prioridade, thresholds, critérios de escalação
7. **SELF-EVALUATION** — Checklist de qualidade, score de completude, triggers de melhoria
8. **ACTIVATION PROMPTS** — Cold start, continuation, review/audit
9. **INTEGRATION POINTS** — Upstream, downstream, cross-squad handoffs

---

## 6. ESTRUTURA DE DIRETÓRIOS

### 6.1 Resumo Completo

| Diretório | Arquivos | Descrição |
|-----------|----------|-----------|
| agents/ | 7 | 7 agentes core com HRM |
| checklists/ | ~95+ | Quality gates: 20 raiz + 12 subpastas |
| frameworks/ | ~80+ | Núcleo + agente + referência + stack + aplicação |
| reference/ | ~90+ | Livros + movimentos + campanhas + psicologia + indústrias |
| templates/ | ~50+ | Briefs, outputs, reports, plans, operational |
| tasks/ | ~65+ | Research, strategy, creation, activation, measurement, review, ops |
| workflows/ | ~20 | Fluxos numerados ponta-a-ponta |
| voice/ | ~22+ | Tone profiles, language guides, calibration, channel |
| phrases/ | ~18 | Biblioteca de frases por categoria |
| swipe/ | ~37+ | Manifestos, slogans, rituals, memes, creator, PR, identity, community |
| swipe-sources/ | ~8 | Fontes curadas |
| data/ | ~45+ | Research + registries + metrics |
| docs/ | ~18 | Documentação completa |
| scripts/ | ~12 | Automação e cálculo |
| lib/ | ~38+ | Components, patterns, utilities, taxonomies |
| archive/ | ~20+ | Iconic, evolution, failures |
| authority/ | ~13 | Thought leadership |
| projects/ | ~40+ | 6 tipos de projeto com fases |
| **TOTAL** | **~690+** | **Sistema operacional de movement marketing** |

---

## 7. PADRÕES DE ARQUIVO

### 7.1 Template por Tipo

**Agent (.md):** YAML frontmatter + 9 seções HRM (~400-500 linhas)
**Framework (.md):** YAML frontmatter + Overview, Princípios, Protocolo, Quando Usar, Integração, Exemplo (~150-300 linhas)
**Reference (.md):** YAML frontmatter + Resumo, Insights, Aplicabilidade, Cross-refs (~100-200 linhas)
**Checklist (.md):** YAML frontmatter + Items por fase, Pass/Fail, Escalação (~80-150 linhas)
**Task (.md):** YAML frontmatter + Objetivo, Inputs, Processo, Outputs, Quality Gate (~100-200 linhas)
**Template (.md):** YAML frontmatter + Instruções, Seções, Exemplo (~80-150 linhas)
**Workflow (.md):** YAML frontmatter + Diagrama, Fases, Decision Gates, Agents, Artifacts (~150-250 linhas)

### 7.2 YAML Frontmatter (obrigatório)

```yaml
---
id: {kebab-case-unique-id}
title: "{Título Descritivo}"
squad: movement
type: {agent|framework|reference|checklist|task|template|workflow|voice|phrase|script|doc}
category: {subcategoria}
agents: [{lista de agentes relacionados}]
version: "1.0"
updated: "YYYY-MM-DD"
tags: [{tags relevantes}]
---
```

### 7.3 Naming Conventions

- **Arquivos:** kebab-case em inglês (conforme MMOS): `movement-chief.md`, `enemy-dream-mechanism.md`
- **Subpastas:** kebab-case em inglês
- **Dados YAML:** kebab-case para keys
- **Numeração em workflows:** `NN-` prefix (00-20)
- **Numeração em projects:** `NN-` prefix por fase

---

## 8. CROSS-SQUAD INTEGRATION

```
                    ┌───────────────┐
                    │  MOVEMENT     │
                    │  SQUAD        │
                    └───────┬───────┘
            ┌───────────────┼───────────────┐
            │               │               │
     ┌──────▼──────┐ ┌─────▼─────┐ ┌───────▼──────┐
     │ BRAND SQUAD │ │COPY SQUAD │ │STORYTELLING  │
     │             │ │           │ │SQUAD         │
     │ identidade  │ │ slogans   │ │ narrativa    │
     │ positioning │ │ headlines │ │ public narr. │
     │ guidelines  │ │ tom/voz   │ │ founder story│
     └─────────────┘ └───────────┘ └──────────────┘
            │               │               │
     ┌──────▼──────┐ ┌─────▼─────┐
     │TRAFFIC SQUAD│ │DESIGN     │
     │             │ │SQUAD      │
     │ amplificação│ │ visual id │
     │ hooks/ads   │ │ artefatos │
     │ métricas    │ │ templates │
     └─────────────┘ └───────────┘
```

### 8.1 Handoffs Bidirecionais

Detalhados em `config.yaml` na seção `cross_squad`.

---

## 9. QUALITY GATES

### 9.1 Gates Obrigatórios (toda ação)

1. `movement-thesis-quality` — Toda ação começa com tese validada
2. `identity-system-quality` — Identidade coletiva definida
3. `impact-dashboard-quality` — Métricas definidas e acionáveis

### 9.2 Gates por Domínio

- **Research:** cultural-insight-quality, phenomenology-signal-capture
- **Identity:** we-us-now-identity, boundary-and-belonging
- **Creation:** manifesto-quality, memetic-asset-quality, ritual-design-quality
- **Activation:** distribution-plan-quality, community-activation-quality
- **Measurement:** experimentation-quality, vanity-metric-filter
- **Governance:** ethics-and-boundaries, claim-proof-standard

---

## 10. KPIs

### 10.1 Movement Health

| KPI | Descrição | Threshold |
|-----|-----------|-----------|
| Movement Health Score | Score composto (0-100) | Verde: >70, Amarelo: 40-70, Vermelho: <40 |
| Content→Conversation Rate | % conteúdo que gera conversa real | >15% |
| Memetic Spread Rate | Shares, remixes, UGC | Crescendo MoM |
| Ritual Participation | Participação em rituais | >30% dos membros ativos |

### 10.2 Community

| KPI | Descrição |
|-----|-----------|
| Community Growth Rate | Crescimento com qualidade |
| Community Retention | Retenção por coorte (30/60/90d) |
| Champion Count & Impact | Número e contribuição dos champions |
| Community Sentiment | Positivo/neutro/negativo |

### 10.3 Business

| KPI | Descrição |
|-----|-----------|
| Leads Attributed | Leads atribuíveis ao movimento |
| Trials from Movement | Trials/demos originados |
| Revenue Attributed | Receita (com limites honestos) |
| Brand Search Lift | Lift em buscas de marca |

### 10.4 Operational

| KPI | Descrição |
|-----|-----------|
| Thesis Validation Rate | % teses validadas vs descartadas |
| Experiment Velocity | Experimentos por mês |
| Time to First Signal | Detecção → primeira ação |
| Decision Log Currency | Semanas desde última entry |

---

## 11. GLOSSÁRIO RÁPIDO

| Termo | Definição |
|-------|-----------|
| **Movimento** | Sistema vivo de identidade + narrativa + rituais + ação coletiva |
| **Tese** | Enemy/Dream/Mechanism — o "porquê" do movimento |
| **Artefato** | Qualquer asset replicável (manifesto, meme, kit, ritual) |
| **Ritual** | Ação repetível com gatilho → script → recompensa social |
| **Champion** | Membro que lidera/defende o movimento organicamente |
| **Health Score** | Score composto que mede se o movimento está vivo |
| **RalphLooping** | Ciclo: Pesquisar→Criar→Lançar→Medir→Aprender→Atualizar→Repetir |
| **Kill Criteria** | Condições para encerrar/pivotar um movimento |
| **Quality Gate** | Checklist que precisa passar antes de "final" |
