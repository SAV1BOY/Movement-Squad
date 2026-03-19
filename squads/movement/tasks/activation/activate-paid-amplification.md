---
id: activate-paid-amplification
name: "Ativar Amplificação Paga"
squad: movement
type: task
category: activation
agents: [movement-chief, analista-de-impacto]
frameworks: [distribution-trident, cycle-momentum-mapping]
checklists: [distribuicao/paid-amplification-guardrails, distribuicao/attribution-sanity-check]
templates: [outputs/distribution-plan]
registry: [data/registries/distribution-plans]
version: "1.0"
tags: [activation, paid, midia, amplificacao, ads, distribuicao]
---

# Ativar Amplificação Paga

## Objetivo

Executar a estratégia de amplificação paga do movimento — usando mídia paga não para vender diretamente, mas para amplificar os melhores conteúdos de movimento até audiências que ainda não conhecem a causa, acelerando o crescimento orgânico.

## Contexto

Mídia paga em movimento não é campanha de performance. É acelerador de orgânico. O objetivo é pegar o conteúdo que já provou ressonância orgânica e colocá-lo na frente de mais pessoas certas. Nunca pagar para distribuir conteúdo que não engaja organicamente — se não funciona free, ads não vão salvar.

## Inputs Necessários

- Conteúdo de movimento com dados de performance orgânica
- Platform Briefs com specs de ads por plataforma
- Budget aprovado e alocado por plataforma
- Públicos-alvo definidos e segmentados
- Win Conditions com métricas de alcance e conversão
- Channel Architecture com função de cada canal

## Processo

1. **Selecionar conteúdo para amplificação** — Identificar top 10-20% do conteúdo orgânico com melhor performance. Critérios: engajamento rate acima da média, sentimento positivo, compartilhamentos altos, comments qualitativos.

2. **Definir objetivos por peça** — Para cada conteúdo selecionado, definir: awareness (alcance + impressões), engajamento (interações + compartilhamentos), community (entradas na comunidade), conversão (landing page + trial).

3. **Segmentar públicos** — Criar segmentações: (a) Lookalike da comunidade atual, (b) Interessados em temas do movimento, (c) Audiência de creators parceiros, (d) Retargeting de visitantes, (e) Públicos de concorrentes culturais.

4. **Criar variações de ads** — Para cada conteúdo, adaptar 2-3 variações: diferentes hooks de abertura, diferentes CTAs, diferentes thumbnails. Manter essência intacta.

5. **Configurar tracking completo** — Garantir: UTMs em todos os links, pixels configurados, eventos de conversão definidos (entry na comunidade, não só clique), atribuição multi-touch se possível.

6. **Alocar budget por teste** — Iniciar com budget de teste (20% do total) distribuído entre variações e públicos. Não concentrar budget antes de ter dados.

7. **Lançar e monitorar** — Ativar campanhas e monitorar nas primeiras 24-48h: CPM, CTR, custo por engajamento, custo por entrada na comunidade, sentimento nos comentários dos ads.

8. **Otimizar com dados** — Após fase de teste: matar variações com baixo desempenho, escalar vencedoras, ajustar públicos, redistribuir budget. Otimizar para métricas de profundidade (community entry), não superficiais (cliques).

9. **Sincronizar com orgânico** — Garantir que a experiência paga → orgânica seja fluida: landing page alinhada com conteúdo do ad, comunidade pronta para receber novos membros, onboarding ativo.

10. **Reportar e decidir** — Semanalmente: relatório de performance por plataforma, por conteúdo, por público. Mensalmente: relatório de ROI incluindo impacto em métricas de movimento (não só cliques).

## Outputs Esperados

- **Conteúdo amplificado** com variações por plataforma
- **Segmentações ativas** com performance monitorada
- **Tracking completo** configurado e funcionando
- **Relatório semanal** de performance
- **Relatório mensal** de ROI do movimento
- **Recomendações de otimização** contínuas

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Conteúdo selecionado | Apenas top performers orgânicos |
| Variações testadas | >= 2 por conteúdo |
| Tracking | 100% dos links com UTM + pixel |
| Custo por community entry | Definido e monitorado |
| Report semanal | 100% entregues |
| ROI positivo em métricas de movimento | Após 30 dias de otimização |

## Decision Points

- **CPA community entry aceitável** → Escalar budget gradualmente
- **Alto alcance mas baixo engajamento** → Conteúdo ou público errado, ajustar
- **Comentários negativos nos ads** → Avaliar se é audiência errada ou messaging problemático
- **Budget esgotando rápido** → Reallocar para plataformas e públicos mais eficientes

## Integração

| Tipo | Referência |
|------|-----------|
| **Frameworks** | `frameworks/distribution-trident.md`, `frameworks/cycle-momentum-mapping.md` |
| **Checklists** | `checklists/distribuicao/paid-amplification-guardrails.md`, `checklists/distribuicao/attribution-sanity-check.md` |
| **Templates** | `templates/outputs/distribution-plan.md` |
| **Registries** | `data/registries/distribution-plans/` |
| **Workflows** | `workflows/03-activation-sprint.md` |

### Regras de Fluxo
- **Rework:** Se quality gate reprovar → pausar canal/fase afetada, diagnosticar causa raiz e reexecutar com ajustes
- **Escalation:** Se bloqueio ou decisão fora de escopo → escalar para Movement Chief
- **Handoff:** Output vai para → tasks de Measurement (measure-movement-health, run-experiments)
