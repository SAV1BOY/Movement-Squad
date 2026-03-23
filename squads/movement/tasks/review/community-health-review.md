---
id: community-health-review
name: "Review de Saúde da Comunidade"
squad: movement
type: task
category: review
agents: [movement-architect, analista-de-impacto]
frameworks: [community-flywheel, impact-cohort-analysis]
checklists: [comunidade/community-health-indicators, comunidade/community-to-movement-bridge]
templates: [reports/community-health-report]
registry: [data/metrics/community-growth-quality]
version: "1.0"
tags: [review, comunidade, saude, diagnostico, intervencao]
---

# Review de Saúde da Comunidade

## Objetivo

Conduzir sessão de review dedicada à saúde da comunidade — analisando métricas, sentimento, estrutura e dinâmicas — para diagnosticar problemas emergentes, celebrar sucessos e tomar decisões sobre intervenções necessárias antes que problemas se agravem.

## Contexto

Comunidades são organismos vivos que podem adoecer silenciosamente. O review de saúde é o check-up periódico que detecta sinais antes que se tornem crises: queda de engajamento, toxicidade crescente, burnout de champions, perda de novos membros. Detectar cedo é a diferença entre ajuste e ressuscitação.

## Inputs Necessários

- Community Health Report mais recente
- Cohort Retention Analysis atualizada
- Dados de participação em rituais
- Feedback qualitativo de membros e champions
- Logs de moderação (conflitos, bans, advertências)
- Pulse survey mais recente

## Processo

1. **Revisar métricas-chave** — Apresentar: DAU/MAU ratio (tendência), taxa de contribuição (tendência), retenção por coorte (evolução), net member growth, sentimento médio. Comparar com mês anterior e com metas.

2. **Avaliar camadas de participação** — Analisar distribuição: % observadores vs. participantes vs. contribuidores vs. champions. A pirâmide está saudável? Há mobilidade entre camadas?

3. **Analisar saúde dos champions** — Revisar: quantos champions ativos, nível de atividade individual, sinais de burnout, satisfação (última pesquisa), pipeline de novos champions. Champions são o "coração" — se estão mal, a comunidade vai sentir.

4. **Revisar onboarding** — Analisar: taxa de conclusão do onboarding, tempo até primeira interação, retention D7 de novos membros, feedback de recém-chegados.

5. **Avaliar qualidade das conversas** — Amostragem de conversas recentes: profundidade dos diálogos, presença de humor saudável, ausência de toxicidade, temas que mais engajam, temas que geram silêncio.

6. **Revisar incidentes** — Analisar logs de moderação: houve conflitos? Como foram resolvidos? Há padrões problemáticos? Algum membro tóxico recorrente? Algum tema que sempre gera conflito?

7. **Ouvir feedback direto** — Trazer para a sessão: 3-5 quotes de feedback recente de membros (positivo e negativo), resultado do último pulse survey, sugestões dos champions.

8. **Diagnosticar problemas** — Para cada métrica em amarelo/vermelho ou feedback negativo recorrente, formular diagnóstico: qual é o problema? Qual é a causa provável? Qual seria a intervenção?

9. **Priorizar intervenções** — Selecionar 2-3 intervenções prioritárias para o próximo mês: ações específicas, responsáveis, métricas de sucesso, prazo.

10. **Documentar e comunicar** — Registrar decisões e ações. Compartilhar com a comunidade (quando apropriado) o que estamos fazendo para melhorar a experiência.

## Outputs Esperados

- **Community Health Review Report**
- **Diagnóstico de problemas** com causa provável
- **Plano de intervenção** com 2-3 ações priorizadas
- **Atualização do status** de champions
- **Decisões documentadas** no log

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Métricas revisadas | Todas as core (>= 6) |
| Feedback qualitativo | >= 5 quotes analisados |
| Saúde de champions | Avaliada individualmente |
| Diagnósticos formulados | Para todo item amarelo/vermelho |
| Intervenções priorizadas | 2-3 com responsável e prazo |
| Documentação | Completa em até 24h |

## Decision Points

- **Comunidade saudável** → Manter práticas e considerar expansão
- **Sinais de fadiga** → Reduzir frequência de rituais e diversificar formatos
- **Toxicidade emergente** → Intervenção imediata + reforço de código de conduta
- **Champions em burnout** → Ativar programa de suporte e recrutar novos

## Integração

| Tipo | Referência |
|------|-----------|
| **Frameworks** | `frameworks/community-flywheel.md`, `frameworks/impact-cohort-analysis.md` |
| **Checklists** | `checklists/comunidade/community-health-indicators.md`, `checklists/comunidade/community-to-movement-bridge.md` |
| **Templates** | `templates/reports/community-health-report.md` |
| **Registries** | `data/metrics/community-growth-quality.md` |
| **Workflows** | `workflows/05-ralphloop-kaizen-weekly.md` |

### Regras de Fluxo
- **Rework:** Se quality gate reprovar → documentar gaps encontrados, definir ações corretivas e reagendar review em 1 semana
- **Escalation:** Se bloqueio ou decisão fora de escopo → escalar para Movement Chief
- **Handoff:** Output vai para → tasks de Strategy e Operations do próximo ciclo
