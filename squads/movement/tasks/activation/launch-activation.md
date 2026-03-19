---
id: launch-activation
name: "Ativar Lançamento por Fase e Canal"
squad: movement
type: task
category: activation
agents: [ativador-chefe, estrategista-movimento, community-builder]
frameworks: [phased-activation-framework, channel-orchestration-model]
checklists: [activation-readiness-checklist, channel-launch-checklist]
templates: [activation-plan-template, war-room-template]
version: "1.0"
tags: [activation, lancamento, fases, canais, execucao, orquestracao]
---

# Ativar Lançamento por Fase e Canal

## Objetivo

Executar o lançamento do movimento seguindo a sequência planejada — coordenando ativações em múltiplos canais, múltiplos agentes e múltiplas fases — garantindo que cada ação aconteça no momento certo, no canal certo, com o impacto desejado.

## Contexto

O plano existe no papel. A ativação existe no mundo. Esta task é sobre transformar estratégia em execução impecável — onde cada post, cada mensagem para creator, cada PR pitch, cada ação comunitária acontece em sincronia para criar a impressão de que o movimento explodiu organicamente (quando na verdade foi meticulosamente orquestrado).

## Inputs Necessários

- Launch Plan Document com sequência completa
- Todos os assets produzidos e aprovados
- Creators e parceiros confirmados e briefados
- Canais configurados e testados
- War room setup definido
- Win Conditions com métricas de acompanhamento
- Go/no-go checklist aprovado

## Processo

1. **Executar go/no-go final** — 72h antes da ignição, percorrer checklist completo: assets prontos, canais configurados, creators confirmados, PR pautado, equipe escalada, contingências preparadas, métricas configuradas.

2. **Ativar fase de Infiltração** — Executar ações sutis: plantar sementes em comunidades relevantes, iniciar conversas sem mencionar o movimento, creators de nicho fazendo conteúdo "espontâneo", teasers crípticos nos canais próprios.

3. **Ativar fase de Pré-aquecimento** — Escalar gradualmente: revelar primeiros artefatos para inner circle, abrir waitlist/convite fechado, creators compartilham primeiras pistas, PR dá exclusiva para veículo-chave.

4. **Monitorar sinais de tração** — Verificar triggers de avanço: inner circle engajou? Waitlist está crescendo? Conversas orgânicas estão surgindo? Creators estão animados? Se triggers não atingidos, avaliar extensão da fase.

5. **Ativar Ignição** — Lançamento coordenado: manifesto publicado em todos os canais, creators publicam simultaneamente, PR distribuído, comunidade aberta, ads ativados para amplificação. Tudo em janela de 24-48h.

6. **Operar war room** — Durante primeiras 72h pós-ignição: monitorar métricas em tempo real, responder a conversas, amplificar conteúdo orgânico, ajustar ads, resolver problemas, capturar momentum.

7. **Ativar fase de Sustentação** — Pós-ignição: manter cadência de conteúdo alta, ativar segunda leva de creators, publicar stories de membros, aprofundar comunidade, iniciar rituais.

8. **Documentar learnings em tempo real** — Durante toda a ativação, registrar: o que funcionou acima do esperado, o que não funcionou, reações inesperadas, oportunidades emergentes, problemas encontrados.

9. **Executar contingências se necessário** — Se cenários negativos se materializam: ativar protocolo de crise, ajustar messaging, pausar elementos problemáticos, comunicar squad imediatamente.

10. **Compilar activation report** — Após 2 semanas, produzir relatório completo: resultados por fase e canal, comparação com win conditions, learnings, recomendações para próximo ciclo.

## Outputs Esperados

- **Ativação executada** em todas as fases
- **War room logs** das primeiras 72h
- **Métricas em tempo real** capturadas
- **Learnings documentados** durante execução
- **Activation Report** completo em até 14 dias
- **Recomendações para próximo ciclo**

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Go/no-go | Aprovado antes de iniciar |
| Fases executadas | Todas as 4 fases |
| War room operante | 72h de cobertura contínua |
| Métricas capturadas | 100% das métricas definidas |
| Activation report | Entregue em até 14 dias |
| Contingências testadas | Protocolos ativados se necessário |

## Decision Points

- **Infiltração sem eco** → Extender por mais 1 semana ou mudar tática
- **Pré-aquecimento com tração explosiva** → Antecipar ignição para surfar momentum
- **Ignição com backlash** → Ativar protocolo de crise imediatamente
- **Sustentação perdendo energia** → Injetar novos assets e ativar segunda leva de creators

## Integração

| Tipo | Referência |
|------|-----------|
| **Frameworks** | `frameworks/distribution-trident.md`, `frameworks/community-flywheel.md`, `frameworks/cycle-launch-sequencing.md`, `frameworks/ralphloop-kaizen.md` |
| **Checklists** | `checklists/distribution-plan-quality.md`, `checklists/launch-sequencing-quality.md`, `checklists/community-activation-quality.md`, `checklists/impact-dashboard-quality.md` |
| **Templates** | `templates/outputs/distribution-plan.md`, `templates/outputs/community-playbook.md`, `templates/reports/weekly-readout.md` |
| **Registries** | `data/registries/distribution-plans/`, `data/registries/experiment-log.yaml`, `data/metrics/movement-health-score.md`, `data/metrics/business-impact.md` |
| **Workflows** | `workflows/03-activation-sprint.md` |

### Regras de Fluxo
- **Rework:** Se quality gate reprovar → pausar canal/fase afetada, diagnosticar causa raiz e reexecutar com ajustes
- **Escalation:** Se bloqueio ou decisão fora de escopo → escalar para Movement Architect
- **Handoff:** Output vai para → tasks de Measurement (measure-movement-health, run-experiments)
