---
id: signal-radar-daily
name: "Signal Radar Diário"
squad: movement
type: workflow
agents: [fenomenologo]
cadence: daily
version: "1.0"
tags: [workflow, diario, sinais, radar, captura, cultura]
---

# Signal Radar Diário

## Objetivo

Operar o ciclo diário de captura de sinais culturais — da varredura matinal à triagem e registro — garantindo que o movimento esteja permanentemente conectado ao pulso cultural e que nenhum sinal urgente passe despercebido.

## Diagrama de Fases

```
[MANHÃ]          [MEIO-DIA]         [TARDE]           [FIM DO DIA]
Varredura    →   Triagem        →   Registro      →   Alerta
de Fontes        e Classificação     no Sistema        se Urgente
   |                 |                   |                  |
   v                 v                   v                  v
15 fontes       Urgente/             Signal Cards      Digest rápido
mínimo          Importante/          preenchidos       para squad
                Monitorar                               (se aplicável)
```

## Fases Detalhadas

### Fase 1: Varredura de Fontes (Manhã — 30-45min)

**Agentes:** fenomenologo

**Inputs:**
- Lista de fontes monitoradas (mínimo 15)
- Alertas de social listening acumulados overnight
- Trending topics das plataformas prioritárias
- Calendar de datas culturais relevantes

**Ações:**
1. Checar alertas de social listening configurados — revisar notificações e dashboards
2. Percorrer cada fonte da lista: subreddits, grupos de Telegram/Discord, hashtags TikTok, threads X, newsletters, fóruns
3. Para cada fonte, buscar: linguagem nova, frustrações recorrentes, celebrações coletivas, memes emergentes, rupturas de norma
4. Capturar screenshot/link de qualquer item relevante encontrado
5. Anotar impressões rápidas (30 segundos por sinal): o que é, por que chamou atenção, potencial

**Outputs:**
- Lista bruta de sinais capturados (mínimo 3-5/dia em dias normais)
- Screenshots e links salvos
- Notas rápidas de impressão

**Decision Gate:**
- Se sinal urgente detectado (viral, crise, oportunidade temporal) → pular para Fase 4 imediatamente
- Se dia sem sinais relevantes → registrar "dia limpo" e reduzir tempo de varredura

### Fase 2: Triagem e Classificação (Meio-dia — 15-20min)

**Agentes:** fenomenologo

**Inputs:**
- Sinais brutos capturados na manhã
- Thesis vigente para referência
- Tipologia de sinais (Tensão, Desejo, Linguagem, Comportamento, Estética, Rejeição)

**Ações:**
1. Revisar cada sinal bruto capturado
2. Classificar por urgência: Urgente (agir hoje), Importante (incorporar esta semana), Monitorar (acompanhar evolução)
3. Categorizar por tipologia do sinal
4. Pontuar relevância para o movimento (1-5 rápido)
5. Descartar ruído (sinal que parecia relevante mas não é)

**Outputs:**
- Sinais classificados por urgência e tipologia
- Sinais descartados com justificativa breve
- Sinais urgentes sinalizados

**Decision Gate:**
- Sinais urgentes → notificar Arquiteto de Movimento imediatamente
- Sinais importantes → encaminhar para Weekly Signal Digest
- Monitorar → adicionar ao tracking de evolução

### Fase 3: Registro no Sistema (Tarde — 15-20min)

**Agentes:** fenomenologo

**Inputs:**
- Sinais triados e classificados
- Template de Signal Card
- Banco de Signal Cards existente

**Ações:**
1. Para cada sinal mantido (não descartado), preencher Signal Card: fonte, data, verbatim exato, contexto, sentimento, frequência, tipologia, relevância, screenshot/link
2. Adicionar ao banco de Signal Cards com tags de busca
3. Verificar se sinal se conecta a algum cluster existente
4. Atualizar rastreamento de sinais em monitoramento (evoluíram? enfraqueceram?)

**Outputs:**
- Signal Cards preenchidos e registrados
- Banco de sinais atualizado
- Clusters existentes atualizados (se aplicável)

**Decision Gate:**
- Sinal que forma novo cluster → sinalizar para consolidação semanal
- Sinal que confirma tendência em ascensão → atualizar Trend Radar

### Fase 4: Alerta e Digest (Fim do dia — 5-10min)

**Agentes:** fenomenologo

**Inputs:**
- Sinais urgentes identificados
- Resumo do dia de captura

**Ações:**
1. Se há sinais urgentes: enviar mensagem no canal do squad com: sinal, por que é urgente, ação sugerida
2. Se dia teve muitos sinais relevantes: postar resumo rápido de 3 linhas no canal do squad
3. Se dia limpo: não enviar nada (evitar ruído)
4. Sinalizar itens que devem entrar no Weekly Signal Digest de segunda

**Outputs:**
- Alerta de sinais urgentes (se houver)
- Resumo rápido do dia (se relevante)
- Itens sinalizados para digest semanal

**Decision Gate:**
- Sinal urgente com potencial de crise → acionar workflow `06-crisis-and-backlash`
- Sinal urgente com oportunidade → acionar produção de conteúdo reativo

## Cadência

| Momento | Ação | Duração | Responsável |
|---------|------|---------|------------|
| 8h-9h | Varredura de fontes | 30-45min | Fenomenólogo Cultural |
| 12h-12h30 | Triagem e classificação | 15-20min | Fenomenólogo Cultural |
| 15h-15h30 | Registro no sistema | 15-20min | Fenomenólogo + Analista |
| 17h-17h10 | Alerta e digest | 5-10min | Fenomenólogo Cultural |

**Total diário:** ~70-95 minutos
**Dias de operação:** Segunda a sexta (fim de semana: alertas automáticos only)

## Artefatos Produzidos

- Signal Cards diários (3-5 por dia em média)
- Alertas urgentes (quando aplicável)
- Resumos rápidos do dia (quando relevante)
- Inputs para Weekly Signal Digest
- Atualizações de clusters e Trend Radar

## Métricas de Sucesso

| Métrica | Meta |
|---------|------|
| Sinais capturados/semana | >= 15 |
| Tempo de alerta (sinal urgente → squad notificado) | < 2 horas |
| Signal Cards preenchidos vs. sinais capturados | >= 80% |
| Cobertura de fontes/semana | 100% da lista |
| Contribuição para Weekly Digest | Todos os dias de captura |
| Sinais que se tornaram ações | >= 20% dos urgentes |

## Integração

| Tipo | Referência |
|------|-----------|
| **Tasks** | `tasks/research/detect-cultural-signals.md`, `tasks/research/track-cultural-trends.md`, `tasks/research/map-cultural-tensions.md`, `tasks/research/map-counter-narratives.md`, `tasks/research/research-platform-dynamics.md`, `tasks/operations/weekly-signal-radar.md` |
| **Frameworks** | `frameworks/phenomenology-rapid-ethnography.md`, `frameworks/phenomenology-signal-clustering.md`, `frameworks/radar-layer.md`, `frameworks/phenomenology-language-mapping.md` |
| **Checklists** | `checklists/cultural-insight-quality.md`, `checklists/fenomenologia/phenomenology-signal-capture.md`, `checklists/fenomenologia/signal-source-diversity.md`, `checklists/ciclo/trend-vs-fad-filter.md` |
| **Registries** | `data/registries/signal-archive.yaml`, `data/registries/decision-log.yaml` |

### Regras de Fluxo
- **Quality Gate entre fases:** Cada fase tem Decision Gate próprio que bloqueia avanço se critérios não atingidos
- **Rework:** Se sinal urgente perdido → revisar cobertura de fontes e ajustar lista de monitoramento
- **Escalation:** Sinal urgente com potencial de crise → acionar `workflows/06-crisis-and-backlash.md`
- **Handoff:** Signal Reports consolidados alimentam → `workflows/01-thesis-forge.md` e `workflows/05-ralphloop-kaizen-weekly.md`
