---
id: identity-evolution-flow
name: "Evolução de Identidade: Sinal → Proposta → Teste → Atualização"
squad: movement
type: workflow
agents: [identitario, movement-architect, fenomenologo]
cadence: quarterly
version: "1.0"
tags: [workflow, identidade, evolucao, codigos, atualizacao]
---

# Evolução de Identidade: Sinal → Proposta → Teste → Atualização

## Objetivo

Gerenciar a evolução controlada do sistema de identidade do movimento — atualizando códigos visuais, verbais e rituais conforme a cultura evolui — sem perder a essência que os membros reconhecem e valorizam.

## Diagrama de Fases

```
[SINAL]           [PROPOSTA]        [TESTE]           [ATUALIZAÇÃO]
Detectar      →   Projetar      →   Validar       →   Implementar
Necessidade       Evolução          com Comunidade     e Comunicar
   |                 |                  |                  |
   v                 v                  v                  v
Artefatos        Variações          Inner circle       Identity System
envelhecendo,    propostas,         aprova/rejeita,    atualizado,
cultura mudou    mockups            feedback           comunicado
```

## Fases Detalhadas

### Fase 1: Detectar Necessidade de Evolução (Contínuo + Revisão Trimestral)

**Agentes:** fenomenologo, identitario

**Inputs:**
- Artifact Freshness Review
- Trend Radar com tendências estéticas
- Feedback da comunidade sobre identidade
- Dados de uso de artefatos

**Ações:**
1. Revisar resultado do Artifact Freshness Review: quais códigos estão envelhecendo?
2. Analisar tendências estéticas: a linguagem visual do movimento ainda é contemporânea?
3. Coletar feedback: membros ainda se orgulham dos artefatos? Usam espontaneamente?
4. Comparar com concorrentes: nossa identidade ainda é diferenciada?
5. Formular recomendação: evoluir, manter ou overhaul?

**Outputs:**
- Diagnóstico de identidade com recomendação
- Lista de elementos a evoluir
- Justificativa baseada em dados

**Decision Gate:**
- Elementos envelhecendo → iniciar proposta de evolução
- Identidade sólida → manter e monitorar
- Identidade obsoleta → overhaul completo (raro)

### Fase 2: Projetar Evolução (2 semanas)

**Agentes:** identitario, manifestador

**Inputs:**
- Elementos identificados para evolução
- Referências contemporâneas do swipe file
- Identity System atual como base

**Ações:**
1. Criar 2-3 variações evolutivas para cada elemento (não revolução — evolução)
2. Garantir que a essência é preservada (membros antigos reconhecem)
3. Testar compatibilidade: novas variações funcionam com elementos mantidos?
4. Produzir mockups em contexto real (como fica aplicado em conteúdo, comunidade, artefatos)
5. Preparar comparativo: antes vs. depois com justificativa

**Outputs:**
- Variações propostas com mockups
- Comparativo antes/depois
- Justificativa de cada mudança

**Decision Gate:**
- Variações fortes → avançar para teste
- Variações fracas → iterar antes de testar

### Fase 3: Validar com Comunidade (1 semana)

**Agentes:** movement-architect, identitario

**Inputs:**
- Variações propostas
- Inner circle + champions para feedback

**Ações:**
1. Apresentar variações para 15-20 membros do inner circle (sem revelar preferência do squad)
2. Coletar: reação emocional, preferência entre variações, o que perderiam se mudasse, o que ganhariam
3. Apresentar para champions especificamente (eles são guardiões da identidade)
4. Compilar feedback e identificar consenso ou divergências
5. Se aplicável, fazer A/B test público com amostra maior

**Outputs:**
- Feedback compilado
- Variação preferida identificada
- Concerns documentados

**Decision Gate:**
- Comunidade aprova → implementar
- Comunidade dividida → fazer A/B test mais amplo
- Comunidade rejeita → voltar para Fase 2 ou cancelar mudança

### Fase 4: Implementar e Comunicar (2 semanas)

**Agentes:** identitario, movement-architect

**Inputs:**
- Variação aprovada
- Identity System atual para atualização

**Ações:**
1. Produzir todos os assets atualizados com nova identidade
2. Atualizar Identity System Document, kits e templates
3. Atualizar presença em todas as plataformas gradualmente
4. Comunicar mudança à comunidade: o que mudou, por que, como contribuíram
5. Dar período de transição (2-4 semanas com ambos disponíveis)
6. Treinar champions e squads parceiros na nova identidade
7. Aposentar versões anteriores após período de transição

**Outputs:**
- Identity System v2.0 (ou incremento)
- Assets atualizados
- Comunicação publicada
- Squads treinados

**Decision Gate:**
- Transição suave → caso encerrado
- Resistência à mudança → ouvir e ajustar se justificável

## Cadência

- **Detecção:** Contínua + revisão trimestral
- **Ciclo completo de evolução:** 5-6 semanas quando ativado
- **Frequência típica:** 1-2 evoluções por trimestre

## Artefatos Produzidos

- Diagnóstico de identidade
- Variações propostas com mockups
- Identity System atualizado
- Assets renovados
- Comunicação de mudança

## Métricas de Sucesso

| Métrica | Meta |
|---------|------|
| Aprovação da comunidade | >= 70% positivo |
| Adoção pós-mudança | >= 80% usando nova versão em 30 dias |
| Reconhecibilidade mantida | Membros antigos reconhecem |
| Frescor percebido | Score de freshness sobe |
| Tempo de transição | <= 4 semanas |
| Impacto em engajamento | Neutro ou positivo |

## Integração

| Tipo | Referência |
|------|-----------|
| **Tasks** | `tasks/strategy/design-identity-system.md`, `tasks/creation/create-identity-artifacts.md`, `tasks/review/narrative-consistency-review.md` |
| **Frameworks** | `frameworks/identity-collective-narrative.md`, `frameworks/identity-symbol-design.md`, `frameworks/identity-belonging-gradient.md` |
| **Checklists** | `checklists/identity-system-quality.md`, `checklists/identidade/symbol-system.md`, `checklists/identidade/identity-evolution-guardrails.md`, `checklists/identidade/identity-consistency-across-touchpoints.md`, `checklists/identidade/boundary-and-belonging.md` |
| **Registries** | `data/registries/identity-codes.yaml`, `data/registries/decision-log.yaml` |

### Regras de Fluxo
- **Quality Gate entre fases:** Diagnóstico→Proposta: identidade precisa evoluir (confirmado); Proposta→Teste: variações aprovadas internamente; Teste→Rollout: aprovação comunidade ≥ 70%
- **Rework:** Se comunidade rejeita evolução → iterar com feedback antes de forçar mudança
- **Escalation:** Se evolução exige mudança radical → escalar para Movement Chief + stakeholders
- **Handoff:** Identity System atualizado alimenta → `workflows/02-artifact-foundry.md` e `workflows/14-cross-squad-narrative-handoff.md`
