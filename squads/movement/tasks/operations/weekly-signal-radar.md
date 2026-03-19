---
id: weekly-signal-radar
name: "Radar Semanal de Sinais"
squad: movement
type: task
category: operations
agents: [fenomenologo]
frameworks: [phenomenology-signal-clustering, radar-layer]
checklists: [fenomenologia/phenomenology-signal-capture]
templates: [operational/signal-capture-entry]
registry: [data/registries/signal-archive]
version: "1.0"
tags: [operations, semanal, sinais, radar, monitoramento, rotina]
---

# Radar Semanal de Sinais

## Objetivo

Executar a rotina semanal de captura e triagem de sinais culturais — consolidando as detecções diárias em um digest semanal acionável que alimenta o squad com insights frescos e mantém o movimento conectado ao pulso cultural em tempo real.

## Contexto

O radar semanal é a versão operacional da detecção de sinais. Enquanto a task de research faz mapeamentos profundos mensais, o radar semanal garante que nenhum sinal urgente passe despercebido e que o squad tenha material fresco toda semana para reagir, criar e adaptar.

## Inputs Necessários

- Signal Cards capturados durante a semana
- Alertas de social listening
- Trends das plataformas monitoradas
- Feedback da comunidade da semana
- Ações de concorrentes da semana
- Calendar de datas relevantes da próxima semana

## Processo

1. **Consolidar sinais da semana** — Reunir todos os Signal Cards capturados ao longo da semana. Se houve dias sem captura, fazer varredura rápida retroativa.

2. **Triar por urgência** — Classificar cada sinal: (a) Urgente (requer ação esta semana), (b) Importante (incorporar no próximo ciclo), (c) Monitorar (guardar e acompanhar evolução).

3. **Identificar top 3 sinais da semana** — Selecionar os 3 sinais mais relevantes: com maior potencial de impacto no movimento, maior urgência ou maior novidade.

4. **Cruzar com calendar** — Verificar: há datas, eventos ou acontecimentos na próxima semana que conectam com sinais capturados? Identificar oportunidades de timing.

5. **Escrever Weekly Signal Digest** — Produzir documento conciso (1-2 páginas) com: top 3 sinais, o que significam para o movimento, oportunidades de ação imediata, sinais para monitorar.

6. **Recomendar ações rápidas** — Para sinais urgentes: sugerir 1-2 ações que o squad pode executar na próxima semana. Podem ser: conteúdo reativo, ajuste de ritual, briefing para creator, post na comunidade.

7. **Atualizar Trend Radar** — Se algum sinal indica mudança em tendência monitorada: atualizar posição no radar (subiu de camada, acelerou, desacelerou, declinou).

8. **Distribuir digest** — Enviar Weekly Signal Digest para todo o squad até segunda-feira de manhã. Garantir que esteja acessível e legível em 5 minutos.

9. **Discutir no ritual semanal** — Apresentar top sinais na reunião de abertura da semana. Coletar reações e perspectivas adicionais do squad.

10. **Arquivar para análise mensal** — Guardar todos os digests semanais para alimentar o Signal Report mensal e análise de tendências de longo prazo.

## Outputs Esperados

- **Weekly Signal Digest** publicado (toda segunda)
- **Sinais triados** por urgência
- **Recomendações de ação** para a semana
- **Trend Radar** atualizado (se necessário)
- **Arquivo** para análise mensal

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Digest publicado | Toda segunda até 10h |
| Sinais capturados na semana | >= 5 |
| Top 3 selecionados | Com justificativa |
| Ações recomendadas | >= 1 para sinais urgentes |
| Distribuição | 100% do squad recebeu |

## Decision Points

- **Sinal urgente com alto impacto** → Acionar squad imediatamente (não esperar segunda)
- **Semana sem sinais relevantes** → Expandir fontes de monitoramento
- **Sinal que contradiz thesis** → Escalar para Arquiteto de Movimento
- **Muitos sinais urgentes** → Priorizar top 1 e agendar os demais

## Integração

| Tipo | Referência |
|------|-----------|
| **Frameworks** | `frameworks/phenomenology-signal-clustering.md`, `frameworks/radar-layer.md` |
| **Checklists** | `checklists/fenomenologia/phenomenology-signal-capture.md` |
| **Templates** | `templates/operational/signal-capture-entry.md` |
| **Registries** | `data/registries/signal-archive.yaml` |
| **Workflows** | `workflows/05-ralphloop-kaizen-weekly.md` |

### Regras de Fluxo
- **Rework:** Se quality gate reprovar → identificar bloqueio, resolver dependência e reexecutar no próximo ciclo
- **Escalation:** Se bloqueio ou decisão fora de escopo → escalar para Movement Chief
- **Handoff:** Output vai para → todas as tasks que dependem dos registros atualizados
