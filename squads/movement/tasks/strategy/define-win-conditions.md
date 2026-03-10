---
id: define-win-conditions
name: "Definir Condições de Vitória 30/60/90"
squad: movement
type: task
category: strategy
agents: [arquiteto-movimento, estrategista-movimento, analista-impacto]
frameworks: [win-condition-framework, okr-movement-model]
checklists: [win-condition-checklist, metric-feasibility-checklist]
templates: [win-condition-canvas-template, milestone-tracker-template]
version: "1.0"
tags: [strategy, metas, milestones, metricas, planejamento]
---

# Definir Condições de Vitória 30/60/90

## Objetivo

Estabelecer condições de vitória claras e mensuráveis para o movimento nos horizontes de 30, 60 e 90 dias, definindo quais marcos concretos precisam ser alcançados em cada fase para que o movimento seja considerado saudável e em progresso.

## Contexto

Movimentos culturais não podem ser medidos apenas por métricas de vaidade (likes, followers). Precisam de condições de vitória que capturem profundidade de engajamento, qualidade da comunidade, ressonância narrativa e impacto no negócio. Sem win conditions claras, o squad não sabe se está ganhando ou perdendo.

## Inputs Necessários

- Thesis Document aprovado
- Identity System definido
- Baseline de métricas atuais (comunidade, engajamento, negócio)
- Benchmarks de movimentos similares
- Objetivos de negócio da empresa para o período
- Recursos disponíveis (budget, equipe, ferramentas)

## Processo

1. **Definir dimensões de vitória** — Estabelecer 4-5 dimensões: (a) Comunidade (tamanho e qualidade), (b) Narrativa (ressonância e share of conversation), (c) Engajamento (profundidade e frequência), (d) Negócio (leads, conversão, retention), (e) Cultura (mudança de percepção).

2. **Estabelecer baseline** — Para cada dimensão, documentar onde estamos hoje com dados reais. Se não há dados, definir como capturá-los antes de começar.

3. **Definir metas para 30 dias (Ignição)** — Focar em: primeiros sinais de vida do movimento, primeiros membros engajados, primeiros artefatos publicados, primeiras reações. Metas devem ser ambiciosas mas alcançáveis.

4. **Definir metas para 60 dias (Tração)** — Focar em: crescimento orgânico, primeiros champions emergindo, narrativa se espalhando além do público direto, primeiros sinais de impacto em negócio.

5. **Definir metas para 90 dias (Sustentação)** — Focar em: comunidade autossustentável, narrativa estabelecida no setor, impacto mensurável em métricas de negócio, base para escalar.

6. **Definir métricas por condição** — Para cada win condition, especificar: métrica exata, fonte de dados, frequência de medição, responsável pela coleta, threshold de sucesso/alerta/falha.

7. **Criar leading indicators** — Para cada win condition de resultado (lagging), definir 2-3 indicadores antecedentes que permitam corrigir curso antes que seja tarde.

8. **Definir kill criteria** — Estabelecer claramente: em quais condições o movimento deve ser pausado, pivotado ou encerrado. Não definir kill criteria é irresponsável.

9. **Alinhar com stakeholders** — Apresentar win conditions para stakeholders de negócio. Garantir que expectativas estão calibradas e que há acordo sobre o que "sucesso" significa.

10. **Criar dashboard de acompanhamento** — Montar dashboard visual com: win conditions por fase, métricas atuais vs. metas, leading indicators, status (verde/amarelo/vermelho).

## Outputs Esperados

- **Win Conditions Document** com metas 30/60/90
- **Métricas detalhadas** por dimensão e fase
- **Leading indicators** definidos
- **Kill criteria** documentados
- **Dashboard de acompanhamento** configurado
- **Alinhamento com stakeholders** registrado

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Dimensões cobertas | >= 4 dimensões |
| Baseline documentado | 100% das métricas com baseline |
| Metas por fase | 30, 60 e 90 dias definidos |
| Leading indicators | >= 2 por win condition |
| Kill criteria | Definidos e aprovados |
| Alinhamento stakeholders | Formalizado |

## Decision Points

- **Meta 30 dias não atingida** → Revisar tática, não a estratégia (ainda é cedo)
- **Meta 60 dias não atingida** → Avaliar se é problema de execução ou de thesis
- **Meta 90 dias não atingida** → Ativar kill criteria ou pivot
- **Metas superadas significativamente** → Recalibrar para cima e acelerar scaling

## Integração

- **Alimenta:** `plan-launch-sequence`, `run-experiments`, `measure-movement-health`, `measure-business-impact`
- **Recebe de:** `craft-movement-thesis`, `design-identity-system`
- **Workflow relacionado:** `07-30-60-90-launch-plan`, `04-measure-and-learn`
- **Cadência:** Definição inicial + revisão mensal + reset a cada 90 dias
- **Handoff:** Win Conditions vão para todo o squad e stakeholders
