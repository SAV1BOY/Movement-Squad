---
id: monthly-narrative-sync
name: "Sync Narrativo Mensal com Todos os Squads"
squad: movement
type: workflow
agents: [arquiteto-movimento, estrategista-movimento, analista-semiotico]
cadence: monthly
version: "1.0"
tags: [workflow, mensal, narrativa, sync, cross-squad, alinhamento, consistencia]
---

# Sync Narrativo Mensal com Todos os Squads

## Objetivo

Conduzir sessão mensal de sincronização narrativa com todos os squads que produzem conteúdo e comunicação — garantindo que a história do movimento seja contada de forma coerente, identificando conflitos e oportunidades de sinergia entre times.

## Diagrama de Fases

```
[PREPARAÇÃO]      [SESSÃO]          [FOLLOW-UP]       [MONITORAMENTO]
Auditar e     →   Sync de       →   Atualizar e   →   Acompanhar
Preparar          45 min            Distribuir         Consistência
   |                 |                  |                  |
   v                 v                  v                  v
Consistency      Update do         Guidelines        Outputs
audit rápida,    movimento,        atualizados,      revisados
agenda           alinhamento,      ações             antes de
definida         oportunidades     definidas         publicar
```

## Fases Detalhadas

### Fase 1: Preparação (Dia 1-3 antes da sessão)

**Agentes:** analista-semiotico, estrategista-movimento

**Inputs:**
- Narrative Consistency Review do mês
- Outputs recentes de todos os squads
- Atualizações no movimento (thesis, identidade, sinais)
- Calendar de ativações do próximo mês

**Ações:**
1. Rodar auditoria rápida de consistência: amostra de 15-20 outputs de squads parceiros
2. Identificar desvios narrativos do mês: onde a história foi contada diferente do esperado
3. Identificar oportunidades de sinergia: momentos onde squads podem amplificar mutuamente
4. Preparar agenda da sessão: update do movimento, desvios a corrigir, oportunidades, Q&A
5. Enviar pre-brief: "O que está acontecendo no movimento este mês" (1 página)

**Outputs:**
- Auditoria rápida de consistência
- Agenda preparada
- Pre-brief distribuído

**Decision Gate:**
- Desvios significativos → priorizar na sessão
- Tudo consistente → sessão focada em oportunidades e preview

### Fase 2: Sessão de Sync (45-60 minutos)

**Agentes:** arquiteto-movimento + representantes de cada squad

**Inputs:**
- Agenda e pre-brief
- Dúvidas acumuladas dos squads

**Ações:**
1. **Update do movimento (10min):** Onde estamos, o que mudou, quais sinais culturais são relevantes, quais temas priorizar/evitar este mês
2. **Feedback bidirecional (15min):** Squads compartilham o que está planejado, Movement Squad identifica conflitos ou oportunidades. Squads trazem dúvidas e feedback do público
3. **Correção de desvios (10min):** Apresentar desvios detectados na auditoria, explicar por que importa, alinhar como corrigir indo em frente
4. **Oportunidades de sinergia (10min):** Identificar momentos onde squads podem amplificar o movimento e vice-versa. Definir ações concretas de colaboração
5. **Q&A e alinhamento (5-10min):** Responder dúvidas, esclarecer áreas cinzentas, confirmar próximos passos

**Outputs:**
- Alinhamento narrativo atualizado
- Desvios corrigidos e comprometidos
- Oportunidades de sinergia com ações definidas
- Dúvidas esclarecidas

**Decision Gate:**
- Squads alinhados → seguir para follow-up
- Squads com resistência → sessão adicional 1:1 com squad específico

### Fase 3: Follow-Up e Atualização (Dia 1-3 após sessão)

**Agentes:** estrategista-movimento

**Inputs:**
- Notas da sessão
- Ações definidas
- Desvios identificados

**Ações:**
1. Documentar decisões e ações no log compartilhado
2. Atualizar Narrative Kit se houve mudanças relevantes
3. Enviar resumo da sessão para todos os participantes e ausentes
4. Se houve correção de guideline: distribuir versão atualizada
5. Agendar próxima sessão

**Outputs:**
- Resumo da sessão distribuído
- Guidelines atualizados (se necessário)
- Ações com responsáveis e prazos
- Próxima sessão agendada

**Decision Gate:**
- Follow-up completo → monitorar até próxima sessão
- Ações pendentes → cobrar antes do próximo sync

### Fase 4: Monitoramento Contínuo (Entre sessões)

**Agentes:** analista-semiotico

**Inputs:**
- Outputs publicados pelos squads ao longo do mês
- Alertas de desvio

**Ações:**
1. Monitorar outputs de squads parceiros semanalmente (amostra)
2. Se desvio detectado: comunicar squad responsável imediatamente (não esperar sessão)
3. Se oportunidade surge: avisar squad relevante para capitalizar
4. Manter canal assíncrono disponível para consultas
5. Acumular notas para a próxima sessão de preparação

**Outputs:**
- Alertas de desvio comunicados (quando aplicável)
- Notas acumuladas para próxima sessão
- Oportunidades sinalizadas

**Decision Gate:**
- Desvio crítico → intervenção imediata
- Desvio menor → documentar para próximo sync
- Consistência mantida → seguir fluxo normal

## Cadência

| Ação | Frequência | Duração |
|------|-----------|---------|
| Preparação | Mensal (3 dias antes) | 2-3h total |
| Sessão de sync | Mensal (data fixa) | 45-60min |
| Follow-up | Mensal (3 dias após) | 1-2h total |
| Monitoramento | Semanal | 30min/semana |

**Dia sugerido:** Primeira semana do mês (após monthly review do Movement Squad)

## Artefatos Produzidos

- Auditoria de consistência mensal
- Resumo de sessão de sync
- Guidelines atualizados (quando necessário)
- Log de decisões e ações
- Narrative Kit atualizado

## Métricas de Sucesso

| Métrica | Meta |
|---------|------|
| Sessões realizadas | 100% dos meses |
| Participação de squads | >= 80% dos squads representados |
| Desvios críticos corrigidos | 100% antes de publicação |
| Consistência narrativa | >= 80% (medido na auditoria) |
| Oportunidades de sinergia ativadas | >= 1 por mês |
| Satisfação dos squads parceiros | >= 7/10 |
| Tempo de resposta a consultas | <= 24h |

## Integração

| Tipo | Referência |
|------|-----------|
| **Tasks** | `tasks/review/narrative-consistency-review.md`, `tasks/operations/cross-squad-sync.md`, `tasks/operations/monthly-movement-review.md` |
| **Frameworks** | `frameworks/narrative-graph-framework.md`, `frameworks/architect-system-map.md`, `frameworks/architect-channel-architecture.md` |
| **Checklists** | `checklists/narrative-coherence-quality.md`, `checklists/architect/architect-system-coherence.md`, `checklists/architect/architect-cross-squad-integration.md` |
| **Registries** | `data/registries/decision-log.yaml` |

### Regras de Fluxo
- **Quality Gate entre fases:** Preparação→Sessão: auditoria completa; Sessão→Follow-up: decisões documentadas; Monitoramento: consistência ≥ 80%
- **Rework:** Se desvio crítico detectado → intervenção imediata com squad responsável
- **Escalation:** Se consistência narrativa < 80% por 2+ meses → escalar para Movement Chief + Chiefs dos squads parceiros
- **Handoff:** Guidelines e Narrative Kit atualizados alimentam → todos os squads parceiros e `workflows/14-cross-squad-narrative-handoff.md`
