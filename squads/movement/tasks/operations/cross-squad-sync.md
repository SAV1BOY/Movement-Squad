---
id: cross-squad-sync
name: "Sincronização Cross-Squad"
squad: movement
type: task
category: operations
agents: [arquiteto-movimento, estrategista-movimento]
frameworks: [cross-squad-sync-framework, narrative-alignment-model]
checklists: [cross-squad-checklist]
templates: [sync-agenda-template, handoff-template]
version: "1.0"
tags: [operations, cross-squad, sincronizacao, alinhamento, handoff]
---

# Sincronização Cross-Squad

## Objetivo

Manter alinhamento contínuo entre o Movement Squad e os demais squads (Copy, Brand, Story, Traffic, etc.) — garantindo que a narrativa do movimento seja respeitada e amplificada corretamente em todos os pontos de contato gerenciados por outros times.

## Contexto

O movimento não existe isolado. Outros squads produzem conteúdo, gerenciam canais, criam campanhas e interagem com o público. Se não há sincronização, o movimento diz uma coisa e o email marketing diz outra. Cross-squad sync é o que garante orquestração narrativa — muitas vozes, uma história.

## Inputs Necessários

- Thesis Document e manifesto atuais
- Identity System e guidelines
- Calendar de ativações do movimento
- Outputs recentes de cada squad parceiro
- Narrative Consistency Review mais recente
- Roadmap do próximo período

## Processo

1. **Mapear touchpoints por squad** — Documentar: quais squads produzem outputs que mencionam ou deveriam estar alinhados com o movimento? Quais são os pontos de contato? Com qual frequência produzem?

2. **Definir cadência de sync** — Estabelecer: sync semanal breve (15min) com squads de produção diária (Copy, Content), sync quinzenal com squads de campanha (Traffic, Performance), sync mensal com squads estratégicos (Brand, Story).

3. **Preparar update do movimento** — Para cada sync, preparar: o que está acontecendo no movimento esta semana/quinzena, quais mensagens priorizar, quais evitar, oportunidades de sinergia.

4. **Coletar inputs dos squads** — Em cada sync, perguntar: o que vocês estão planejando que impacta o movimento? Há conflitos de narrativa? Precisam de assets/guidelines? Têm feedback do público sobre o movimento?

5. **Identificar conflitos narrativos** — Se outputs de outros squads conflitam com a narrativa do movimento: levantar respeitosamente, propor alternativa, alinhar antes da publicação.

6. **Fazer handoffs estruturados** — Quando o Movement Squad produz algo que outros squads precisam usar: entregar com briefing claro, guidelines de adaptação, do's e don'ts, contato para dúvidas.

7. **Receber handoffs** — Quando outros squads produzem algo que impacta o movimento: revisar alinhamento narrativo, aprovar ou sugerir ajustes antes da publicação.

8. **Criar shared calendar** — Manter calendário compartilhado onde todos os squads veem: ativações do movimento, lançamentos de campanha, datas importantes, momentos de confluência.

9. **Resolver conflitos de prioridade** — Quando ações de diferentes squads conflitam em timing ou mensagem: facilitar negociação e encontrar solução que preserve a narrativa do movimento.

10. **Documentar acordos** — Registrar: decisões de alinhamento, guidelines compartilhados, processos de handoff, contatos-chave por squad.

## Outputs Esperados

- **Sync sessions** realizadas na cadência definida
- **Mapa de touchpoints** por squad atualizado
- **Shared calendar** mantido
- **Handoffs estruturados** documentados
- **Conflitos resolvidos** e documentados
- **Guidelines cross-squad** atualizados

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Syncs realizados | >= 80% da cadência definida |
| Squads cobertos | 100% dos squads que impactam o movimento |
| Conflitos resolvidos | 100% antes de publicação |
| Handoffs com briefing | 100% |
| Calendar atualizado | Semanalmente |

## Decision Points

- **Squad parceiro consistentemente desalinhado** → Escalar para liderança e investir em treinamento
- **Oportunidade de sinergia detectada** → Propor ação conjunta e co-criar
- **Conflito de prioridade irreconciliável** → Escalar para decisor comum
- **Processo de sync pesado demais** → Simplificar e focar em async com check-ins pontuais

## Integração

- **Alimenta:** `narrative-consistency-review`, outputs de squads parceiros
- **Recebe de:** Todos os outputs de criação e ativação do Movement Squad
- **Workflow relacionado:** `14-cross-squad-narrative-handoff`, `20-monthly-narrative-sync`
- **Cadência:** Semanal/quinzenal/mensal (conforme squad)
- **Handoff:** Guidelines e briefings para squads parceiros
