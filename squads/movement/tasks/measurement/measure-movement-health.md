---
id: measure-movement-health
name: "Medir Health Score do Movimento"
squad: movement
type: task
category: measurement
agents: [analista-impacto, estrategista-movimento]
frameworks: [movement-health-scorecard, vitality-index-model]
checklists: [health-measurement-checklist]
templates: [health-scorecard-template, dashboard-template]
version: "1.0"
tags: [measurement, saude, health-score, metricas, dashboard, vitalidade]
---

# Medir Health Score do Movimento

## Objetivo

Calcular e acompanhar o Health Score do movimento — um índice composto que captura a vitalidade geral do movimento através de múltiplas dimensões — servindo como termômetro principal para decisões estratégicas.

## Contexto

Métricas isoladas (followers, likes, impressões) não contam a história completa de um movimento. O Health Score agrega múltiplas dimensões em um índice único que responde: "O movimento está vivo, crescendo e saudável?" Um score alto com crescimento estável indica que o investimento está valendo. Um score em queda é alerta para ação.

## Inputs Necessários

- Dados de todas as plataformas e canais do movimento
- Métricas de comunidade (participação, retenção, contribuição)
- Dados de engajamento com conteúdo
- Métricas de creator partnerships
- Dados de PR e earned media
- Dados de business impact (se disponíveis)

## Processo

1. **Definir dimensões do Health Score** — Estabelecer 5-7 dimensões: (a) Alcance narrativo (share of conversation, menções), (b) Profundidade de engajamento (comments/saves vs. likes), (c) Vitalidade comunitária (membros ativos, contribuição, retenção), (d) Ressonância cultural (UGC, remixes, organic spread), (e) Impacto de negócio (leads, trials, NPS).

2. **Definir métricas por dimensão** — Para cada dimensão, selecionar 3-5 métricas concretas com fonte de dados, frequência de coleta e responsável. Priorizar métricas de profundidade sobre vaidade.

3. **Estabelecer pesos** — Atribuir peso a cada dimensão no score composto. Pesos refletem prioridades estratégicas do momento: fase de lançamento pesa mais alcance, fase madura pesa mais comunidade.

4. **Definir escalas e benchmarks** — Para cada métrica, definir: escala (0-100), benchmarks de referência, thresholds (verde >= 70, amarelo 50-69, vermelho < 50).

5. **Configurar coleta de dados** — Implementar: integrações com plataformas, dashboards automatizados, processos manuais para métricas qualitativas, cadência de coleta.

6. **Calcular primeiro Health Score** — Rodar o cálculo pela primeira vez. Validar se o score reflete a percepção real do squad. Se muito otimista ou pessimista, recalibrar pesos e escalas.

7. **Criar dashboard visual** — Montar dashboard com: Health Score geral (big number), score por dimensão, tendência temporal (últimas 4-12 semanas), alertas automáticos, drill-down por métrica.

8. **Analisar tendências** — Mais importante que o número absoluto é a tendência: está subindo, estável ou caindo? Identificar quais dimensões puxam para cima e quais para baixo.

9. **Gerar insights acionáveis** — Para cada dimensão em amarelo ou vermelho, diagnosticar: por que está baixa? O que mudou? O que podemos fazer nas próximas 2 semanas para melhorar?

10. **Reportar e decidir** — Semanalmente: compartilhar Health Score com squad. Mensalmente: report completo para stakeholders com análise, diagnóstico e recomendações.

## Outputs Esperados

- **Health Score** calculado e atualizado
- **Dashboard** visual configurado
- **Report semanal** para o squad
- **Report mensal** para stakeholders
- **Diagnóstico** por dimensão com ações
- **Histórico de tendência** documentado

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Dimensões cobertas | >= 5 dimensões |
| Métricas por dimensão | >= 3 métricas com fonte real |
| Dashboard funcional | Atualizado automaticamente ou semanalmente |
| Report semanal | 100% entregues |
| Insights acionáveis | >= 2 por report |
| Calibração | Validada pelo squad |

## Decision Points

- **Health Score > 80 e subindo** → Manter curso e considerar aceleração de scaling
- **Health Score 60-80 e estável** → Operação normal com otimizações pontuais
- **Health Score 40-60 e caindo** → Alerta — diagnosticar e agir em até 1 semana
- **Health Score < 40** → Crise — reunião emergencial e possível pivot

## Integração

| Tipo | Referência |
|------|-----------|
| **Frameworks** | `frameworks/movement-health-score-framework.md`, `frameworks/impact-cohort-analysis.md` |
| **Checklists** | `checklists/impact-dashboard-quality.md`, `checklists/impacto/vanity-metric-filter.md` |
| **Templates** | `templates/reports/movement-health-dashboard.md` |
| **Registries** | `data/metrics/movement-health-score.md` |
| **Workflows** | `workflows/04-measure-and-learn.md` |

### Regras de Fluxo
- **Rework:** Se quality gate reprovar → revisar metodologia, corrigir viés identificado e reexecutar análise
- **Escalation:** Se bloqueio ou decisão fora de escopo → escalar para Movement Chief
- **Handoff:** Output vai para → tasks de Review (impact-review) e próximo ciclo de Strategy
