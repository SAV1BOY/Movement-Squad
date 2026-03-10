---
id: analyze-cohort-retention
name: "Analisar Retenção por Coorte"
squad: movement
type: task
category: measurement
agents: [analista-impacto]
frameworks: [cohort-analysis-framework, retention-curve-model]
checklists: [cohort-analysis-checklist]
templates: [cohort-table-template, retention-report-template]
version: "1.0"
tags: [measurement, coortes, retencao, analise, membros, engajamento]
---

# Analisar Retenção por Coorte

## Objetivo

Analisar a retenção de membros do movimento por coorte — agrupando por período de entrada e rastreando seu engajamento ao longo do tempo — para identificar padrões, diagnosticar problemas de retenção e otimizar a experiência em cada estágio da jornada.

## Contexto

Média de retenção esconde a verdade. Uma comunidade pode ter 50% de retenção mensal, mas se a coorte de janeiro retém 80% e a de março retém 20%, há um problema grave que a média não revela. Análise de coorte é o microscópio que mostra o que está realmente acontecendo.

## Inputs Necessários

- Dados de entrada de membros com data de ingresso
- Dados de atividade por membro ao longo do tempo
- Dados de marcos de integração (onboarding steps)
- Changelog de ações do movimento (para correlacionar)
- Dados de exit/churn quando disponíveis
- Community Health Report mais recente

## Processo

1. **Definir coortes** — Agrupar membros por: semana ou mês de entrada. Para movimentos jovens (< 6 meses), usar coortes semanais. Para maduros, coortes mensais. Cada coorte é um grupo distinto.

2. **Definir "ativo"** — Estabelecer definição clara: o que conta como "ativo" em cada período? Login? Postagem? Participação em ritual? Reação em conteúdo? Definir threshold mínimo.

3. **Construir tabela de coorte** — Montar matrix: linhas = coortes, colunas = períodos (D1, D7, D14, D30, D60, D90). Cada célula = % de membros da coorte que ainda estão ativos naquele período.

4. **Plotar curvas de retenção** — Visualizar curvas sobrepostas de cada coorte. Identificar: a curva está melhorando ao longo dos coortes? Há um "cliff" em algum período específico? Onde a curva estabiliza?

5. **Identificar padrões** — Buscar: (a) Coortes com retenção atipicamente alta ou baixa, (b) Período em que mais membros abandonam (o "cliff"), (c) Tendência geral: coortes recentes retêm melhor ou pior?

6. **Correlacionar com ações** — Para coortes atípicas, cruzar com: o que estava acontecendo no movimento naquela semana/mês? Mudou algo no onboarding? Houve evento especial? Houve crise?

7. **Analisar marcos de integração** — Para membros retidos vs. perdidos, comparar: quantos completaram onboarding, quantos participaram do primeiro ritual, quantos fizeram primeira contribuição. Identificar ações que predizem retenção.

8. **Investigar churners** — Para membros que saíram: (a) Em que momento saíram, (b) Qual era seu nível de engajamento antes de sair, (c) Se responderam pesquisa de exit, quais razões deram.

9. **Formular hipóteses de melhoria** — Com base nos dados: "Se melhorarmos X no período Y, a retenção da coorte deveria melhorar em Z%". Cada hipótese vira candidata a experimento.

10. **Produzir Cohort Retention Report** — Mensal: tabela de coorte atualizada, curvas de retenção, análise de padrões, correlações com ações, hipóteses de melhoria, ações recomendadas.

## Outputs Esperados

- **Tabela de coorte** atualizada mensalmente
- **Curvas de retenção** visualizadas
- **Análise de padrões** documentada
- **Correlações com ações** do movimento
- **Hipóteses de melhoria** formuladas
- **Cohort Retention Report** mensal

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Coortes analisadas | Todas desde o início do movimento |
| Períodos rastreados | D1, D7, D30, D60, D90 |
| Definição de "ativo" | Clara e consistente |
| Correlações | >= 3 ações correlacionadas |
| Hipóteses formuladas | >= 2 por report |
| Report mensal | Entregue |

## Decision Points

- **Retenção D7 < 50%** → Problema grave de onboarding — priorizar redesign
- **Cliff em D30** → Investigar o que acontece no 2o mês (falta de novidade? fadiga de ritual?)
- **Coorte com retenção excepcionalmente alta** → Analisar o que foi diferente e replicar
- **Tendência geral de piora** → Alarme — o movimento está perdendo relevância

## Integração

- **Alimenta:** `measure-community-health`, `create-onboarding-experience`, `run-experiments`
- **Recebe de:** `activate-community`, `create-community-rituals`
- **Workflow relacionado:** `04-measure-and-learn`, `08-community-build-and-nurture`
- **Cadência:** Mensal (report completo), semanal (monitoramento de coorte ativa)
- **Handoff:** Report vai para community builder, analista e Arquiteto de Movimento
