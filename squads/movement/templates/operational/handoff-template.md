---
id: tmpl-mov-ops-003
name: Template de Handoff entre Squads
squad: movement
type: template
category: operational
tags: [handoff, transição, squads, colaboração, entrega]
---

# Template de Handoff entre Squads

## Instruções de Uso

O Handoff documenta a transferência de trabalho entre o squad de movimento e outros
squads (design, mídia, conteúdo, etc). Handoffs mal feitos geram retrabalho, perda
de contexto e desalinhamento. Este template garante que nada se perca na transição.

**Quando usar:** Sempre que entregar trabalho para outro squad ou receber de outro.
**Quem preenche:** Squad que está entregando.
**Princípio:** Se o squad receptor não consegue trabalhar só com este documento, o handoff falhou.

---

## Template

### 1. Informações da Entrega

**De:** {{squad_origem}} — {{pessoa_origem}}
**Para:** {{squad_destino}} — {{pessoa_destino}}
**Data:** {{data_handoff}}
**Projeto:** {{nome_projeto}}
**Deadline:** {{deadline_entrega_final}}

### 2. Contexto

**O que é esse projeto:**
{{contexto_projeto}}

**Onde estamos:**
{{status_atual}}

**O que já foi feito:**
| Entregável | Status | Link |
|-----------|--------|------|
| {{entregavel_1}} | {{status_1}} | {{link_1}} |
| {{entregavel_2}} | {{status_2}} | {{link_2}} |
| {{entregavel_3}} | {{status_3}} | {{link_3}} |

### 3. O Que Precisamos de Vocês

**Entregáveis solicitados:**
| # | Entregável | Especificação | Prazo |
|---|-----------|---------------|-------|
| 1 | {{ent_sol_1}} | {{spec_1}} | {{prazo_1}} |
| 2 | {{ent_sol_2}} | {{spec_2}} | {{prazo_2}} |
| 3 | {{ent_sol_3}} | {{spec_3}} | {{prazo_3}} |

### 4. Diretrizes e Guardrails

**Tom de voz:** {{tom}}
**Referências visuais/criativas:** {{referencias}}
**O que NÃO fazer:** {{restricoes}}

**Documentos de referência:**
- {{doc_ref_1}} — {{link_ref_1}}
- {{doc_ref_2}} — {{link_ref_2}}

### 5. Stakeholders e Aprovação

| Pessoa | Papel | Contato |
|--------|-------|---------|
| {{stake_1}} | {{papel_1}} | {{contato_1}} |
| {{stake_2}} | {{papel_2}} | {{contato_2}} |

**Processo de aprovação:** {{processo_aprovacao}}
**Número de rodadas esperado:** {{rodadas}}

### 6. Timeline

| Etapa | Data | Responsável |
|-------|------|-------------|
| Kick-off/alinhamento | {{data_kickoff}} | {{resp_kick}} |
| Primeira entrega | {{data_v1}} | {{resp_v1}} |
| Feedback | {{data_feedback}} | {{resp_feedback}} |
| Entrega final | {{data_final}} | {{resp_final}} |

### 7. Riscos e Dependências

| Risco/Dependência | Impacto | Mitigação |
|-------------------|---------|-----------|
| {{risco_1}} | {{impacto_1}} | {{mit_1}} |
| {{risco_2}} | {{impacto_2}} | {{mit_2}} |

### 8. Checklist de Handoff

**Squad que entrega confirma:**
- [ ] Contexto e objetivos estão claros
- [ ] Todos os materiais de referência estão acessíveis
- [ ] Prazos são realistas e acordados
- [ ] Ponto de contato definido para dúvidas
- [ ] Critérios de aprovação estão explícitos

**Squad que recebe confirma:**
- [ ] Leu e entendeu o handoff
- [ ] Tem acesso a todos os materiais
- [ ] Concorda com os prazos
- [ ] Sabe quem é o ponto de contato

---

## Exemplo Preenchido

### Informações
**De:** Movement Squad — Ana
**Para:** Design Squad — Carlos
**Projeto:** Kit visual para campanha "Rótulo da Semana"
**Deadline:** 20/03/2026

### O Que Precisamos
| # | Entregável | Spec | Prazo |
|---|-----------|------|-------|
| 1 | Template de card Instagram | Canva editável, com e sem foto | 15/03 |
| 2 | Frame para Stories | Transparente, 4 variações | 15/03 |
| 3 | Pack de stickers WhatsApp | 10 stickers, estilo do movimento | 18/03 |

### Guardrails
**Tom:** Visual cru, tipografia industrial, cores do movimento (amarelo + preto).
**Não fazer:** Nada "clean" ou "minimalista demais" — queremos estética de rótulo real.
**Ref:** Identity charter (link), mood board (link).

---

## Dicas

- **O handoff é um contrato.** Se não está escrito, não foi pedido.
- **Inclua o "por quê".** O squad receptor trabalha melhor quando entende o contexto.
- **Links funcionais.** Verifique que todos os links abrem e os acessos estão dados.
- **Uma reunião de kick-off** de 15 minutos economiza horas de retrabalho.
- **Feedback construtivo.** Quando devolver com comentários, seja específico e respeitoso.
- **Agradeça.** Reconhecer o trabalho do outro squad fortalece a colaboração futura.
