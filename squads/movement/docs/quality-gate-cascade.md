---
id: quality-gate-cascade
name: "Cascata de Quality Gates"
squad: movement
type: doc
category: docs
version: 1.0.0
tags: [quality-gate, cascata, qualidade, processo, operacional]
---

# Cascata de Quality Gates

## Visão Geral

Quality gates são checkpoints de qualidade que todo artefato, decisão ou entrega
deve passar antes de avançar. No Movement Squad, os gates formam uma cascata —
cada nível valida um escopo diferente, do micro (tarefa individual) ao macro
(cross-squad). Este documento mapeia toda a cascata e explica como ela funciona.

## Diagrama da Cascata

```
┌─────────────────────────────────────────────────────────┐
│                    CAMADA 6: HRM                        │
│         Compliance geral do operating system            │
│  ┌───────────────────────────────────────────────────┐  │
│  │              CAMADA 5: CROSS-SQUAD                │  │
│  │         Handoff entre squads avaliado             │  │
│  │  ┌─────────────────────────────────────────────┐  │  │
│  │  │            CAMADA 4: SQUAD                  │  │  │
│  │  │      Sprint review e health check           │  │  │
│  │  │  ┌───────────────────────────────────────┐  │  │  │
│  │  │  │         CAMADA 3: DOMAIN              │  │  │  │
│  │  │  │   Revisão por lead do domínio         │  │  │  │
│  │  │  │  ┌─────────────────────────────────┐  │  │  │  │
│  │  │  │  │       CAMADA 2: TASK            │  │  │  │  │
│  │  │  │  │   Checklist de entrega          │  │  │  │  │
│  │  │  │  │  ┌───────────────────────────┐  │  │  │  │  │
│  │  │  │  │  │    CAMADA 1: AGENT       │  │  │  │  │  │
│  │  │  │  │  │  Autoavaliação pessoal   │  │  │  │  │  │
│  │  │  │  │  └───────────────────────────┘  │  │  │  │  │
│  │  │  │  └─────────────────────────────────┘  │  │  │  │
│  │  │  └───────────────────────────────────────┘  │  │  │
│  │  └─────────────────────────────────────────────┘  │  │
│  └───────────────────────────────────────────────────┘  │
└─────────────────────────────────────────────────────────┘
```

## Gate por Camada

### Camada 1: Agent (Autoavaliação)

**Quem aplica:** O próprio agent antes de entregar qualquer artefato
**Quando:** Antes de submeter para revisão

| Critério | Pergunta | Pass/Fail |
|----------|----------|-----------|
| Completude | O artefato está completo conforme o escopo definido? | |
| Alinhamento | Está alinhado com a tese e identidade do movimento? | |
| Qualidade mínima | Está revisado quanto a erros, tom e formatação? | |
| Evidências | Afirmações estão sustentadas por dados ou sinais reais? | |
| Formato | Segue o template ou padrão aplicável? | |

**Se falhar:** Agent corrige antes de submeter. Não ocupa tempo de revisores.

### Camada 2: Task (Checklist de Entrega)

**Quem aplica:** Agent executor + 1 revisor (peer review)
**Quando:** Ao concluir uma task/entrega específica

| Critério | Pergunta | Pass/Fail |
|----------|----------|-----------|
| Escopo atendido | Todos os requisitos da task foram atendidos? | |
| Quality standard | Atende ao padrão de qualidade do squad? | |
| Documentação | Decisões e racional estão documentados? | |
| Testado | Foi testado/validado antes de entregar (se aplicável)? | |
| Dependências | Dependências downstream estão notificadas? | |

**Se falhar:** Volta para o agent com feedback específico do revisor.

### Camada 3: Domain (Revisão de Lead)

**Quem aplica:** Lead do domínio (narrativa, comunidade, estratégia, etc.)
**Quando:** Antes de publicar/distribuir ou entregar para outro domínio

| Critério | Pergunta | Pass/Fail |
|----------|----------|-----------|
| Consistência | Está consistente com outros artefatos do domínio? | |
| Estratégia | Está alinhado com a estratégia do ciclo atual? | |
| Qualidade narrativa | Tom, linguagem e posicionamento estão corretos? | |
| Risco | Há algum risco reputacional, legal ou cultural? | |
| Métricas | Tem métricas de sucesso definidas (se aplicável)? | |

**Se falhar:** Volta para a task com feedback do lead. Máximo 2 ciclos de rework.

### Camada 4: Squad (Sprint Review)

**Quem aplica:** Time completo na review semanal (ciclo Kaizen)
**Quando:** Semanalmente, ao final do ciclo

| Critério | Pergunta | Pass/Fail |
|----------|----------|-----------|
| Cadência | O loop semanal rodou completo? | |
| Health Score | O Movement Health Score está acima do threshold? | |
| Aprendizado | Aprendizados da semana foram documentados? | |
| Backlog | Backlog foi atualizado com base nos aprendizados? | |
| Riscos | Risk log foi revisado e atualizado? | |

**Se falhar:** Itens específicos entram no backlog da semana seguinte com prioridade.

### Camada 5: Cross-Squad (Handoff)

**Quem aplica:** Squad receptor usando a `cross-squad-handoff-rubric`
**Quando:** Em toda transição de trabalho entre squads

| Critério | Pergunta | Pass/Fail |
|----------|----------|-----------|
| Completude | Todos os artefatos prometidos foram entregues? | |
| Clareza | Documentação é autoexplicativa? | |
| Evidências | Dados e provas estão presentes e verificáveis? | |
| Rastreabilidade | Cadeia de decisões está documentada? | |
| Timing | Entrega dentro do prazo acordado? | |

**Classificação:** GOLD (100-125) / GOOD (75-99) / REVIEW (50-74) / REJECT (0-49)
**Se REJECT:** Devolve ao squad de origem. Se REVIEW: reunião de alinhamento em 48h.

### Camada 6: HRM (Compliance Geral)

**Quem aplica:** Chief of Movement + auditoria periódica
**Quando:** Mensalmente (auditoria de decisões) e trimestralmente (compliance)

| Critério | Pergunta | Pass/Fail |
|----------|----------|-----------|
| Governança | Decisões seguem o framework de governança? | |
| Ética | Operações respeitam boundaries éticos? | |
| Documentação | Decision logs e registros estão atualizados? | |
| Qualidade sistêmica | Quality gates estão sendo aplicados consistentemente? | |
| Melhoria contínua | Kaizen está rodando e gerando aprendizados? | |

**Se falhar:** Plano de correção com prazo, reportado a stakeholders se necessário.

## Fluxo de Rejeição/Rework

```
Artefato submetido ao gate
  ↓
Gate avalia critérios
  ↓
┌──── PASS → avança para próximo gate ou entrega final
│
└──── FAIL → feedback específico gerado
        ↓
      Owner recebe feedback
        ↓
      Rework executado (prazo: igual ou menor que original)
        ↓
      Resubmetido ao mesmo gate
        ↓
      ┌──── PASS → avança
      │
      └──── FAIL (2ª vez) → escalar para camada acima
              ↓
            Lead/Chief avalia: rework viável ou escopo errado?
              ↓
            ┌──── Rework viável → última tentativa com suporte
            │
            └──── Escopo errado → redesign com nova definição
```

## Exemplos de Cascata

### Exemplo 1: Post de conteúdo para redes sociais

1. **Agent:** Narrative architect cria o post, faz autoavaliação (Camada 1) ✓
2. **Task:** Peer review com outro criador — feedback sobre CTA (Camada 2) → rework → ✓
3. **Domain:** Lead de narrativa revisa tom e alinhamento com tese (Camada 3) ✓
4. **Squad:** Post entra na sprint review semanal com métricas (Camada 4) ✓

### Exemplo 2: Pesquisa cultural entregue para outro squad

1. **Agent → Task → Domain:** Pesquisa passa pelas 3 primeiras camadas ✓
2. **Squad:** Review semanal confirma qualidade (Camada 4) ✓
3. **Cross-Squad:** Squad receptor avalia com handoff rubric → REVIEW (68 pts)
   → Reunião de alinhamento → Complementação → GOOD (82 pts) ✓

### Exemplo 3: Decisão de sunset de movimento

1. Todas as camadas anteriores alimentam a decisão
2. **HRM (Camada 6):** Chief verifica que processo seguiu governança ✓
3. Relatório final de sunset passa por Camada 4 (squad review) e Camada 6 (compliance) ✓

## Onde Encontrar Cada Gate

| Camada | Documento de Referência |
|--------|------------------------|
| 1 - Agent | Checklists por tipo de artefato em `checklists/` |
| 2 - Task | Templates de entrega em `templates/` |
| 3 - Domain | Rubricas em `lib/utilities/` |
| 4 - Squad | Ciclo Kaizen em `frameworks/ralphloop-kaizen` |
| 5 - Cross-Squad | `cross-squad-handoff-rubric` + `cross-squad-handoff-protocol` |
| 6 - HRM | `movement-governance-framework` |

## Integração

- Camada 1-3 rodam dentro do `movement-engine-5-loop`
- Camada 4 roda no `ralphloop-kaizen` (sexta-feira)
- Camada 5 usa o `cross-squad-handoff-rubric` e `handoff-component`
- Camada 6 segue o `movement-governance-framework`
- Rejeições geram rework via protocolo do governance framework
