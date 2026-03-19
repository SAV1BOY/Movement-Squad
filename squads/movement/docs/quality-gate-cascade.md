---
id: quality-gate-cascade
name: "Quality Gate Cascade"
squad: movement
type: doc
category: quality
tags:
  - quality-gate
  - cascata
  - revisao
  - governanca
  - operacional
---

# Quality Gate Cascade — Cascata de Portões de Qualidade

## Objetivo

Todo output produzido pelo Movement Squad passa por uma cascata de verificação
antes de ser considerado pronto. Este documento detalha os 6 níveis da cascata,
quem aplica cada um, quando e o que acontece se o output reprovar.

A cascata existe para garantir que nenhum artefato saia do squad sem a qualidade
mínima necessária. Quanto mais cedo um problema é detectado, menor o custo de
correção. Um erro pego no Nível 1 custa minutos; no Nível 6 pode custar semanas.

---

## Diagrama Visual

```
┌─────────────────────────────────────────────┐
│  Nível 1 — Agent Self-Eval                  │  Quem produz, avalia primeiro
├─────────────────────────────────────────────┤
│  Nível 2 — Task Gate                        │  Checklist obrigatório da task
├─────────────────────────────────────────────┤
│  Nível 3 — Domain Gate                      │  Gate do domínio (research, identity...)
├─────────────────────────────────────────────┤
│  Nível 4 — Chief Review                     │  Movement Chief valida estratégia
├─────────────────────────────────────────────┤
│  Nível 5 — Cross-Squad Gate                 │  Squad receptor valida handoff
├─────────────────────────────────────────────┤
│  Nível 6 — HRM Gate                         │  Human Review Manager (quando aplicável)
└─────────────────────────────────────────────┘
```

Cada nível é sequencial. O output só avança para o próximo nível se aprovado no anterior.

---

## Detalhamento por Nível

### Nível 1 — Agent Self-Eval

- **Quem aplica:** O agente que produziu o output
- **Quando:** Imediatamente após concluir a tarefa
- **Critérios:**
  - Output atende ao objetivo descrito na task
  - Formato segue o template esperado
  - Sem erros óbvios de conteúdo ou estrutura
  - Referências e dados estão corretos
- **Se reprovar:** Agente corrige antes de submeter. Não gera registro.

### Nível 2 — Task Gate

- **Quem aplica:** Checklist específico da task (automático ou manual)
- **Quando:** Ao marcar task como concluída
- **Critérios:**
  - Checklist da task 100% preenchido
  - Todos os outputs obrigatórios presentes
  - Nomenclatura segue `naming-conventions.md`
  - Metadados YAML corretos (quando aplicável)
- **Se reprovar:** Task retorna ao agente com itens faltantes listados.

### Nível 3 — Domain Gate

- **Quem aplica:** Gate do domínio correspondente (conforme `config.yaml > quality_gates > per_domain`)
- **Quando:** Ao concluir conjunto de tasks de um domínio
- **Critérios:**
  - research: `cultural-insight-quality`, `phenomenology-signal-capture`
  - identity: `we-us-now-identity`, `boundary-and-belonging`
  - creation: `manifesto-quality`, `memetic-asset-quality`, `ritual-design-quality`
  - activation: `distribution-plan-quality`, `community-activation-quality`
  - measurement: `experimentation-quality`, `vanity-metric-filter`
  - governance: `ethics-and-boundaries`, `claim-proof-standard`
- **Se reprovar:** Output retorna ao agente do domínio com feedback específico do gate.

### Nível 4 — Chief Review

- **Quem aplica:** Movement Chief (chief-of-movement)
- **Quando:** Antes de publicação, lançamento ou handoff externo
- **Critérios:**
  - Alinhamento estratégico com a tese do movimento
  - Coerência com identidade coletiva
  - Risco reputacional avaliado
  - Gates obrigatórios (`movement-thesis-quality`, `identity-system-quality`, `impact-dashboard-quality`) aprovados
- **Se reprovar:** Chief documenta motivo no decision-log e define ação: rework ou pivot.

### Nível 5 — Cross-Squad Gate

- **Quem aplica:** Squad receptor do handoff
- **Quando:** Ao receber output de handoff cross-squad
- **Critérios:**
  - Output no formato esperado pelo squad receptor
  - Briefing completo com contexto e objetivo
  - Qualidade suficiente para o squad receptor trabalhar sem retrabalho
  - Conforme protocolo em `docs/cross-squad-handoff-protocol.md`
- **Se reprovar:** Handoff retorna ao Movement Squad com feedback. Se rejeitado 2x, Chiefs alinham formato e critérios.

### Nível 6 — HRM Gate

- **Quem aplica:** Human Review Manager (stakeholder humano)
- **Quando:** Conforme definido em `config.yaml > review_triggers`
- **Critérios:**
  - Sensibilidade cultural ou ética requer olhar humano
  - Decisões de alto impacto (lançamento, sunset, pivot)
  - Output público que representa a marca
- **Se reprovar:** HRM define se é rework, pivot ou kill. Registro obrigatório no decision-log.

---

## Fluxo de Rejeição / Rework

Quando um output reprova em qualquer nível:

1. **Registro** — O motivo da rejeição é documentado (nível 3+ vai para decision-log)
2. **Feedback** — Feedback específico e acionável é entregue ao agente
3. **Rework** — Agente corrige e resubmete ao mesmo nível
4. **Limite** — Máximo 3 ciclos de rework no mesmo nível. Se reprovar 3x, escala para o nível acima
5. **Root Cause** — Na 2a rejeição, análise de causa raiz é obrigatória

```
Output reprovado → Feedback → Rework → Resubmissão ao mesmo nível
                                          ↓ (se reprovado 3x)
                                    Escalação ao nível superior
```

---

## Exemplo de Cascata Completa

**Cenário:** Narrative Architect cria um manifesto para o movimento.

| Nível | Ação | Resultado |
|-------|------|-----------|
| 1 — Self-Eval | Architect revisa estrutura, tom, coerência com tese | Aprovado |
| 2 — Task Gate | Checklist `manifesto-quality` preenchido: 8/8 itens | Aprovado |
| 3 — Domain Gate | Gate `creation` valida identidade coletiva e enemy-dream | Reprovado — enemy mal calibrado |
| 3 — Rework | Architect ajusta posicionamento do enemy | Aprovado |
| 4 — Chief Review | Chief valida alinhamento estratégico e risco | Aprovado |
| 5 — Cross-Squad | Copy Squad recebe para refinamento de linguagem | Aprovado |
| 6 — HRM | Stakeholder humano valida antes de publicação | Aprovado |

**Tempo total:** 3 dias (incluindo 1 ciclo de rework no Nível 3)

---

## Gates Obrigatórios (Toda Ação)

Conforme `config.yaml`, três gates são obrigatórios para toda ação do squad:

1. `movement-thesis-quality` — Toda ação começa com tese validada
2. `identity-system-quality` — Identidade coletiva definida e coerente
3. `impact-dashboard-quality` — Métricas definidas e acionáveis

Esses gates se aplicam transversalmente, independente do domínio.

---

## Referências

- `config.yaml` seção `quality_gates` — Gates por domínio
- `checklists/` — Checklists operacionais de cada gate
- `ARCHITECTURE.md` seção 9 — Quality Gates na arquitetura
- `docs/readiness-review-protocol.md` — Protocolo de readiness review
- `docs/cross-squad-handoff-protocol.md` — Protocolo de handoff
- `data/registries/decision-log.yaml` — Registro de decisões (rejeições nível 3+)
