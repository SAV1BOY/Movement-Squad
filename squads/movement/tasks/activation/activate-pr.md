---
id: activate-pr
name: "Ativar PR e Earned Media"
squad: movement
type: task
category: activation
agents: [movement-chief, estrategista-de-ciclo]
frameworks: [narrative-graph-framework]
checklists: [pr/narrative-pitch-quality, pr/spokesperson-readiness, pr/backlash-mitigation]
templates: [outputs/pr-pitch]
registry: [data/metrics/earned-media-metrics]
version: "1.0"
tags: [activation, pr, earned-media, imprensa, midia, cobertura]
---

# Ativar PR e Earned Media

## Objetivo

Executar a estratégia de PR do movimento — distribuindo ângulos jornalísticos, gerenciando relações com mídia e conquistando cobertura espontânea em veículos relevantes que amplifica a narrativa do movimento como fenômeno cultural legítimo.

## Contexto

PR de movimento é diferente de PR de produto. Não estamos pedindo para a mídia falar do nosso produto — estamos oferecendo uma história cultural que vale ser contada. O jornalista não está nos fazendo um favor; estamos oferecendo pauta relevante para a audiência dele. Essa mudança de mentalidade é fundamental.

## Inputs Necessários

- Ângulos de PR desenvolvidos e priorizados
- Press Kit completo
- Porta-vozes preparados
- Mapa de veículos e jornalistas target
- Timeline de PR alinhada com lançamento
- Counter-Narrative Playbook para reativas

## Processo

1. **Priorizar veículos e jornalistas** — Criar lista ranked: tier 1 (veículos de maior impacto + jornalistas que cobrem o tema), tier 2 (veículos relevantes + newsletters de nicho), tier 3 (podcasts, canais de YouTube, veículos de segmento).

2. **Personalizar pitches** — Para cada jornalista/veículo tier 1, customizar: subject line irresistível, parágrafo que conecta com o que ele já escreveu, o ângulo específico que serve pra ele, oferta concreta (dados exclusivos, entrevista, acesso).

3. **Executar outreach em ondas** — Primeira onda: tier 1 com exclusivas. Após resposta/publicação, segunda onda: tier 2 com ângulo complementar. Terceira onda: tier 3 com liberdade de abordagem.

4. **Gerenciar exclusividades** — Se veículo tier 1 aceita exclusiva: definir janela (24-48h de embargo), preparar porta-voz, garantir material exclusivo, coordenar timing com lançamento.

5. **Facilitar entrevistas** — Preparar porta-vozes: key messages frescas, soundbites prontas, briefing sobre o jornalista e o veículo, simulação de perguntas difíceis (especialmente sobre marca vs. movimento).

6. **Monitorar cobertura** — Rastrear em tempo real: publicações sobre o movimento, menções em redes por jornalistas, citações em matérias sobre tendências, share of voice vs. concorrentes.

7. **Amplificar cobertura earned** — Quando matéria sai: compartilhar nos canais do movimento, enviar para comunidade, usar como prova social, considerar amplificação paga de matéria de veículo relevante.

8. **Nutrir relações contínuas** — Pós-publicação: agradecer jornalista, enviar dados de impacto da matéria dele, oferecer updates futuros, convidar para eventos/rituais do movimento.

9. **Gerenciar reativas** — Se jornalista faz pergunta inesperada ou matéria toma ângulo não desejado: responder com calma usando Counter-Narrative Playbook, nunca confrontar publicamente, oferecer contexto adicional.

10. **Compilar PR report** — Mensal: cobertura conquistada (lista de matérias), reach estimado, sentimento da cobertura, AVE (se stakeholders exigem), impacto em métricas de movimento, learnings.

## Outputs Esperados

- **Outreach executado** em ondas
- **Cobertura earned** conquistada
- **Entrevistas facilitadas** com porta-vozes
- **Monitoramento de mídia** ativo
- **PR Report** mensal
- **Relações com mídia** documentadas

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Pitches enviados | >= 20 por ciclo |
| Taxa de resposta | >= 30% |
| Cobertura earned | >= 3 matérias por ciclo |
| Sentimento da cobertura | >= 80% positivo/neutro |
| Porta-vozes preparados | 100% treinados antes |
| PR report | Entregue mensalmente |

## Decision Points

- **Veículo tier 1 quer matéria de fundo** → Priorizar e oferecer acesso total
- **Cobertura negativa** → Avaliar se responde publicamente ou deixa passar, conforme protocolo
- **Jornalista vira aliado do movimento** → Nutrir relação como parceiro de longo prazo
- **PR não gerando tração** → Revisitar ângulos e testar novos hooks

## Integração

| Tipo | Referência |
|------|-----------|
| **Frameworks** | `frameworks/narrative-graph-framework.md` |
| **Checklists** | `checklists/pr/narrative-pitch-quality.md`, `checklists/pr/spokesperson-readiness.md`, `checklists/pr/backlash-mitigation.md` |
| **Templates** | `templates/outputs/pr-pitch.md` |
| **Registries** | `data/metrics/earned-media-metrics.md` |
| **Workflows** | `workflows/03-activation-sprint.md` |

### Regras de Fluxo
- **Rework:** Se quality gate reprovar → pausar canal/fase afetada, diagnosticar causa raiz e reexecutar com ajustes
- **Escalation:** Se bloqueio ou decisão fora de escopo → escalar para Movement Chief
- **Handoff:** Output vai para → tasks de Measurement (measure-movement-health, run-experiments)
