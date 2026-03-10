---
id: plan-launch-sequence
name: "Planejar Sequência de Lançamento"
squad: movement
type: task
category: strategy
agents: [arquiteto-movimento, estrategista-movimento, ativador-chefe]
frameworks: [launch-sequence-framework, phased-activation-model]
checklists: [launch-readiness-checklist, go-no-go-checklist]
templates: [launch-plan-template, timeline-template]
version: "1.0"
tags: [strategy, lancamento, sequencia, fases, timing]
---

# Planejar Sequência de Lançamento

## Objetivo

Projetar a sequência completa de lançamento do movimento — desde o pré-aquecimento até a ignição pública — definindo ordem de ações, timing, canais, responsáveis e critérios de avanço entre fases para maximizar impacto e construir momentum.

## Contexto

Movimentos não nascem com um bang — nascem com um sussurro que se amplifica. A sequência de lançamento controla essa amplificação: quem sabe primeiro, quando cada camada é ativada, como a narrativa se constrói progressivamente. Um lançamento mal sequenciado desperdiça o momento mais precioso de um movimento — a primeira impressão.

## Inputs Necessários

- Thesis Document aprovado
- Identity System e artefatos prontos
- Win Conditions 30/60/90 definidas
- Channel Architecture planejada
- Lista de creators e parceiros confirmados
- Budget e recursos aprovados
- Calendário de datas relevantes do setor

## Processo

1. **Definir fases do lançamento** — Estruturar em 4 fases: (a) Infiltração (semanas -4 a -2): plantar sementes sem revelar o movimento, (b) Pré-aquecimento (semanas -2 a -1): teaser, inner circle, primeiros códigos, (c) Ignição (semana 0): lançamento público coordenado, (d) Sustentação (semanas 1-4): manter momentum e expandir.

2. **Mapear audiências por camada** — Definir: Inner Circle (primeiros 50-100 verdadeiros crentes), Early Adopters (500-1000 entusiastas), Early Majority (público amplo). Cada fase do lançamento atinge uma camada diferente.

3. **Sequenciar ações por fase** — Para cada fase, listar todas as ações necessárias com: descrição, canal, responsável, data, dependências, assets necessários.

4. **Definir triggers de avanço** — Estabelecer critérios objetivos para avançar de uma fase para a próxima. Ex: "Avançar para Ignição quando: 80% dos inner circle engajaram, manifesto testado com NPS > 70, 5+ creators confirmados".

5. **Planejar orquestração de canais** — Definir qual canal é ativado quando: owned media primeiro, earned media coordenado, paid media para amplificar. Evitar ativar tudo ao mesmo tempo.

6. **Criar calendar detalhado** — Montar cronograma dia a dia para as 2 semanas ao redor da ignição. Incluir: posts, emails, ativações de creators, PR, eventos, community drops.

7. **Preparar contingências** — Para cada fase, definir: "Se der errado, fazemos X". Incluir: cenário de baixo engajamento, cenário de backlash, cenário de concorrente reagir, cenário de viralizar acima do esperado.

8. **Alinhar cross-squad** — Sincronizar com outros squads (Copy, Brand, Traffic, Story) sobre: timing, narrativa, assets compartilhados, distribuição de responsabilidades.

9. **Definir go/no-go gate** — Estabelecer checkpoint formal 72h antes da Ignição: todos os assets prontos? Todos os canais configurados? Todos os parceiros confirmados? Contingências preparadas? Se qualquer item crítico falhar, postergar.

10. **Preparar war room** — Definir: equipe de plantão durante ignição, cadência de check-ins, ferramentas de monitoramento em tempo real, protocolos de decisão rápida, critérios de escalação.

## Outputs Esperados

- **Launch Plan Document** com fases detalhadas
- **Calendar detalhado** da sequência
- **Critérios de avanço** entre fases (triggers)
- **Plano de contingência** por cenário
- **Go/No-Go Checklist** para ignição
- **War Room Setup** para execução

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Fases definidas | Todas as 4 fases detalhadas |
| Ações sequenciadas | 100% com responsável e data |
| Triggers de avanço | Definidos para cada transição |
| Contingências | >= 3 cenários cobertos |
| Cross-squad alinhado | Confirmação de todos os squads |
| Go/no-go checklist | Completo com todos os itens críticos |

## Decision Points

- **Fase de Infiltração sem tração** → Extender infiltração por mais 1 semana e ajustar tática
- **Go/no-go falha** → Postergar ignição (nunca lançar sem estar pronto)
- **Ignição supera expectativas** → Ativar plano de aceleração e antecipar fase de sustentação
- **Backlash na ignição** → Ativar protocolo de crise e avaliar pausa

## Integração

- **Alimenta:** `launch-activation`, `activate-community`, `activate-creators`, `activate-pr`
- **Recebe de:** `craft-movement-thesis`, `define-win-conditions`, `design-channel-architecture`
- **Workflow relacionado:** `07-30-60-90-launch-plan`, `03-activation-sprint`
- **Cadência:** Uma vez por ciclo de lançamento + revisões semanais durante execução
- **Handoff:** Launch Plan vai para todos os agentes de ativação e squads parceiros
