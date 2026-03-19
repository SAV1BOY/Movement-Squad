---
id: analyze-content-to-conversation
name: "Analisar Conteúdo para Conversação"
squad: movement
type: task
category: measurement
agents: [analista-de-impacto, fenomenologo]
frameworks: [impact-metrics-model, community-flywheel]
checklists: [impacto/vanity-metric-filter]
templates: [reports/weekly-readout]
registry: [data/metrics/content-to-conversation]
version: "1.0"
tags: [measurement, conteudo, conversacao, propagacao, narrativa, analise]
---

# Analisar Conteúdo para Conversação

## Objetivo

Analisar como o conteúdo do movimento se transforma em conversação orgânica — rastreando o caminho de publicação até virar tema de discussão genuína entre pessoas — entendendo quais tipos de conteúdo geram diálogo real e quais morrem no consumo passivo.

## Contexto

O indicador mais poderoso de um movimento não é quantas pessoas viram o conteúdo, mas quantas começaram a falar sobre o tema com outras pessoas. Quando o conteúdo do movimento gera conversas que existiriam mesmo sem o post original, o movimento está funcionando. Quando gera apenas likes, é só conteúdo.

## Inputs Necessários

- Dados de performance de conteúdo publicado
- Dados de social listening (menções, conversas derivadas)
- Dados de comunidade (threads geradas por conteúdo)
- Dados de shared/saves/forwards vs. likes
- UGC catalogado e rastreado
- Dados de search volume por termos do movimento

## Processo

1. **Mapear funil de propagação** — Definir estágios: (a) Impressão (viu), (b) Engajamento raso (like, react), (c) Engajamento médio (comment, share), (d) Conversação derivada (pessoa fala sobre o tema em outro contexto), (e) UGC (pessoa cria conteúdo próprio sobre o tema), (f) Meme/referência cultural (o tema entra no vocabulário coletivo).

2. **Classificar conteúdo por performance no funil** — Para cada peça de conteúdo publicada, medir: em qual estágio parou? Quanto avançou no funil? O ratio de conversação/impressão é o indicador-chave.

3. **Identificar conteúdo que gera conversação** — Selecionar top 10% de conteúdo que mais avançou no funil. Analisar: o que têm em comum? Formato? Tema? Tom? Timing? Plataforma?

4. **Analisar a conversação derivada** — Para conteúdos que geraram discussão: como as pessoas reinterpretam? Que palavras usam? Concordam ou discordam? Adicionam suas próprias histórias? Mudam o framing?

5. **Mapear caminhos de propagação** — Rastrear: onde a conversa começou → para onde migrou → quem amplificou → em quais plataformas se espalhou. Identificar "nós de amplificação" (pessoas/espaços que mais propagam).

6. **Medir share/save ratio** — Share e save são indicadores mais fortes que like: share = "quero que outros vejam" e save = "quero rever". Calcular ratio share/impressão e save/impressão como proxy de valor real.

7. **Rastrear UGC derivado** — Catalogar todo conteúdo criado por membros e não-membros inspirado pelo movimento: remixes, paródias, reações, complementos, contestações. UGC é o indicador máximo de propagação.

8. **Correlacionar com métricas de busca** — Verificar: após publicação de conteúdo forte, houve aumento em buscas por termos do movimento? Isso indica que o conteúdo fez pessoas irem ativamente procurar mais.

9. **Extrair padrões e playbook** — Compilar: quais fórmulas de conteúdo geram mais conversação? Criar playbook de "conteúdo que gera conversa" com: formatos, temas, tons, timings, plataformas.

10. **Produzir Content-to-Conversation Report** — Mensal: funil de propagação por tipo de conteúdo, top conteúdos conversacionais, padrões identificados, UGC catalogado, recomendações para próximo ciclo.

## Outputs Esperados

- **Funil de propagação** mapeado e mensurado
- **Ranking de conteúdo** por poder conversacional
- **Análise de UGC** catalogado
- **Playbook de conteúdo conversacional**
- **Content-to-Conversation Report** mensal
- **Nós de amplificação** identificados

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Conteúdo analisado | 100% do conteúdo publicado |
| Funil mapeado | Todos os estágios com dados |
| Share/save ratio | Calculado para todo conteúdo |
| UGC rastreado | 100% catalogado |
| Padrões identificados | >= 3 padrões documentados |
| Report mensal | Entregue |

## Decision Points

- **Conteúdo com alta impressão mas baixa conversação** → Revisar tom — pode estar polished demais
- **Conteúdo com baixa impressão mas alta conversação** → Amplificar com paid e redistribuir
- **UGC explodindo** → Amplificar, reconhecer criadores, criar mais templates remixáveis
- **Nenhum conteúdo gera conversação** → Problema grave — revisar pilares de conteúdo e thesis

## Integração

| Tipo | Referência |
|------|-----------|
| **Frameworks** | `frameworks/impact-metrics-model.md`, `frameworks/community-flywheel.md` |
| **Checklists** | `checklists/impacto/vanity-metric-filter.md` |
| **Templates** | `templates/reports/weekly-readout.md` |
| **Registries** | `data/metrics/content-to-conversation.md` |
| **Workflows** | `workflows/04-measure-and-learn.md` |

### Regras de Fluxo
- **Rework:** Se quality gate reprovar → revisar metodologia, corrigir viés identificado e reexecutar análise
- **Escalation:** Se bloqueio ou decisão fora de escopo → escalar para Movement Chief
- **Handoff:** Output vai para → tasks de Review (impact-review) e próximo ciclo de Strategy
