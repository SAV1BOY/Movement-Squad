---
id: define-win-conditions
name: "Definir Condições de Vitória 30/60/90"
squad: movement
type: task
category: strategy
agents: [movement-chief, analista-de-impacto]
frameworks: [chief-win-conditions-30-60-90, chief-movement-business-canvas, impact-metrics-model]
checklists: [chief/chief-win-condition, chief/chief-alignment-with-business, impact-dashboard-quality]
templates: [plans/30-60-90-launch-plan, reports/movement-health-dashboard]
registry: [data/registries/decision-log]
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

| Tipo | Referência |
|------|-----------|
| **Frameworks** | `frameworks/chief-win-conditions-30-60-90.md`, `frameworks/chief-movement-business-canvas.md`, `frameworks/impact-metrics-model.md` |
| **Checklists** | `checklists/chief/chief-win-condition.md`, `checklists/chief/chief-alignment-with-business.md`, `checklists/impact-dashboard-quality.md` |
| **Templates** | `templates/plans/30-60-90-launch-plan.md`, `templates/reports/movement-health-dashboard.md` |
| **Registries** | `data/registries/decision-log.yaml` |
| **Workflows** | `workflows/01-thesis-forge.md` |

### Regras de Fluxo
- **Rework:** Se quality gate reprovar → retornar ao passo que falhou, incorporar feedback e resubmeter para aprovação do Movement Chief
- **Escalation:** Se bloqueio ou decisão fora de escopo → escalar para Movement Architect
- **Handoff:** Output vai para → tasks de Creation (write-manifesto, create-memetic-assets)
