---
id: artifact-freshness-review
name: "Review de Frescor dos Artefatos"
squad: movement
type: task
category: review
agents: [manifestador-criativo, designer-identitario, analista-semiotico]
frameworks: [artifact-lifecycle-framework, freshness-assessment-model]
checklists: [artifact-freshness-checklist]
templates: [freshness-audit-template, refresh-plan-template]
version: "1.0"
tags: [review, artefatos, frescor, renovacao, relevancia, fadiga]
---

# Review de Frescor dos Artefatos

## Objetivo

Auditar o frescor e relevância de todos os artefatos do movimento — manifestos, memes, rituais, identidade visual, slogans — identificando quais ainda ressoam, quais estão perdendo impacto e quais precisam ser renovados ou aposentados.

## Contexto

Cultura se move rápido. O meme que arrepiava há 3 meses pode parecer datado hoje. O ritual que engajava pode estar gerando fadiga. Artefatos precisam ser renovados antes de virarem clichê. O review de frescor previne que o movimento fique preso no passado enquanto a cultura avança.

## Inputs Necessários

- Inventário completo de artefatos ativos
- Dados de performance por artefato (engajamento, compartilhamento)
- Trend Radar com tendências estéticas e narrativas
- Feedback da comunidade sobre artefatos
- Data de criação/última atualização de cada artefato
- Benchmarks visuais e narrativos atuais do setor

## Processo

1. **Inventariar artefatos ativos** — Listar todos: manifesto, slogans, memes, templates, rituais, Identity Kit, Creator Kit, onboarding materials, Community Kit. Registrar: data de criação, última atualização, frequência de uso.

2. **Avaliar performance recente** — Para cada artefato medível: como está performando vs. 3 meses atrás? Engajamento subindo, estável ou caindo? Compartilhamentos aumentando ou diminuindo?

3. **Testar ressonância atual** — Selecionar 10-15 artefatos-chave e fazer teste rápido: mostrar para 5-10 membros e perguntar: ainda provoca emoção? Ainda compartilharia? Parece atual ou datado?

4. **Comparar com zeitgeist** — Confrontar estética e linguagem dos artefatos com o que está prevalecendo culturalmente: os artefatos parecem atuais? A linguagem evoluiu? As referências visuais ainda são relevantes?

5. **Classificar por status** — Categorizar cada artefato: (a) Evergreen (atemporal, manter), (b) Atual (ainda ressoa, monitorar), (c) Envelhecendo (perda de impacto, planejar refresh), (d) Datado (precisa de refresh imediato), (e) Aposentar (não tem mais utilidade).

6. **Identificar gaps** — Há artefatos que deveriam existir mas não existem? A comunidade pediu algo que não temos? Há formatos novos que nossos artefatos não cobrem?

7. **Priorizar refreshes** — Para artefatos classificados como "envelhecendo" e "datado": priorizar por impacto (quais são mais usados e vistos) e urgência (quão datados estão).

8. **Criar refresh briefs** — Para cada artefato a ser renovado: o que manter (essência), o que mudar (forma), referências atuais, deadline, responsável.

9. **Planejar aposentadorias** — Para artefatos a aposentar: como retirar de circulação sem confundir a comunidade, como substituir com algo novo, como comunicar a mudança.

10. **Documentar e calendarizar** — Compilar refresh plan com timeline: quais artefatos serão renovados quando, quais aposentados, quais novos criados.

## Outputs Esperados

- **Inventário de artefatos** com status de frescor
- **Teste de ressonância** resultados
- **Classificação por status** (evergreen → aposentar)
- **Lista de gaps** identificados
- **Refresh briefs** para artefatos priorizados
- **Refresh Plan** com timeline

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Artefatos auditados | 100% do inventário |
| Teste de ressonância | >= 10 artefatos testados |
| Classificação | 100% dos artefatos classificados |
| Refresh briefs | 100% dos artefatos "datado" + "envelhecendo" |
| Gaps identificados | Documentados |
| Refresh Plan | Com timeline e responsáveis |

## Decision Points

- **Maioria evergreen/atual** → Operação normal, foco em novos artefatos para gaps
- **Muitos envelhecendo** → Acelerar ciclo de produção criativa
- **Artefato core datado (manifesto, slogan)** → Prioridade máxima de refresh
- **Comunidade apegada a artefato datado** → Refresh gradual, não substituição abrupta

## Integração

- **Alimenta:** `create-memetic-assets`, `create-identity-artifacts`, `create-movement-content`
- **Recebe de:** `measure-movement-health`, `track-cultural-trends`
- **Workflow relacionado:** `13-artifact-refresh-cycle`, `12-identity-evolution-flow`
- **Cadência:** Mensal (review rápido), trimestral (auditoria completa)
- **Handoff:** Refresh briefs vão para agentes de criação
