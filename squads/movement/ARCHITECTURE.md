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

---

## 12. CASCATA DE QUALITY GATES

O Movement Squad opera com uma cascata de 6 níveis de quality gates, cada um progressivamente mais rigoroso. Nenhum output avança para o próximo nível sem aprovação no anterior.

```
┌─────────────────────────────────────────────────────────────────────────────────┐
│                         CASCATA DE QUALITY GATES                                │
│                                                                                 │
│  Nível 1        Nível 2         Nível 3        Nível 4       Nível 5   Nível 6 │
│                                                                                 │
│  Agent      →   Task Quality →  Domain     →   Chief     →  Cross-  → HRM      │
│  Self-Eval      Gate            Gate           Review        Squad     Gate     │
│  (8 items)      (checklist)     (per-domain)   (aprovação)   Gate      (final)  │
│                                                              (handoff          │
│                                                               rubric)          │
└─────────────────────────────────────────────────────────────────────────────────┘
```

### 12.1 Detalhamento por Nível

| Nível | Nome | Quem Aplica | Quando Aplica | Se Reprovar | Escalação |
|-------|------|-------------|---------------|-------------|-----------|
| 1 | **Agent Self-Eval** | O próprio agente executor | Antes de submeter qualquer output | Agente corrige internamente, sem registro | Não escala — é autocorreção |
| 2 | **Task Quality Gate** | Agente reviewer (definido na task) | Após entrega do output pelo agente | Feedback específico → agente corrige (rework policy: max 3 iterações) | Após 2ª rejeição: Chief notificado |
| 3 | **Domain Gate** | Agente especialista do domínio | Para outputs que cruzam domínios | Reviewer do domínio indica gaps específicos | Se conflito entre domínios: Chief arbitra |
| 4 | **Chief Review** | Movement Chief | Outputs estratégicos (tese, identidade, kill/pivot) | Chief redefine escopo ou realoca recursos | Se bloqueio persistente: Chief escala para stakeholders |
| 5 | **Cross-Squad Gate** | Chief + Architect do squad receptor | Handoffs para outros squads | Handoff rejeitado → Chiefs alinham formato e critérios | Após 2ª rejeição: escalação para HRM Chief |
| 6 | **HRM Gate** | HRM Central Command | Outputs que afetam múltiplos squads ou estratégia global | Retorno com diretrizes de ajuste | Decisão final do HRM Chief |

### 12.2 Regras da Cascata

- **Sequencial e obrigatória:** nenhum nível pode ser pulado.
- **Rework policy ativa:** máximo 3 iterações por nível (ver `config.yaml > rework_policy`).
- **Registro automático:** toda rejeição gera entry em `data/registries/lessons-learned-registry.yaml`.
- **Gates obrigatórios globais:** `movement-thesis-quality`, `identity-system-quality` e `impact-dashboard-quality` são aplicados em TODOS os outputs, independente do domínio.
- **Gates por domínio:** checklists específicos para research, identity, creation, activation, measurement e governance (ver `config.yaml > quality_gates > per_domain`).

---

## 13. MEMÓRIA E LOOP DE APRENDIZADO

O Movement Squad opera com um sistema de memória institucional baseado no ciclo **RalphLoop/Kaizen**. Nada se perde — todo output, decisão, erro e aprendizado alimenta o próximo ciclo.

### 13.1 Como Outputs Viram Registries

```
Output do Agente
    │
    ├──► Aprovado no Quality Gate
    │       │
    │       ├──► Decisão estratégica → data/registries/decision-log.yaml
    │       ├──► Resultado de experimento → data/registries/experiment-log.yaml
    │       ├──► Sinal cultural novo → data/registries/signal-archive.yaml
    │       ├──► Asset validado → data/registries/memetic-assets/ + slogan-bank.yaml
    │       └──► Lição aprendida → data/registries/lessons-learned-registry.yaml
    │
    └──► Rejeitado no Quality Gate
            │
            └──► Rework entry → data/registries/lessons-learned-registry.yaml
                 (causa, correção, prevenção)
```

### 13.2 Como Registries Influenciam Próximas Execuções

Antes de iniciar qualquer tarefa, o agente executor DEVE consultar a memória relevante:

| Ação | Registry a Consultar | Motivo |
|------|----------------------|--------|
| Criar nova tese | `data/registries/movement-theses.yaml` | Evitar repetição, aprender com teses anteriores |
| Novo experimento | `data/registries/experiment-log.yaml` | Não repetir experimentos já feitos, aprender com resultados |
| Criar asset | `data/registries/memetic-assets/` | Reusar e evoluir assets existentes |
| Handoff cross-squad | `data/registries/lessons-learned-registry.yaml` | Evitar erros já documentados |
| Decisão de kill/pivot | `data/registries/decision-log.yaml` | Entender histórico de decisões similares |

### 13.3 Cadência de Registro

| Frequência | O que é Registrado | Onde |
|------------|--------------------|----|
| **Sempre** (a cada output) | Decisões estratégicas, resultados de experimentos, sinais culturais, lessons learned, assets validados | Registries em `data/registries/` |
| **Semanal** | Signal radar, health score snapshot, kaizen loop learnings | `data/registries/signal-archive.yaml`, `data/metrics/weekly-dashboard.md` |
| **Mensal** | Movement health review, community health, business impact | `data/metrics/movement-health-score.md`, `data/metrics/community-growth-quality.md` |
| **Trimestral** | Maturity score, kill/continue review | `data/metrics/maturity-score-history.md`, `data/registries/decision-log.yaml` |

### 13.4 Exemplo de Ciclo Completo de Aprendizado

1. **Semana 1:** Fenomenólogo detecta sinal cultural emergente sobre "fadiga de produtividade tóxica" → registra em `signal-archive.yaml`.
2. **Semana 2:** Architect + Identitário criam tese baseada no sinal → registram em `movement-theses.yaml`. Manifestador cria 3 memes de teste → registra em `memetic-assets/`.
3. **Semana 3:** Analista de Impacto roda experimento A/B com memes em 2 canais → registra design em `experiment-log.yaml`.
4. **Semana 4:** Resultados mostram que meme #2 tem 3x mais compartilhamento. Analista registra resultado em `experiment-log.yaml`. Weekly kaizen identifica padrão: "formato confessional performa melhor que formato imperativo" → registra em `lessons-learned-registry.yaml`.
5. **Próximo ciclo:** Manifestador consulta `lessons-learned-registry.yaml` ANTES de criar novos assets. Usa formato confessional como baseline. Ciclo se repete com dados enriquecidos.

### 13.5 Retenção de Memória

- **Ativa (0-6 meses):** dados ficam em `data/registries/` para acesso direto.
- **Arquivo (>6 meses):** dados movidos para `archive/` para desafogar operação.
- **Permanente (nunca arquivado):** `decision-log`, `experiment-log` e `lessons-learned` — são a memória institucional do squad.

---

## 14. PROTOCOLO GO/NO-GO

O squad utiliza readiness reviews formais em 3 momentos críticos do ciclo de vida de um movimento. Nenhum movimento avança de fase sem aprovação explícita no gate correspondente.

### 14.1 Os 3 Gates de Prontidão

```
┌─────────────────┐     ┌─────────────────┐     ┌─────────────────┐
│   PRE-LAUNCH    │────►│  PRE-SCALING    │────►│   PRE-SUNSET    │
│                 │     │                 │     │                 │
│ "Estamos pron-  │     │ "Podemos esca-  │     │ "Devemos encer- │
│  tos para       │     │  lar com segu-  │     │  rar este movi- │
│  lançar?"       │     │  rança?"        │     │  mento?"        │
│                 │     │                 │     │                 │
│ Chief +         │     │ Chief +         │     │ Chief +         │
│ Architect       │     │ Analista de     │     │ Stakeholder     │
│                 │     │ Impacto         │     │                 │
└─────────────────┘     └─────────────────┘     └─────────────────┘
```

### 14.2 Pre-Launch — Gate de Prontidão para Lançamento

**Quem participa:** Chief + Architect assinam go/no-go.

**Critérios (todos obrigatórios):**
1. Tese validada com no mínimo 5 evidências documentadas
2. Identidade visual e verbal definida e aprovada
3. Manifesto escrito e revisado por Chief + Identitário
4. Mínimo 3 artefatos meméticos prontos para distribuição
5. Comunidade seed com no mínimo 20 membros ativos
6. Canais de distribuição mapeados e configurados
7. Plano 30-60-90 aprovado pelo Chief
8. Dashboard de métricas configurado com baseline
9. Plano de crise/backlash documentado
10. Protocolo de moderação ativo

**Formato:** reunião estruturada com checklist. Cada item é marcado como pass/fail com evidência.

### 14.3 Pre-Scaling — Gate de Prontidão para Scaling

**Quem participa:** Chief + Analista de Impacto assinam.

**Critérios (todos obrigatórios):**
1. Health Score >60 por no mínimo 4 semanas consecutivas
2. Taxa de retenção da comunidade >50% em 90 dias
3. No mínimo 3 champions ativos (tier silver+)
4. Content-to-conversation rate >15%
5. Unit economics validado (CAC vs LTV do movimento)
6. Infraestrutura de moderação escala com crescimento

### 14.4 Pre-Sunset — Gate de Confirmação de Sunset

**Quem participa:** Chief + Stakeholder assinam.

**Critérios (todos obrigatórios):**
1. Health Score <30 por no mínimo 60 dias
2. No mínimo 3 tentativas de pivot documentadas e falhadas
3. Análise de impacto na comunidade existente
4. Plano de transição/legado documentado
5. Stakeholders informados e alinhados

### 14.5 Registro e Referência

- **Onde registrar:** `data/readiness-reviews/`
- **Protocolo completo:** [docs/readiness-review-protocol.md](docs/readiness-review-protocol.md)
- **Decisões de go/no-go:** também registradas em `data/registries/decision-log.yaml`

---

## 15. GESTÃO DE RISCOS

O Movement Squad gerencia riscos operacionais de forma contínua, com categorização, registro e mitigação estruturados.

### 15.1 Categorias de Risco

| Categoria | Descrição | Exemplos | Agente Monitor |
|-----------|-----------|----------|----------------|
| **Reputacional** | Dano à imagem da marca ou do movimento | Backlash cultural, associação indesejada, apropriação de causa | Chief + Architect |
| **Operacional** | Falhas no processo do squad | Agente sobrecarregado, quality gate quebrado, handoff falhado | Chief |
| **Legal** | Riscos jurídicos ou de compliance | Uso indevido de imagem, claims sem prova, violação de dados | Chief → Jurídico |
| **Cultural** | Leitura errada de sinais ou tensões | Movimento que ofende grupo, tom surdo, timing errado | Fenomenólogo + Identitário |
| **Financeiro** | Investimento sem retorno mensurável | Budget estourado, CAC insustentável, ROI negativo | Analista de Impacto + Chief |

### 15.2 Processo de Gestão

```
Identificar → Registrar → Classificar → Mitigar → Monitorar → Revisar
    │              │            │            │           │          │
    ▼              ▼            ▼            ▼           ▼          ▼
 Qualquer     risk-log     Severidade   Plano de    Dashboard   Revisão
 agente       .yaml        + Probab.    ação        semanal     mensal
 detecta                   + Impacto    concreto    no radar    no review
```

**Como identificar:**
- Qualquer agente pode identificar um risco a qualquer momento durante a execução.
- Sinais de risco incluem: feedback negativo recorrente, queda em métricas, sinais culturais de rejeição, conflitos internos repetidos, compliance flags.

**Como registrar:**
- Todo risco identificado é registrado em `data/risk-log.yaml` com: descrição, categoria, severidade (1-5), probabilidade (1-5), impacto potencial, responsável pela mitigação, status.

**Como mitigar:**
- Riscos com severidade x probabilidade >= 12: mitigação imediata + Chief notificado.
- Riscos com severidade x probabilidade >= 8: plano de mitigação em 7 dias.
- Riscos com severidade x probabilidade < 8: monitoramento contínuo.

**Como escalar:**
- Risco reputacional confirmado → pausar execução, Chief decide próximo passo.
- Risco legal identificado → pausar, consultar jurídico, documentar (ver `config.yaml > escalation_rules`).
- Risco financeiro >20% do budget → Chief escala para stakeholders.

### 15.3 Referências

- **Registro de riscos:** `data/risk-log.yaml`
- **Taxonomia de riscos:** [lib/taxonomies/risk-taxonomy.md](lib/taxonomies/risk-taxonomy.md)
- **Checklists relacionados:** `checklists/governance/ethics-and-boundaries.md`, `checklists/pr/backlash-mitigation.md`
- **Plano de crise:** `templates/plans/crisis-response-plan.md`

---

## 16. MATRIZ DE DELEGAÇÃO E ESCALAÇÃO

Esta matriz define quem decide o quê no Movement Squad, e quando escalar para um nível superior. Referência completa em `config.yaml` nas seções `escalation_rules` e `delegation_rules`.

### 16.1 Matriz de Decisão

| Tipo de Decisão | Agent (autônomo) | Chief (decide) | Stakeholder (aprova) |
|-----------------|:----------------:|:--------------:|:--------------------:|
| Execução dentro do escopo delegado | **DECIDE** | Informado | — |
| Escolha de framework/método para task | **DECIDE** | — | — |
| Priorização do backlog | — | **DECIDE** | Informado |
| Win conditions e métricas de sucesso | — | **DECIDE** | Informado |
| Aprovação final de tese | Propõe | **DECIDE** | — |
| Aprovação de identidade do movimento | Propõe | **DECIDE** | — |
| Conflitos entre agentes | — | **DECIDE** | — |
| Alocação de recursos entre tasks | — | **DECIDE** | — |
| Outputs que afetam cross-squad | Propõe | **APROVA** | — |
| Kill/pivot de movimento | Recomenda | Recomenda | **DECIDE** |
| Investimento >R$100K ou >6 meses | — | Propõe | **DECIDE** |
| Risco legal ou compliance | Identifica | Pausa + documenta | **DECIDE** |
| Budget >20% do previsto | Identifica | Escala | **DECIDE** |
| Conflito cross-squad não resolvido | — | Tenta resolver | **DECIDE** (HRM Chief) |

### 16.2 Níveis de Autonomia

| Nível | Descrição | Exemplos |
|-------|-----------|----------|
| **Autonomia Total** | Agente executa sem aprovação prévia | Pesquisa cultural, criação de draft, análise de métricas, execução dentro do escopo delegado |
| **Aprovação Necessária** | Agente executa, Chief aprova antes de publicar/entregar | Outputs que afetam identidade, tese, cross-squad handoffs |
| **Somente Chief** | Apenas Chief pode decidir | Kill decisions, budget >20%, comunicação com stakeholders |

### 16.3 Regras de Escalação

| Condição | De → Para | Ação |
|----------|-----------|------|
| Risco reputacional identificado | Agent → Chief | Pausar execução, notificar Chief imediatamente |
| Conflito entre agentes sobre direção | Agent → Chief | Chief arbitra com base em win conditions |
| Output reprovado 2x no mesmo quality gate | Agent → Chief | Chief revisa escopo e realoca recursos |
| Sinal cultural com potencial de tese | Fenomenólogo → Architect + Chief | Avaliar viabilidade e priorizar |
| Budget necessário >20% do previsto | Agent → Chief → Stakeholder | Chief escala para stakeholders |
| Kill/pivot de movimento ativo | Chief → Stakeholder | Apresentar dados + recomendação |
| Investimento >R$100K ou >6 meses | Chief → Stakeholder | Business case formal + aprovação |
| Risco legal ou compliance | Chief → Jurídico + Stakeholder | Pausar, consultar jurídico, documentar |
| Handoff rejeitado 2x | Chief → Chief receptor | Chiefs alinham formato e critérios |
| Dependência bloqueante de outro squad | Chief → Chief receptor | Notificar + deadline, escalar se não resolvido em 48h |

### 16.4 Delegação por Agente

| Agente | Escopo Delegado |
|--------|----------------|
| **Movement Architect** | Design de sistema, loops, coerência, arquitetura de canais |
| **Fenomenólogo** | Pesquisa cultural, sinais, linguagem, tensões |
| **Identitário** | Sistema de identidade, símbolos, pertencimento |
| **Estrategista de Ciclo** | Timing, cadência, janelas de atenção, sazonalidade |
| **Manifestador** | Criação de artefatos, manifestos, memes, rituais |
| **Analista de Impacto** | Métricas, experimentos, atribuição, health score |
