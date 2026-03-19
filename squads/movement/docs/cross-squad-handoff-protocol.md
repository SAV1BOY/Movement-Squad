---
id: cross-squad-handoff-protocol
name: "Cross-Squad Handoff Protocol"
squad: movement
type: doc
category: operacional
tags:
  - handoff
  - cross-squad
  - integracao
  - protocolo
  - quality-gate
---

# Cross-Squad Handoff Protocol — Protocolo de Handoff entre Squads

## Objetivo

Definir o processo padronizado para enviar e receber entregáveis entre o
Movement Squad e outros squads. Um handoff mal feito gera retrabalho, atrito
e perda de qualidade. Este protocolo garante que toda transferência seja
completa, contextualizada e com qualidade verificada.

---

## Tipos de Handoff

### Outbound (Movement → Outro Squad)

O Movement Squad envia outputs para outros squads consumirem ou refinarem.

| Squad Receptor | O que Enviamos |
|---------------|---------------|
| Brand Squad | Cultural insights, identity codes, movement narrative |
| Copy Squad | Slogans validados, manifesto copy, movement language |
| Storytelling Squad | Movement thesis, cultural tensions, identity narrative |
| Traffic Squad | Memetic assets, manifesto clips, community UGC |
| Design Squad | Identity symbols, movement visual language |
| Data Squad | Experiment results, movement health metrics, signal data, community metrics |
| Deep Research Squad | Research briefs, signal clusters, thesis hypotheses |
| Advisory Board Squad | Movement health reports, kill/pivot recommendations, quarterly reviews |
| C-Level Squad | Movement impact reports, quarterly reviews, crisis alerts |

### Inbound (Outro Squad → Movement)

O Movement Squad recebe inputs de outros squads como base para seu trabalho.

| Squad Emissor | O que Recebemos |
|--------------|----------------|
| Brand Squad | Brand positioning, brand guidelines, brand purpose |
| Copy Squad | Copy frameworks, headlines testados |
| Storytelling Squad | Public narrative (Ganz), founder story |
| Traffic Squad | Ad performance data, winning hooks |
| Design Squad | Visual identity, design system |
| Data Squad | Analytics dashboards, experiment infrastructure, cohort models, data pipelines |
| Deep Research Squad | Cultural deep-dives, competitive analysis, academic foundations, trend reports |
| Advisory Board Squad | Strategic direction, capital allocation, governance decisions, culture guidelines |
| C-Level Squad | Brand vision, business objectives, CMO priorities, resource approval |

---

## Protocolo Passo-a-Passo

### Passo 1 — Preparar

O agente responsável prepara o output para handoff:
- Verificar que o output passou pelos gates internos (Níveis 1-4 da cascata)
- Preencher o template de handoff com contexto, objetivo e instruções
- Garantir que nomenclatura e formato seguem padrões do squad receptor

### Passo 2 — Quality Gate de Saída

Antes de enviar, aplicar o checklist de saída (ver seção abaixo):
- Se aprovado: avançar para Passo 3
- Se reprovado: corrigir e reaplicar o checklist

### Passo 3 — Empacotar

Criar o pacote de handoff:
- Output principal (artefato, documento, asset)
- Briefing de contexto (por que foi criado, para que serve)
- Instruções de uso (como o squad receptor deve usar)
- Referências (links para frameworks, dados ou decisões relevantes)

### Passo 4 — Enviar

Entregar o pacote ao squad receptor:
- Notificar o responsável do squad receptor
- Indicar prazo esperado de confirmação (padrão: 48h)
- Registrar envio no decision-log

### Passo 5 — Confirmar Recebimento

O squad receptor confirma:
- Recebimento do pacote
- Completude do briefing
- Aplicação do Quality Gate de Entrada
- Aceite ou rejeição com feedback

### Passo 6 — Feedback

Após consumir o output, squad receptor fornece feedback:
- O que funcionou bem
- O que precisou de ajuste
- Sugestões para próximos handoffs
- Feedback é registrado para melhoria contínua

---

## Quality Gate de Saída

Checklist obrigatório antes de enviar qualquer handoff:

- [ ] Output passou pelos gates internos do Movement Squad (Níveis 1-4)
- [ ] Template de handoff preenchido completamente
- [ ] Contexto estratégico incluído (tese, objetivo, público)
- [ ] Formato compatível com padrões do squad receptor
- [ ] Nomenclatura segue `naming-conventions.md`
- [ ] Sem dependências pendentes ou bloqueios
- [ ] Ethics check aprovado (quando output é público)
- [ ] Dados sensíveis removidos ou protegidos
- [ ] Responsável do squad receptor identificado
- [ ] Prazo de entrega alinhado

---

## Quality Gate de Entrada

Checklist ao receber handoff de outro squad:

- [ ] Pacote completo (output + briefing + instruções)
- [ ] Contexto suficiente para trabalhar sem perguntas adicionais
- [ ] Formato utilizável pelo Movement Squad
- [ ] Alinhamento com a tese e identidade do movimento atual
- [ ] Dados ou pesquisa incluídos são verificáveis
- [ ] Sem conflitos com outputs existentes do squad
- [ ] Prazo de uso/entrega definido
- [ ] Responsável interno do Movement Squad atribuído

---

## Template de Handoff

Usar o template padrão para documentar cada handoff:

```yaml
handoff:
  id: "HO-YYYY-MM-DD-XXX"
  direcao: "" # outbound | inbound
  squad_origem: ""
  squad_destino: ""
  responsavel_origem: ""
  responsavel_destino: ""
  output: ""
  descricao: ""
  contexto: ""
  instrucoes_de_uso: ""
  referencias: []
  prazo_confirmacao: ""
  status: "" # enviado | recebido | aceito | rejeitado
  feedback: ""
  data_envio: ""
  data_confirmacao: ""
```

Referência: `templates/operational/handoff-template.md`

---

## Registro

Todo handoff deve ser registrado:
- **Outbound:** Entrada no decision-log com tipo "handoff-out"
- **Inbound:** Entrada no decision-log com tipo "handoff-in"
- **Rejeição:** Registrar motivo e ação corretiva

---

## Escalação

Quando um handoff é rejeitado:

| Situação | Ação |
|----------|------|
| 1a rejeição | Agente corrige com base no feedback e reenvia |
| 2a rejeição | Chiefs dos dois squads alinham formato e critérios |
| Dependência bloqueante | Chief notifica + define deadline, escala se não resolvido em 48h |
| Impasse | Escalação para nível organizacional acima dos Chiefs |

Protocolo de escalação detalhado em `config.yaml` seção `escalation > cross_squad`.

---

## Squads Integrados

O Movement Squad mantém handoffs ativos com 9 squads, conforme `config.yaml`
seção `cross_squad`:

| Squad | Ativos Compartilhados | Frequência Típica |
|-------|----------------------|-------------------|
| **Brand Squad** | identity-codes, brand-purpose-to-movement-thesis | Semanal |
| **Copy Squad** | slogan-bank, phrases-library | Semanal |
| **Storytelling Squad** | movement-theses, cultural-tensions | Quinzenal |
| **Traffic Squad** | memetic-assets, hook-bank | Semanal |
| **Design Squad** | symbol-systems, visual-identity | Quinzenal |
| **Data Squad** | experiment-log, health-score-dashboard, cohort-retention-data | Semanal |
| **Deep Research Squad** | research-briefs, cultural-context, academic-references | Quinzenal |
| **Advisory Board Squad** | decision-log, quarterly-reviews, strategic-alignment | Mensal |
| **C-Level Squad** | business-impact-metrics, quarterly-movement-review, brand-reputation-score | Mensal |

---

## Referências

- `config.yaml` seção `cross_squad` — Definição completa de handoffs por squad
- `config.yaml` seção `escalation > cross_squad` — Regras de escalação
- `docs/cross-squad-integration-guide.md` — Guia geral de integração
- `docs/quality-gate-cascade.md` — Cascata de quality gates (Nível 5)
- `data/registries/decision-log.yaml` — Registro de decisões e handoffs
