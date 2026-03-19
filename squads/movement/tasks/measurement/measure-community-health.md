---
id: measure-community-health
name: "Medir Saúde da Comunidade"
squad: movement
type: task
category: measurement
agents: [analista-de-impacto, movement-architect]
frameworks: [community-flywheel, impact-cohort-analysis]
checklists: [comunidade/community-health-indicators, impacto/vanity-metric-filter]
templates: [reports/community-health-report]
registry: [data/metrics/community-growth-quality]
version: "1.0"
tags: [measurement, comunidade, saude, engajamento, retencao, membros]
---

# Medir Saúde da Comunidade

## Objetivo

Monitorar e analisar a saúde da comunidade do movimento em profundidade — indo além de membros totais para medir qualidade do engajamento, retenção, contribuição ativa e sentimento — garantindo que a comunidade esteja genuinamente viva e não apenas numericamente grande.

## Contexto

Uma comunidade com 10.000 membros e 50 ativos é menos saudável que uma com 500 membros e 200 ativos. Saúde comunitária é sobre profundidade, não amplitude. Este task monitora os sinais vitais que indicam se a comunidade está florescendo ou definhando — antes que seja tarde para agir.

## Inputs Necessários

- Dados de plataformas comunitárias (Discord, Telegram, forum, etc.)
- Histórico de participação em rituais
- Dados de onboarding (conclusão, retenção)
- Feedback qualitativo de membros
- Dados de champions (atividade, satisfação)
- Benchmarks de comunidades referência

## Processo

1. **Definir métricas de saúde comunitária** — Acompanhar: (a) DAU/MAU ratio (membros ativos diários vs. mensais), (b) Taxa de contribuição (% que posta, não só lê), (c) Retenção por coorte (D7, D30, D90), (d) Tempo até primeira contribuição, (e) Net member growth (entradas - saídas), (f) Sentimento geral.

2. **Segmentar por camada** — Medir separadamente: observadores, participantes, contribuidores, champions. Cada camada tem benchmarks diferentes. Uma comunidade saudável tem distribuição piramidal, não plana.

3. **Analisar retenção por coorte** — Agrupar membros por semana/mês de entrada e rastrear: quantos ainda estão ativos em 7/30/60/90 dias. Identificar se coortes recentes retêm melhor ou pior que anteriores.

4. **Medir qualidade do engajamento** — Diferenciar: (a) Engajamento raso (emoji react, curtida), (b) Engajamento médio (comentário breve, participação em enquete), (c) Engajamento profundo (post longo, conteúdo criado, mentoria de novo membro).

5. **Monitorar sentimento** — Analisar tom das conversas: (a) Amostra semanal de 50 mensagens categorizadas (positivo/neutro/negativo), (b) Reclamações recorrentes, (c) Elogios espontâneos, (d) Nível de humor saudável vs. cinismo.

6. **Rastrear fluxo de membros** — Documentar: (a) De onde vêm (referral, orgânico, paid, creator), (b) Quando saem e por quê (pesquisa de exit quando possível), (c) Picos de entrada e saída correlacionados com ações do movimento.

7. **Avaliar saúde dos champions** — Medir especificamente: nível de atividade, satisfação (pesquisa trimestral), sinais de burnout, taxa de rotatividade, pipeline de novos champions.

8. **Conduzir pulse survey** — Mensalmente, rodar pesquisa rápida (3-5 perguntas) para membros ativos: NPS da comunidade, o que mais gosta, o que mudaria, probabilidade de recomendar.

9. **Comparar com benchmarks** — Contrastar métricas com: (a) Mês anterior (tendência), (b) Benchmark de comunidades similares, (c) Metas definidas nas Win Conditions.

10. **Produzir Community Health Report** — Mensalmente: relatório com todas as métricas, análise de tendências, diagnóstico de problemas, recomendações de ação, destaque de membros exemplares.

## Outputs Esperados

- **Dashboard de saúde comunitária** atualizado
- **Análise de coortes** por período de entrada
- **Pulse survey** resultados mensais
- **Community Health Report** mensal
- **Alertas** de métricas em queda
- **Recomendações acionáveis** por problema

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Métricas rastreadas | >= 6 métricas core |
| Análise de coorte | Atualizada mensalmente |
| Pulse survey | Rodado mensalmente com >= 20% resposta |
| DAU/MAU ratio | >= 20% para comunidade saudável |
| Community Health Report | Entregue mensalmente |
| Tempo de ação em alerta | <= 1 semana |

## Decision Points

- **Retenção D30 caindo** → Investigar onboarding e primeiros 7 dias
- **Contribuição caindo** → Avaliar se rituais estão engajantes e se há provocações suficientes
- **Champions com burnout** → Ativar backup e revisar carga
- **Sentimento deteriorando** → Investigar causa raiz e intervir rapidamente

## Integração

| Tipo | Referência |
|------|-----------|
| **Frameworks** | `frameworks/community-flywheel.md`, `frameworks/impact-cohort-analysis.md` |
| **Checklists** | `checklists/comunidade/community-health-indicators.md`, `checklists/impacto/vanity-metric-filter.md` |
| **Templates** | `templates/reports/community-health-report.md` |
| **Registries** | `data/metrics/community-growth-quality.md` |
| **Workflows** | `workflows/04-measure-and-learn.md` |

### Regras de Fluxo
- **Rework:** Se quality gate reprovar → revisar metodologia, corrigir viés identificado e reexecutar análise
- **Escalation:** Se bloqueio ou decisão fora de escopo → escalar para Movement Chief
- **Handoff:** Output vai para → tasks de Review (impact-review) e próximo ciclo de Strategy
