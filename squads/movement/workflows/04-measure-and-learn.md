---
id: measure-and-learn
name: "Medir e Aprender: Métricas, Coortes e Experimentos"
squad: movement
type: workflow
agents: [analista-impacto, estrategista-movimento, community-builder]
cadence: weekly
version: "1.0"
tags: [workflow, medicao, aprendizado, metricas, coortes, experimentos]
---

# Medir e Aprender: Métricas, Coortes e Experimentos

## Objetivo

Operar o ciclo contínuo de medição, análise e aprendizado do movimento — integrando health score, análise de coortes, business impact e experimentos num fluxo que transforma dados em decisões e decisões em ações.

## Diagrama de Fases

```
[FASE 1]          [FASE 2]          [FASE 3]          [FASE 4]
Coleta de     →   Análise e     →   Insights e    →   Ações e
Dados             Diagnóstico       Experimentos      Comunicação
   |                 |                  |                  |
   v                 v                  v                  v
Dashboards       Health Score,      Hipóteses          Ajustes
atualizados      coortes,           testadas,          implementados,
                 tendências         readouts            reports
                 analisadas         produzidos          distribuídos
```

## Fases Detalhadas

### Fase 1: Coleta de Dados (Contínua + Consolidação Semanal)

**Agentes:** analista-impacto

**Inputs:**
- APIs e integrações com plataformas
- Dados de comunidade
- Dados de business (CRM, analytics)
- Dados de social listening
- Dados de experimentos em andamento

**Ações:**
1. Verificar integridade das coletas automáticas (dashboards, APIs)
2. Coletar dados manuais que não são automatizados
3. Consolidar dados da semana em formato padronizado
4. Verificar anomalias e dados faltantes
5. Atualizar dashboards com dados frescos

**Outputs:**
- Dashboards atualizados
- Dados consolidados da semana
- Anomalias sinalizadas

**Decision Gate:**
- Dados completos → avançar para análise
- Dados faltantes → investigar e documentar gap

### Fase 2: Análise e Diagnóstico (Semanal)

**Agentes:** analista-impacto, estrategista-movimento

**Inputs:**
- Dashboards atualizados
- Health Score anterior para comparação
- Tabela de coortes
- Win Conditions vigentes

**Ações:**
1. Calcular Health Score semanal e comparar com semana anterior
2. Atualizar tabela de coortes com dados da semana
3. Analisar métricas de comunidade: DAU/MAU, contribuição, retenção
4. Analisar content-to-conversation: quais conteúdos geraram diálogo
5. Analisar business impact: funil de conversão, CAC, atribuição
6. Para métricas em queda: diagnosticar causa provável
7. Para métricas em alta: identificar fator de sucesso

**Outputs:**
- Health Score semanal com tendência
- Coortes atualizadas
- Diagnóstico de métricas em alerta
- Fatores de sucesso identificados

**Decision Gate:**
- Health Score estável/subindo → manter curso
- Health Score em queda → formular hipóteses de intervenção
- Anomalia detectada → investigação profunda

### Fase 3: Insights e Experimentos (Semanal/Quinzenal)

**Agentes:** analista-impacto, estrategista-movimento

**Inputs:**
- Diagnósticos da Fase 2
- Backlog de hipóteses
- Resultados de experimentos em andamento

**Ações:**
1. Analisar resultados de experimentos que concluíram nesta semana
2. Produzir readouts para experimentos finalizados
3. Formular novas hipóteses a partir dos diagnósticos
4. Priorizar próximos experimentos pelo framework impacto x custo
5. Projetar próximo experimento (variáveis, amostra, duração, métrica)
6. Lançar novo experimento se há slot disponível

**Outputs:**
- Readouts de experimentos concluídos
- Novas hipóteses formuladas
- Próximo experimento projetado/lançado
- Banco de aprendizados atualizado

**Decision Gate:**
- Hipótese confirmada → implementar mudança permanente
- Hipótese refutada → documentar e pivotar
- Resultado inconclusivo → redesenhar teste com mais rigor

### Fase 4: Ações e Comunicação (Semanal)

**Agentes:** analista-impacto, arquiteto-movimento

**Inputs:**
- Health Score e diagnósticos da semana
- Readouts de experimentos
- Ações recomendadas

**Ações:**
1. Transformar diagnósticos em ações concretas (quem, o quê, quando)
2. Alimentar kaizen semanal com insights e recomendações
3. Produzir weekly metrics brief (1 página) para o squad
4. Atualizar dashboards acessíveis a todo o squad
5. Sinalizar itens que precisam entrar no monthly review

**Outputs:**
- Weekly metrics brief distribuído
- Ações definidas com responsáveis
- Inputs para kaizen semanal
- Itens sinalizados para monthly review

**Decision Gate:**
- Ações implementáveis → squad executa na semana seguinte
- Ações que exigem mudança estratégica → escalar para monthly review

## Cadência

| Ação | Frequência | Responsável |
|------|-----------|------------|
| Coleta automática | Diária | Automações |
| Consolidação manual | Semanal (segunda) | Analista |
| Health Score | Semanal (terça) | Analista |
| Análise de coortes | Mensal | Analista |
| Experimentos | Quinzenal (ciclo) | Analista + Estrategista |
| Weekly brief | Semanal (quarta) | Analista |
| Monthly report | Mensal (última semana) | Analista + Estrategista |

## Artefatos Produzidos

- Health Score semanal
- Weekly Metrics Brief
- Cohort Analysis (mensal)
- Experiment Readouts
- Business Impact Report (mensal)
- Content-to-Conversation Analysis (mensal)
- Learning Log atualizado

## Métricas de Sucesso

| Métrica | Meta |
|---------|------|
| Health Score atualizado | Toda semana sem falha |
| Weekly brief entregue | Toda quarta |
| Experimentos/mês | >= 2 |
| Readouts produzidos | 100% dos experimentos |
| Tempo de diagnóstico a ação | <= 1 semana |
| Ações implementadas | >= 80% das recomendadas |

## Integração

| Tipo | Referência |
|------|-----------|
| **Tasks** | `tasks/measurement/run-experiments.md`, `tasks/measurement/measure-movement-health.md`, `tasks/measurement/measure-community-health.md`, `tasks/measurement/measure-business-impact.md`, `tasks/measurement/analyze-cohort-retention.md`, `tasks/measurement/analyze-content-to-conversation.md` |
| **Frameworks** | `frameworks/impact-experiment-design.md`, `frameworks/impact-learning-loop.md`, `frameworks/movement-health-score-framework.md`, `frameworks/impact-cohort-analysis.md`, `frameworks/impact-metrics-model.md`, `frameworks/impact-movement-attribution.md` |
| **Checklists** | `checklists/experimentation-quality.md`, `checklists/impacto/experiment-readout.md`, `checklists/impact-dashboard-quality.md`, `checklists/impacto/vanity-metric-filter.md`, `checklists/impacto/cohort-and-retention.md`, `checklists/impacto/causal-attribution-sanity.md` |
| **Registries** | `data/registries/experiment-log.yaml`, `data/metrics/movement-health-score.md`, `data/metrics/community-growth-quality.md`, `data/metrics/business-impact.md`, `data/metrics/cohort-retention.md`, `data/metrics/content-to-conversation.md` |

### Regras de Fluxo
- **Quality Gate entre fases:** Fase 1→2: dados completos; Fase 2→3: diagnóstico claro; Fase 3→4: readouts produzidos com veredicto claro
- **Rework:** Se resultado de experimento inconclusivo → redesenhar teste com mais rigor ou mais amostra
- **Escalation:** Se Health Score em queda crítica (<25) → reunião emergencial com Movement Chief
- **Handoff:** Insights e recomendações alimentam → `workflows/05-ralphloop-kaizen-weekly.md` e `workflows/16-quarterly-movement-review.md`
