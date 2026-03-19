---
id: community-build-and-nurture
name: "Construir Comunidade: Onboarding → Engajamento → Champions"
squad: movement
type: workflow
agents: [movement-architect, manifestador]
cadence: weekly
version: "1.0"
tags: [workflow, comunidade, onboarding, engajamento, champions, nurture]
---

# Construir Comunidade: Onboarding → Engajamento → Champions

## Objetivo

Operar o fluxo contínuo de construção e nutrição da comunidade — desde o primeiro contato de um novo membro até sua evolução para champion — garantindo que cada pessoa encontre seu lugar e progrida naturalmente dentro do movimento.

## Diagrama de Fases

```
[FASE 1]          [FASE 2]          [FASE 3]          [FASE 4]
Onboarding    →   Engajamento   →   Contribuição  →   Champion
(Dia 0-7)         (Dia 8-30)        (Dia 31-60)       (Dia 60+)
   |                 |                  |                  |
   v                 v                  v                  v
Welcome Kit,     Ritual semanal,   Primeiro          Programa,
buddy,           conversa ativa,   conteúdo criado,  liderança,
primeiro wow     participação      mentoria          reconhecimento
                 regular           de novos
```

## Fases Detalhadas

### Fase 1: Onboarding (Dia 0-7)

**Agentes:** movement-architect

**Inputs:**
- Novo membro entra (via invite, orgânico, creator, ad)
- Onboarding Experience configurada
- Welcome Kit pronto
- Buddy disponível

**Ações:**
1. Welcome message automática personalizada por fonte de entrada
2. Entrega do Welcome Kit (manifesto, guia rápido, artefatos, links)
3. Pareamento com buddy do inner circle
4. Buddy faz contato pessoal em até 24h
5. Trigger de "primeiro momento wow" (presente digital, menção, convite VIP)
6. Sequência de 5 conteúdos de formação (1 por dia)
7. Convite para primeiro ritual semanal

**Outputs:**
- Membro recebido e orientado
- Buddy ativo acompanhando
- Marcos de integração trackados (perfil, interação, ritual)

**Decision Gate:**
- Membro completou marcos D7 → avançar para engajamento
- Membro silencioso após D3 → buddy faz re-engagement direto
- Membro saiu → registrar motivo (se possível) e analisar

### Fase 2: Engajamento (Dia 8-30)

**Agentes:** movement-architect, manifestador

**Inputs:**
- Membros que passaram pelo onboarding
- Calendar de rituais e conteúdo
- Provocações e challenges ativos

**Ações:**
1. Incluir em fluxo de rituais semanais (check-in, troca, celebração)
2. Enviar provocações personalizadas (perguntas, enquetes, desafios)
3. Reconhecer publicamente contribuições (mesmo pequenas)
4. Conectar com membros de interesses similares
5. Monitorar nível de engajamento: ativo, periférico, silencioso
6. Para silenciosos: intervenção do buddy ou do community builder
7. Oferecer oportunidades de participação com baixa barreira

**Outputs:**
- Membros participando de rituais regularmente
- Engajamento monitorado por nível
- Intervenções realizadas para re-engagement

**Decision Gate:**
- Membro engaja regularmente → monitorar e nutrir
- Membro periférico → aumentar touchpoints personalizados
- Membro silencioso após 3 tentativas → aceitar e manter no radar passivamente

### Fase 3: Contribuição (Dia 31-60)

**Agentes:** movement-architect

**Inputs:**
- Membros engajados ativamente
- Templates e ferramentas para criação
- Challenges de contribuição

**Ações:**
1. Convidar para primeira contribuição: história pessoal, opinião, conteúdo, review
2. Fornecer templates que facilitem criação
3. Amplificar primeira contribuição: repost, destaque, agradecimento público
4. Convidar para participar de co-criação (ideação, feedback, teste)
5. Propor mentoria de novo membro (buddy reverso)
6. Rastrear qualidade e frequência de contribuições
7. Identificar contribuidores com potencial de champion

**Outputs:**
- Membros criando conteúdo e contribuindo
- UGC gerado pela comunidade
- Potenciais champions identificados

**Decision Gate:**
- Contribuidor ativo e alinhado → considerar para champion
- Contribuidor ativo mas desalinhado → coaching de alinhamento
- Membro que não contribui → manter como participante (sem forçar)

### Fase 4: Champion (Dia 60+)

**Agentes:** movement-architect

**Inputs:**
- Contribuidores identificados como potenciais champions
- Champion Program estruturado
- Toolkit de champion

**Ações:**
1. Convidar formalmente para o Champion Program (conversa 1:1)
2. Treinar: imersão na causa, técnicas de facilitação, toolkit
3. Designar primeira responsabilidade: facilitar ritual, mentorar novos, criar conteúdo
4. Dar acesso VIP: canal exclusivo, early access, co-criação estratégica
5. Reconhecer publicamente: badge, destaque, menção em rituais
6. Acompanhar satisfação e carga (prevenir burnout)
7. Criar path de evolução: champion → senior champion → council

**Outputs:**
- Champions treinados e ativos
- Rituais facilitados por champions
- Novos membros sendo mentorados
- Pipeline de futuros champions

**Decision Gate:**
- Champion prosperando → dar mais autonomia e visibilidade
- Champion sobrecarregado → redistribuir responsabilidades
- Champion desengajando → conversa empática e opção de pausa

## Cadência

| Ação | Frequência |
|------|-----------|
| Onboarding de novos | Contínuo (cada novo membro) |
| Rituais semanais | 2-3x por semana |
| Provocações de engajamento | Diário |
| Identificação de champions | Mensal |
| Training de champions | Trimestral |
| Health check da comunidade | Semanal |

## Artefatos Produzidos

- Member journey trackado por estágio
- Relatório de onboarding completion rate
- UGC catalogado
- Champions roster atualizado
- Community Health snapshot semanal

## Métricas de Sucesso

| Métrica | Meta |
|---------|------|
| Onboarding completion (D7) | >= 60% |
| Retenção D30 | >= 50% |
| Taxa de contribuição | >= 15% dos ativos |
| Novos champions/trimestre | >= 5 |
| Satisfação de champions | >= 8/10 |
| Community NPS | >= 60 |

## Integração

| Tipo | Referência |
|------|-----------|
| **Tasks** | `tasks/activation/activate-community.md`, `tasks/creation/create-onboarding-experience.md`, `tasks/creation/create-champion-program.md`, `tasks/creation/create-community-rituals.md`, `tasks/strategy/design-community-structure.md`, `tasks/measurement/measure-community-health.md` |
| **Frameworks** | `frameworks/community-flywheel.md`, `frameworks/identity-belonging-gradient.md`, `frameworks/ritual-reward-loop.md` |
| **Checklists** | `checklists/community-activation-quality.md`, `checklists/comunidade/onboarding-and-roles.md`, `checklists/comunidade/champion-program-quality.md`, `checklists/comunidade/engagement-rituals.md`, `checklists/comunidade/moderation-and-safety.md`, `checklists/comunidade/community-health-indicators.md` |
| **Registries** | `data/registries/community-roles/`, `data/registries/champion-registry/`, `data/metrics/community-growth-quality.md` |

### Níveis de Quality Gate Aplicáveis
- **Nível 2 (Task Gate):** Checklists de onboarding, engajamento e champion aplicados em cada fase
- **Nível 3 (Domain Gate):** Gate de comunidade valida saúde e qualidade das interações semanalmente
- **Nível 4 (Chief Gate):** Movement Chief aprova promoções a champion e mudanças estruturais

### Regras de Fluxo
- **Quality Gate entre fases:** Onboarding completion ≥ 60% D7; Retenção D30 ≥ 50%; Champions identificados e ativados mensalmente
- **Rework:** Se retenção D30 < 50% → revisar experiência de onboarding e valor percebido
- **Escalation:** Se community health em queda por 3+ semanas → escalar para Movement Architect
- **Handoff:** Community Health Reports alimentam → `workflows/04-measure-and-learn.md` e `workflows/16-quarterly-movement-review.md`
