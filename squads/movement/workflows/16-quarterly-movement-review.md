---
id: quarterly-movement-review
name: "Review Trimestral: Saúde, Impacto e Atualização Estratégica"
squad: movement
type: workflow
agents: [movement-architect, estrategista-de-ciclo, analista-de-impacto, manifestador]
cadence: quarterly
version: "1.0"
tags: [workflow, trimestral, review, estrategia, saude, impacto]
---

# Review Trimestral: Saúde, Impacto e Atualização Estratégica

## Objetivo

Conduzir o review estratégico trimestral que avalia todas as dimensões do movimento — saúde, impacto, thesis, comunidade, artefatos — e define a direção estratégica para o próximo trimestre.

## Diagrama de Fases

```
[PRÉ-WORK]        [SESSÃO DIA 1]    [SESSÃO DIA 2]    [PÓS-SESSÃO]
Consolidar     →   Retrospectiva →   Estratégia    →   Documentar
Dados              e Diagnóstico     e Planejamento     e Comunicar
   |                  |                  |                  |
   v                  v                  v                  v
90 dias de        O que fizemos,    Thesis review,    OKRs, roadmap,
dados, reports,   o que aprendemos, win conditions,   strategy update,
pre-read          o que impactamos  próximos passos   stakeholder deck
```

## Fases Detalhadas

### Pré-Work: Consolidação de Dados (Semana -1)

**Agentes:** analista-de-impacto

**Inputs:**
- 3 Monthly Reviews do trimestre
- Health Score com tendência de 90 dias
- Business Impact Report acumulado
- Cohort Retention tendência
- Competitor Audit atualizado
- Signal Reports do trimestre

**Ações:**
1. Consolidar todos os dados em deck de review: métricas-chave com tendência, wins e fails, learnings acumulados
2. Preparar comparativo: Win Conditions vs. realizado
3. Preparar análise de cenário externo (mercado, concorrentes, tendências)
4. Enviar pre-read para todo o squad 48h antes

**Outputs:**
- Deck de review consolidado
- Pre-read distribuído

**Decision Gate:**
- Dados completos → sessão pode acontecer
- Dados faltantes → completar e remarcar se necessário

### Sessão Dia 1: Retrospectiva e Diagnóstico (2-3h)

**Agentes:** todo o squad core

**Inputs:**
- Deck de review (pre-read)
- Percepções individuais de cada membro

**Ações:**
1. Apresentar Health Score de 90 dias e principais tendências
2. Revisar Win Conditions: atingimos, superamos ou ficamos abaixo?
3. Analisar top 5 wins do trimestre com fatores de sucesso
4. Analisar top 5 fails do trimestre com causas raiz
5. Avaliar saúde da comunidade: crescimento, retenção, champions, sentimento
6. Avaliar impacto em negócio: ROI, conversão, brand metrics
7. Sessão de retrospectiva: "O que nos orgulha? O que nos incomoda? O que nos surpreendeu?"

**Outputs:**
- Diagnóstico do trimestre documentado
- Wins e fails com causas
- Sentimento do squad capturado

**Decision Gate:**
- Diagnóstico claro → avançar para estratégia no Dia 2
- Pontos controversos → resolver antes de planejar futuro

### Sessão Dia 2: Estratégia e Planejamento (2-3h)

**Agentes:** todo o squad core

**Inputs:**
- Diagnóstico do Dia 1
- Trend Radar e cenário externo
- Thesis Document para revisão

**Ações:**
1. Avaliar thesis: ainda relevante? Precisa evoluir? Precisa pivotar?
2. Revisar cenário externo: o que mudou no mercado, concorrentes, cultura?
3. Tomar decisões estratégicas: thesis, scaling, investimento, foco
4. Definir 3-5 OKRs para o próximo trimestre
5. Definir prioridades de cada dimensão (pesquisa, criação, ativação, comunidade, medição)
6. Alocar recursos e responsabilidades
7. Definir calendário de marcos do próximo trimestre

**Outputs:**
- Decisões estratégicas documentadas
- OKRs do Q+1 definidos
- Prioridades por dimensão
- Calendário de marcos

**Decision Gate:**
- Consenso estratégico → documentar e comunicar
- Sem consenso → sessão adicional ou decisão do Arquiteto

### Pós-Sessão: Documentação e Comunicação (Semana +1)

**Agentes:** movement-architect, estrategista-de-ciclo

**Inputs:**
- Notas e decisões das sessões
- OKRs e prioridades definidos

**Ações:**
1. Produzir Quarterly Review Report completo
2. Produzir Strategy Update (1 página) para o squad
3. Produzir Executive Summary para stakeholders
4. Atualizar roadmap e todos os documentos afetados pelas decisões
5. Agendar apresentação para stakeholders
6. Comunicar OKRs e prioridades para squads parceiros

**Outputs:**
- Quarterly Review Report
- Strategy Update
- Executive Summary
- Roadmap atualizado
- Comunicação distribuída

**Decision Gate:**
- Tudo documentado e comunicado → Q+1 pode começar
- Stakeholders pedem ajustes → incorporar e redistribuir

## Cadência

- **Pré-work:** Semana anterior ao review
- **Sessões:** 2 meios-dias consecutivos (ou 1 dia inteiro)
- **Pós-sessão:** Semana seguinte
- **Frequência:** Trimestral (fim de Q)

## Artefatos Produzidos

- Quarterly Review Report
- Strategy Update
- Executive Summary
- OKRs do Q+1
- Roadmap atualizado
- Decision Log atualizado

## Métricas de Sucesso

| Métrica | Meta |
|---------|------|
| Dados consolidados para review | 100% |
| Participação | Todo o squad core |
| OKRs definidos | 3-5 com key results mensuráveis |
| Strategy Update distribuído | <= 1 semana pós-sessão |
| Stakeholder presentation | Realizada |
| Satisfação do squad com direção | >= 8/10 |

## Integração

| Tipo | Referência |
|------|-----------|
| **Tasks** | `tasks/operations/quarterly-movement-review.md`, `tasks/review/impact-review.md`, `tasks/review/narrative-consistency-review.md`, `tasks/review/community-health-review.md`, `tasks/review/artifact-freshness-review.md`, `tasks/review/crisis-readiness-review.md`, `tasks/measurement/measure-movement-health.md`, `tasks/measurement/measure-business-impact.md` |
| **Frameworks** | `frameworks/movement-lifecycle-framework.md`, `frameworks/governance-layer.md`, `frameworks/movement-health-score-framework.md`, `frameworks/impact-metrics-model.md`, `frameworks/ralphloop-kaizen.md` |
| **Checklists** | `checklists/chief/chief-kill-criteria.md`, `checklists/impact-dashboard-quality.md`, `checklists/chief/chief-win-condition.md`, `checklists/chief/chief-alignment-with-business.md` |
| **Registries** | `data/metrics/maturity-score-history.md`, `data/metrics/movement-health-score.md`, `data/metrics/business-impact.md`, `data/registries/decision-log.yaml` |

### Regras de Fluxo
- **Quality Gate entre fases:** Pré-work→Sessão: dados completos e pre-read distribuído; Dia 1→Dia 2: diagnóstico claro; Pós-sessão: tudo documentado e comunicado
- **Rework:** Se pontos controversos no Dia 1 → resolver antes de planejar futuro no Dia 2
- **Escalation:** Se decisão de kill/pivot → escalar para stakeholders com dados e recomendação
- **Handoff:** OKRs e Strategy Update alimentam → todos os workflows do próximo trimestre
