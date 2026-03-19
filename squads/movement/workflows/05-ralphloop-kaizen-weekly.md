---
id: ralphloop-kaizen-weekly
name: "RalphLoop: Kaizen Semanal do Squad"
squad: movement
type: workflow
agents: [movement-architect, estrategista-de-ciclo, analista-de-impacto, manifestador]
cadence: weekly
version: "1.0"
tags: [workflow, semanal, kaizen, melhoria-continua, retrospectiva, aprendizado]
---

# RalphLoop: Kaizen Semanal do Squad

## Objetivo

Operar o loop semanal de melhoria contínua do Movement Squad — reunindo signal digest, métricas, learnings e feedback num ciclo de 45 minutos que garante evolução constante e prevenção de problemas.

## Diagrama de Fases

```
[PRÉ-SESSÃO]     [ABERTURA]       [ANÁLISE]         [AÇÃO]           [FECHAMENTO]
Preparação    →   Check-in     →   Wins +        →   Ajustes      →   Energia +
de Insumos        + Sinais         Learnings         Definidos         Próxima Semana
   |                 |                |                  |                  |
   v                 v                v                  v                  v
Digest +          Estado do       O que funciona/    1-3 mudanças      Preview e
métricas          squad +          não funciona       concretas         motivação
prontos           top sinais       + causa raiz       implementáveis
```

## Fases Detalhadas

### Pré-Sessão: Preparação de Insumos (30min antes)

**Agentes:** analista-de-impacto, fenomenologo

**Inputs:**
- Weekly Signal Digest
- Weekly Metrics Brief
- Feedback da comunidade da semana
- Status de ações da semana anterior
- Experiment readouts (se houver)

**Ações:**
1. Fenomenólogo prepara top 3 sinais da semana (do Weekly Signal Digest)
2. Analista prepara Health Score e 3 métricas destaque
3. Verificar status dos ajustes definidos na semana anterior
4. Consolidar tudo em formato visual de 1 slide/página

**Outputs:**
- Slide de abertura com sinais + métricas + status
- Material acessível a todos antes da sessão

**Decision Gate:**
- Material pronto → sessão pode acontecer
- Material incompleto → sessão acontece com o que tem (nunca cancelar)

### Fase 1: Check-in e Sinais (10min)

**Agentes:** todos os presentes

**Inputs:**
- Slide de abertura
- Percepção individual de cada membro

**Ações:**
1. Check-in rápido: cada membro em 1 frase — como se sentiu sobre o trabalho da semana (energia alta/média/baixa)
2. Apresentar Health Score da semana e comparar com anterior
3. Apresentar top 3 sinais culturais capturados
4. Abrir para reações rápidas: algum sinal exige ação imediata?

**Outputs:**
- Estado de energia do squad registrado
- Sinais apresentados e discutidos
- Ações urgentes identificadas (se houver)

**Decision Gate:**
- Sinal urgente → separar 5min para definir ação imediata
- Sem urgências → seguir para análise

### Fase 2: Wins e Learnings (15min)

**Agentes:** todos os presentes

**Inputs:**
- Resultados da semana
- Experiment readouts
- Feedback de comunidade e stakeholders

**Ações:**
1. Cada membro compartilha 1 win da semana (o que funcionou bem)
2. Cada membro compartilha 1 learning (o que não funcionou ou poderia melhorar)
3. Para os 2-3 learnings mais impactantes: investigar causa raiz brevemente
4. Se há readout de experimento: apresentar resultado e implicação
5. Documentar wins e learnings no Learning Log

**Outputs:**
- Wins documentados (para replicar)
- Learnings documentados (para evitar)
- Causa raiz dos top learnings
- Learning Log atualizado

**Decision Gate:**
- Causa raiz identificada → definir ajuste na Fase 3
- Causa raiz complexa → agendar investigação dedicada fora da sessão

### Fase 3: Ajustes Definidos (10min)

**Agentes:** movement-architect + squad

**Inputs:**
- Learnings e causas raiz identificados
- Status dos ajustes da semana anterior

**Ações:**
1. Revisar ajustes da semana anterior: implementados? Funcionaram?
2. Para ajustes não implementados: entender por quê e decidir manter ou abandonar
3. Definir 1-3 ajustes novos para a próxima semana
4. Para cada ajuste: o que muda, quem é responsável, como sabemos que melhorou
5. Garantir que ajustes são pequenos e implementáveis em 1 semana

**Outputs:**
- Status de ajustes anteriores documentado
- 1-3 ajustes novos com responsável e métrica
- Registro no Learning Log

**Decision Gate:**
- Ajustes viáveis e aceitos → comprometer e avançar
- Ajuste requer mudança grande → transformar em task e agendar separadamente

### Fase 4: Fechamento e Próxima Semana (10min)

**Agentes:** movement-architect + squad

**Inputs:**
- Calendar da próxima semana
- Prioridades do mês
- Dependências e riscos

**Ações:**
1. Preview da próxima semana: datas importantes, deadlines, eventos
2. Alinhar prioridades: o que é mais importante para cada membro esta semana
3. Identificar dependências entre membros e resolver antes de sair
4. Reconhecimento: destacar algo/alguém que fez diferença na semana
5. Encerrar com energia positiva conectada à causa do movimento

**Outputs:**
- Preview da semana alinhado
- Prioridades individuais claras
- Dependências resolvidas
- Moral do squad mantida/elevada

**Decision Gate:**
- Squad alinhado e energizado → semana começa bem
- Squad sobrecarregado → repriorizar antes de começar

## Cadência

| Momento | Duração | Quem |
|---------|---------|------|
| Preparação (antes) | 30min | Analista + Fenomenólogo |
| Check-in + Sinais | 10min | Todo o squad |
| Wins + Learnings | 15min | Todo o squad |
| Ajustes | 10min | Todo o squad |
| Fechamento | 10min | Todo o squad |
| **Total sessão** | **45min** | — |

**Dia fixo:** Toda segunda-feira (sugestão: 10h)

## Artefatos Produzidos

- Learning Log semanal atualizado
- Ajustes da semana registrados
- Status de ajustes anteriores
- Preview da semana
- Registro de energia do squad

## Métricas de Sucesso

| Métrica | Meta |
|---------|------|
| Sessões realizadas | 100% das semanas |
| Participação | >= 80% do squad presente |
| Duração | <= 50 minutos |
| Ajustes implementados | >= 70% dos definidos |
| Learning Log atualizado | Mesmo dia da sessão |
| Energia do squad | >= 70% alta/média |

## Integração

| Tipo | Referência |
|------|-----------|
| **Tasks** | `tasks/operations/weekly-kaizen-loop.md`, `tasks/operations/weekly-signal-radar.md`, `tasks/review/impact-review.md` |
| **Frameworks** | `frameworks/ralphloop-kaizen.md`, `frameworks/impact-learning-loop.md` |
| **Checklists** | `checklists/impacto/learning-to-playbook.md` |
| **Registries** | `data/registries/lessons-learned-registry.yaml`, `data/registries/decision-log.yaml` |

### Regras de Fluxo
- **Quality Gate entre fases:** Pré-sessão→Sessão: material pronto (sessão nunca cancela); Fase 2→3: causa raiz identificada; Fase 3→4: ajustes viáveis e aceitos
- **Rework:** Se mesmo problema aparece 3+ semanas → escalar para mudança estrutural
- **Escalation:** Se squad sobrecarregado consistentemente → escalar para Movement Chief para repriorização
- **Handoff:** Ajustes e learnings alimentam → todas as tasks do squad e `workflows/16-quarterly-movement-review.md`
