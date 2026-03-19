---
id: checklist-task-matrix
name: "Matriz Reversa: Checklist → Tasks"
type: operational-doc
squad: movement
version: "1.0"
tags: [checklist, reverse-index, routing, quality-gates]
---

# Matriz Reversa: Checklist → Tasks

## Resumo

- **Total de checklists únicos referenciados:** 58
- **Total de tasks no routing:** 52
- **Domínios de checklist:** 8 (fenomenologia, identidade, ciclo, manifestacao, impacto, comunidade, distribuicao, operacional)

---

## 1. Domínio: Fenomenologia

### `fenomenologia/phenomenology-signal-capture`
- detect-cultural-signals
- interview-community-members
- weekly-signal-radar

### `fenomenologia/signal-source-diversity`
- detect-cultural-signals
- track-cultural-trends
- research-platform-dynamics

### `fenomenologia/language-and-phrasing-truth`
- map-audience-language
- interview-community-members

### `fenomenologia/tension-mapping`
- map-cultural-tensions

### `fenomenologia/counter-signal-capture`
- map-cultural-tensions
- map-counter-narratives

---

## 2. Domínio: Identidade

### `identidade/we-us-now-identity`
- craft-movement-thesis

### `identidade/symbol-system`
- design-identity-system

### `identidade/boundary-and-belonging`
- design-identity-system

### `identidade/identity-toxic-exclusion-check`
- design-identity-system

---

## 3. Domínio: Ciclo

### `ciclo/trend-vs-fad-filter`
- detect-cultural-signals
- track-cultural-trends

### `ciclo/cycle-timing-window`
- plan-launch-sequence

---

## 4. Domínio: Manifestacao (Manifesto + Memetics + PR)

### `manifesto/manifesto-structure`
- write-manifesto

### `manifesto/artifact-kit-completeness`
- design-rituals

### `manifesto/artifact-shelf-life-check`
- artifact-freshness-review

### `memetics/memetic-fidelity`
- create-memetic-assets

### `memetics/meme-variation-and-selection`
- create-memetic-assets

### `memetics/format-platform-fit`
- create-memetic-assets

### `memetics/meme-lifecycle-audit`
- artifact-freshness-review

### `pr/narrative-pitch-quality`
- create-pr-angles
- activate-pr

### `pr/spokesperson-readiness`
- create-pr-angles
- activate-pr

### `pr/backlash-mitigation`
- activate-pr
- crisis-readiness-review

---

## 5. Domínio: Impacto

### `impacto/experiment-readout`
- run-experiments

### `impacto/vanity-metric-filter`
- measure-movement-health
- measure-community-health
- analyze-cohort-retention
- analyze-content-to-conversation

### `impacto/causal-attribution-sanity`
- measure-business-impact

### `impacto/cohort-and-retention`
- analyze-cohort-retention

### `impacto/learning-to-playbook`
- impact-review
- weekly-kaizen-loop

---

## 6. Domínio: Comunidade

### `comunidade/onboarding-and-roles`
- design-community-structure
- create-onboarding-experience
- activate-community
- onboard-new-member

### `comunidade/champion-program-quality`
- design-community-structure
- create-champion-program

### `comunidade/moderation-and-safety`
- activate-community

### `comunidade/engagement-rituals`
- create-community-rituals

### `comunidade/community-health-indicators`
- measure-community-health
- community-health-review

### `comunidade/community-to-movement-bridge`
- community-health-review

### `comunidade/community-crisis-protocol`
_(Referenciado em workflow 06-crisis-and-backlash, não diretamente em routing)_

---

## 7. Domínio: Distribuicao

### `distribuicao/channel-mix-quality`
- plan-launch-sequence
- design-channel-architecture
- activate-partnerships

### `distribuicao/paid-amplification-guardrails`
- activate-creators
- activate-paid-amplification

### `distribuicao/attribution-sanity-check`
- activate-paid-amplification

---

## 8. Domínio: Operacional (Governance, Architect, Chief + Top-Level)

### `governance/decision-log-standard`
- update-registries

### `governance/ethics-and-boundaries`
_(Referenciado em quality_gates per_domain, não diretamente em routing)_

### `governance/claim-proof-standard`
_(Referenciado em quality_gates per_domain, não diretamente em routing)_

### `architect/architect-movement-engine-audit`
- craft-movement-thesis

### `architect/architect-channel-role-clarity`
- design-channel-architecture

### `architect/architect-scalability-audit`
- plan-movement-scaling

### `architect/architect-cross-squad-integration`
- cross-squad-sync

### `architect/architect-system-coherence`
- narrative-consistency-review

### `chief/chief-win-condition`
- define-win-conditions

### `chief/chief-alignment-with-business`
- define-win-conditions
- plan-movement-to-product-coupling
- measure-business-impact

### `chief/chief-kill-criteria`
- quarterly-movement-review

---

## 9. Checklists Top-Level (sem prefixo de domínio)

### `cultural-insight-quality`
- detect-cultural-signals
- map-audience-language
- audit-competitor-movements

### `movement-thesis-quality`
- craft-movement-thesis

### `identity-system-quality`
- design-identity-system
- create-identity-artifacts

### `impact-dashboard-quality`
- define-win-conditions
- launch-activation
- monthly-movement-review

### `launch-sequencing-quality`
- plan-launch-sequence
- launch-activation

### `movement-scaling-quality`
- plan-movement-scaling

### `community-activation-quality`
- design-community-structure
- create-onboarding-experience
- create-champion-program
- launch-activation
- activate-community
- activate-employee-advocacy

### `manifesto-quality`
- write-manifesto

### `memetic-asset-quality`
- write-manifesto
- create-memetic-assets
- create-movement-content
- curate-swipe-file

### `ritual-design-quality`
- design-rituals
- create-community-rituals

### `symbol-system-quality`
- create-identity-artifacts

### `narrative-coherence-quality`
- create-movement-content
- narrative-consistency-review

### `distribution-plan-quality`
- launch-activation

### `experimentation-quality`
- run-experiments

### `creator-influencer-brief-quality`
- create-creator-briefs
- activate-creators

### `partner-alignment-quality`
- create-creator-briefs
- activate-partnerships

### `crisis-and-backlash-quality`
- crisis-readiness-review

### `movement-to-product-fit-quality`
- plan-movement-to-product-coupling

---

## Referências

- `config.yaml` seção `routing` — Mapeamento completo task → checklists
- `config.yaml` seção `quality_gates` — Gates obrigatórios e por domínio
- `checklists/` — Diretório com todos os checklists operacionais
