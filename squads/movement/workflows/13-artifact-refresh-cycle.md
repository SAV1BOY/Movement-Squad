---
id: artifact-refresh-cycle
name: "Ciclo de Renovação de Artefatos"
squad: movement
type: workflow
agents: [manifestador, identitario, fenomenologo]
cadence: monthly
version: "1.0"
tags: [workflow, artefatos, renovacao, frescor, ciclo, producao]
---

# Ciclo de Renovação de Artefatos

## Objetivo

Operar o ciclo contínuo de renovação de artefatos do movimento — detectando quais estão envelhecendo, produzindo substitutos frescos e aposentando os datados — mantendo a biblioteca sempre atual e impactante.

## Diagrama de Fases

```
[AUDITORIA]       [PRODUÇÃO]        [QA]              [ROTAÇÃO]
Avaliar       →   Produzir      →   Validar       →   Publicar e
Frescor           Novos             Qualidade         Aposentar
   |                 |                  |                  |
   v                 v                  v                  v
Inventário       20-30 novos       Consistência      Biblioteca
com scores,      assets +          narrativa +       atualizada,
gaps, refresh    refreshes         ressonância       datados
list                                testada           arquivados
```

## Fases Detalhadas

### Fase 1: Auditoria de Frescor (Dia 1-3)

**Agentes:** fenomenologo, manifestador

**Inputs:**
- Inventário de artefatos com datas e performance
- Dados de engajamento por artefato
- Trend Radar com estéticas atuais
- Feedback da comunidade

**Ações:**
1. Revisar performance de todos os artefatos ativos (engajamento, uso, compartilhamento)
2. Classificar por status: evergreen, atual, envelhecendo, datado, aposentar
3. Comparar estética com tendências atuais
4. Identificar gaps: formatos que faltam, temas não cobertos
5. Priorizar refresh list: o que renovar neste ciclo

**Outputs:**
- Inventário atualizado com scores
- Refresh list priorizada
- Gap list

**Decision Gate:**
- Refresh list definida → avançar para produção
- Maioria evergreen → reduzir produção e focar em gaps

### Fase 2: Produção de Novos e Refreshes (Dia 4-14)

**Agentes:** manifestador, identitario

**Inputs:**
- Refresh list e gap list
- Identity System atualizado
- Trend Radar e swipe file
- Frases-semente e verbatims frescos

**Ações:**
1. Produzir refreshes dos artefatos priorizados (manter essência, atualizar forma)
2. Criar novos artefatos para cobrir gaps identificados
3. Produzir variações por plataforma
4. Criar templates remixáveis quando aplicável
5. Adaptar linguagem com verbatims mais recentes

**Outputs:**
- Artefatos refreshed
- Novos artefatos criados
- Variações por plataforma
- Templates remixáveis

**Decision Gate:**
- Produção atende refresh list → avançar para QA
- Produção insuficiente → extender timeline ou reduzir escopo

### Fase 3: QA de Qualidade (Dia 15-17)

**Agentes:** fenomenologo, movement-architect

**Inputs:**
- Artefatos produzidos
- Checklist de consistência

**Ações:**
1. Revisar cada artefato contra Identity System
2. Verificar alinhamento com thesis e tom
3. Testar ressonância rápida com 5-10 membros
4. Aprovar ou solicitar ajustes
5. Garantir formatos técnicos corretos por plataforma

**Outputs:**
- Artefatos aprovados
- Ajustes solicitados (se necessário)

**Decision Gate:**
- QA aprovado → publicar
- QA reprovado → ajustar e revalidar

### Fase 4: Rotação e Publicação (Dia 18-20)

**Agentes:** manifestador

**Inputs:**
- Artefatos aprovados
- Biblioteca existente
- Calendar de publicação

**Ações:**
1. Organizar novos artefatos na biblioteca com tags e metadata
2. Marcar artefatos aposentados e mover para arquivo
3. Comunicar ao squad: o que é novo, o que foi aposentado, o que mudou
4. Agendar publicação conforme calendar
5. Atualizar kits distribuíveis (Creator Kit, Champion Kit, etc.)

**Outputs:**
- Biblioteca atualizada
- Kits atualizados
- Squad comunicado
- Publicações agendadas

**Decision Gate:**
- Biblioteca fresca e organizada → ciclo completo
- Muitos itens datados restantes → planejar ciclo extra

## Cadência

- **Ciclo completo:** 20 dias (mensal)
- **Auditoria:** Primeiros 3 dias
- **Produção:** 10 dias
- **QA:** 3 dias
- **Rotação:** 3 dias

## Artefatos Produzidos

- 20-30 artefatos novos ou refreshed por ciclo
- Biblioteca atualizada e organizada
- Kits renovados
- Inventário com scores de frescor

## Métricas de Sucesso

| Métrica | Meta |
|---------|------|
| Artefatos produzidos/ciclo | >= 20 |
| % da biblioteca "atual" ou "evergreen" | >= 80% |
| Artefatos "datados" restantes | < 10% |
| QA approval rate | >= 85% na primeira rodada |
| Uso de novos artefatos | >= 30% usados em 30 dias |
| Engajamento de artefatos novos vs. antigos | >= 10% superior |

## Integração

| Tipo | Referência |
|------|-----------|
| **Tasks** | `tasks/review/artifact-freshness-review.md`, `tasks/creation/create-memetic-assets.md`, `tasks/creation/create-movement-content.md`, `tasks/operations/curate-swipe-file.md` |
| **Frameworks** | `frameworks/memetic-variation-selection.md`, `frameworks/manifestor-artifact-stack.md`, `frameworks/manifestor-meme-factory.md` |
| **Checklists** | `checklists/manifesto/artifact-shelf-life-check.md`, `checklists/memetics/meme-lifecycle-audit.md`, `checklists/memetic-asset-quality.md`, `checklists/narrative-coherence-quality.md` |
| **Registries** | `data/registries/memetic-assets/`, `data/registries/slogan-bank.yaml` |

### Regras de Fluxo
- **Quality Gate entre fases:** Auditoria→Produção: inventário completo com scores; Produção→QA: artefatos atendem ao brief; QA→Rotação: QA approval rate ≥ 85%
- **Rework:** Se QA reprovado → ajustar com feedback específico e revalidar
- **Escalation:** Se artefato core datado (manifesto, slogan) → prioridade máxima, escalar para Movement Chief
- **Handoff:** Biblioteca atualizada alimenta → `workflows/03-activation-sprint.md` e `workflows/02-artifact-foundry.md`
