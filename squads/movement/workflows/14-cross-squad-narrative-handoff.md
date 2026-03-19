---
id: cross-squad-narrative-handoff
name: "Handoff Narrativo: Movement → Copy, Brand, Story, Traffic"
squad: movement
type: workflow
agents: [movement-architect, estrategista-de-ciclo]
cadence: monthly
version: "1.0"
tags: [workflow, handoff, cross-squad, narrativa, alinhamento, sincronizacao]
---

# Handoff Narrativo: Movement → Copy, Brand, Story, Traffic

## Objetivo

Garantir que a narrativa do movimento seja corretamente transmitida, adaptada e preservada quando passa para outros squads que produzem conteúdo e ações em nome da marca — evitando distorção, diluição ou contradição da mensagem.

## Diagrama de Fases

```
[PREPARAÇÃO]      [HANDOFF]         [ACOMPANHAMENTO]  [REVIEW]
Empacotar     →   Entregar e    →   Suportar e    →   Auditar e
Narrativa         Treinar           Consultar         Ajustar
   |                 |                  |                  |
   v                 v                  v                  v
Narrative Kit,   Sessão de         Dúvidas            Consistência
guidelines,      imersão por       respondidas,       verificada,
do's/don'ts      squad             outputs            guidelines
                                   revisados          atualizados
```

## Fases Detalhadas

### Fase 1: Preparação do Narrative Kit (Dia 1-5)

**Agentes:** movement-architect, estrategista-de-ciclo

**Inputs:**
- Thesis Document atualizado
- Identity System e glossário
- Manifesto e slogans
- Counter-Narrative Playbook (seção relevante)
- Exemplos de conteúdo do movimento bem executado

**Ações:**
1. Produzir Narrative Kit customizado por squad: versão simplificada da thesis, tom de voz com exemplos, glossário essencial, do's e don'ts, templates de referência
2. Criar seção específica por squad: para Copy (guia de linguagem), para Brand (guia de identidade), para Story (arco narrativo), para Traffic (messaging de conversão)
3. Incluir anti-exemplos: o que NÃO fazer com a narrativa do movimento
4. Preparar FAQ: perguntas que cada squad provavelmente terá

**Outputs:**
- Narrative Kit por squad
- FAQ por squad
- Anti-exemplos documentados

**Decision Gate:**
- Kits completos e revisados → agendar sessões de handoff
- Informação incompleta → completar antes de entregar

### Fase 2: Handoff e Treinamento (Dia 6-10)

**Agentes:** movement-architect

**Inputs:**
- Narrative Kits prontos
- Calendar de sessões agendado

**Ações:**
1. Conduzir sessão de 45-60min com cada squad: apresentar thesis (fazendo sentir, não só explicar), demonstrar tom de voz, percorrer do's e don'ts
2. Mostrar exemplos de aplicação correta e incorreta
3. Abrir para perguntas e cenários hipotéticos ("e se eu precisar...")
4. Designar ponto de contato no Movement Squad para dúvidas
5. Entregar Narrative Kit e links de acesso

**Outputs:**
- Sessões realizadas com cada squad
- Pontos de contato definidos
- Kits distribuídos

**Decision Gate:**
- Squads confiantes → avançar para operação
- Squads com muitas dúvidas → agendar follow-up em 1 semana

### Fase 3: Acompanhamento e Consultoria (Contínuo)

**Agentes:** estrategista-de-ciclo

**Inputs:**
- Dúvidas dos squads parceiros
- Outputs em produção que mencionam o movimento

**Ações:**
1. Responder dúvidas de squads parceiros em até 24h
2. Revisar outputs críticos antes da publicação (quando solicitado)
3. Participar de brainstorms de outros squads quando envolvem o movimento
4. Sinalizar proativamente quando detecta output desalinhado
5. Manter canal assíncrono de comunicação (Slack/Teams)

**Outputs:**
- Dúvidas respondidas
- Outputs revisados
- Alertas de desalinhamento

**Decision Gate:**
- Fluxo suave → manter cadência
- Muitas dúvidas → melhorar guidelines e remarcar sessão

### Fase 4: Auditoria e Ajuste (Mensal)

**Agentes:** fenomenologo, movement-architect

**Inputs:**
- Outputs publicados por squads parceiros
- Narrative Consistency Review

**Ações:**
1. Amostra de outputs de cada squad que tocam a narrativa do movimento
2. Avaliar consistência contra guidelines
3. Para desvios: documentar e comunicar ao squad responsável
4. Para padrões de desvio: atualizar guidelines e remarcar treinamento
5. Reconhecer squads que mantêm consistência exemplar

**Outputs:**
- Auditoria de consistência por squad
- Feedback compartilhado
- Guidelines atualizados (se necessário)

**Decision Gate:**
- Consistência >= 80% → manter processo atual
- Consistência < 80% → intensificar suporte e treinamento

## Cadência

| Ação | Frequência |
|------|-----------|
| Atualização de Narrative Kit | Mensal ou quando thesis muda |
| Sessão de handoff | Trimestral (ou quando thesis muda) |
| Consultoria assíncrona | Contínua |
| Auditoria de consistência | Mensal |

## Artefatos Produzidos

- Narrative Kit por squad
- FAQ de narrativa
- Registro de consultorias
- Auditoria de consistência

## Métricas de Sucesso

| Métrica | Meta |
|---------|------|
| Narrative Kit atualizado | <= 1 semana após mudança de thesis |
| Sessões de handoff realizadas | 100% dos squads parceiros |
| Tempo de resposta a dúvidas | <= 24h |
| Consistência narrativa cross-squad | >= 80% |
| Desvios críticos | 0 |
| Satisfação dos squads parceiros | >= 8/10 |

## Integração

| Tipo | Referência |
|------|-----------|
| **Tasks** | `tasks/operations/cross-squad-sync.md`, `tasks/review/narrative-consistency-review.md` |
| **Frameworks** | `frameworks/architect-channel-architecture.md`, `frameworks/architect-system-map.md`, `frameworks/narrative-graph-framework.md` |
| **Checklists** | `checklists/architect/architect-cross-squad-integration.md`, `checklists/narrative-coherence-quality.md`, `checklists/architect/architect-system-coherence.md` |
| **Registries** | `data/registries/decision-log.yaml` |

### Regras de Fluxo
- **Quality Gate entre fases:** Preparação→Sessão: Narrative Kit atualizado; Sessão→Follow-up: decisões documentadas; Auditoria: consistência ≥ 80%
- **Rework:** Se consistência < 80% → intensificar suporte e treinamento com squads afetados
- **Escalation:** Se handoff rejeitado 2x por squad receptor → escalar para Chiefs dos dois squads
- **Handoff:** Narrative Kit e guidelines alimentam → todos os squads parceiros (brand, copy, storytelling, traffic, design)
