---
id: detect-cultural-signals
name: "Detectar Sinais Culturais"
squad: movement
type: task
category: research
agents: [fenomenologo-cultural, analista-semiotico]
frameworks: [cultural-signal-mapping, tension-radar]
checklists: [signal-quality-checklist, source-diversity-checklist]
templates: [signal-card-template, signal-report-template]
version: "1.0"
tags: [research, sinais, cultura, tendencias, escuta]
---

# Detectar Sinais Culturais

## Objetivo

Capturar sinais culturais emergentes — tensões, desejos não articulados, mudanças de comportamento e linguagem — que revelem oportunidades para posicionar o movimento de forma relevante e autêntica no zeitgeist atual.

## Contexto

Sinais culturais são fragmentos de mudança que ainda não viraram tendência mainstream. Eles aparecem em comunidades de nicho, conversas orgânicas, memes, protestos estéticos e micro-comportamentos. A captura sistemática desses sinais é a matéria-prima de todo movimento cultural genuíno. Sem sinais reais, o movimento vira campanha publicitária disfarçada.

## Inputs Necessários

- Lista de comunidades-alvo e plataformas monitoradas
- Histórico de sinais capturados nos últimos 30 dias
- Briefing do movimento atual (thesis vigente)
- Mapa de tensões culturais do setor
- Acesso a ferramentas de social listening e scraping

## Processo

1. **Definir perímetro de escuta** — Listar no mínimo 15 fontes ativas: subreddits, grupos de Telegram/Discord, hashtags no TikTok, threads no X, fóruns de nicho, newsletters independentes e podcasts relevantes.

2. **Varrer fontes primárias** — Percorrer cada fonte buscando: (a) linguagem nova ou ressignificada, (b) frustrações recorrentes, (c) celebrações coletivas inesperadas, (d) memes que capturam sentimento, (e) rupturas com normas anteriores.

3. **Registrar sinais brutos** — Para cada sinal encontrado, preencher o Signal Card com: fonte, data, verbatim exato, contexto, sentimento predominante, frequência observada e screenshot/link.

4. **Classificar por tipologia** — Categorizar cada sinal como: Tensão Emergente, Desejo Latente, Mudança de Linguagem, Comportamento Novo, Estética Emergente ou Rejeição Ativa.

5. **Avaliar intensidade e velocidade** — Para cada sinal, pontuar de 1-5: (a) intensidade emocional, (b) velocidade de propagação, (c) diversidade de fontes, (d) potencial de conexão com a thesis do movimento.

6. **Triangular com dados quantitativos** — Cruzar sinais qualitativos com dados de busca (Google Trends, search volume), menções em social listening e dados de engajamento nas plataformas.

7. **Identificar clusters** — Agrupar sinais relacionados em clusters temáticos. Nomear cada cluster com uma frase que capture a essência do fenômeno.

8. **Priorizar sinais acionáveis** — Selecionar os 3-5 clusters com maior potencial de conexão com o movimento, considerando: relevância para o público-alvo, timing, autenticidade da conexão e viabilidade de ativação.

9. **Redigir Signal Report** — Compilar relatório com: resumo executivo, top sinais priorizados, evidências, recomendações de ação e próximos passos sugeridos para a thesis.

10. **Apresentar e debater** — Compartilhar o report com o squad para validação coletiva e decisão sobre quais sinais alimentam o próximo ciclo de estratégia.

## Outputs Esperados

- **Signal Cards** preenchidos (mínimo 20 por ciclo)
- **Signal Report** consolidado com clusters priorizados
- **Recomendações de ação** vinculadas a cada cluster
- **Atualização do radar de sinais** no registry do squad

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Fontes consultadas | >= 15 fontes distintas |
| Sinais capturados | >= 20 sinais brutos |
| Verbatims incluídos | 100% dos sinais com verbatim real |
| Diversidade de tipologia | >= 3 tipologias representadas |
| Triangulação quanti | >= 50% dos sinais triangulados |
| Clusters formados | >= 3 clusters acionáveis |

## Decision Points

- **Sinal forte + conexão clara com thesis** → Encaminhar imediatamente para `craft-movement-thesis` como input prioritário
- **Sinal forte + sem conexão com thesis atual** → Registrar como oportunidade futura e monitorar evolução
- **Sinal fraco + recorrente** → Manter monitoramento por mais 2 ciclos antes de descartar
- **Sinal contraditório com movimento** → Avaliar se exige ajuste de thesis ou se é ruído

## Integração

| Tipo | Referência |
|------|-----------|
| **Frameworks** | `frameworks/phenomenology-rapid-ethnography.md`, `frameworks/phenomenology-signal-clustering.md`, `frameworks/radar-layer.md` |
| **Checklists** | `checklists/cultural-insight-quality.md`, `checklists/fenomenologia/phenomenology-signal-capture.md`, `checklists/fenomenologia/signal-source-diversity.md`, `checklists/ciclo/trend-vs-fad-filter.md` |
| **Templates** | `templates/outputs/cultural-insight-report.md` |
| **Registries** | `data/registries/signal-archive.yaml`, `data/registries/decision-log.yaml`, `data/metrics/content-to-conversation.md` |
| **Workflows** | `workflows/00-signal-radar-daily.md` |

### Regras de Fluxo
- **Rework:** Se quality gate reprovar → retornar à Fase 1 (varredura) com fontes ampliadas e reexecutar captura
- **Escalation:** Se bloqueio ou decisão fora de escopo → escalar para Movement Chief
- **Handoff:** Output vai para → tasks de Strategy (craft-movement-thesis, design-identity-system)
