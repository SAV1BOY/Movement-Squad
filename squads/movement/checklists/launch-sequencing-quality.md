---
id: launch-sequencing-quality
name: "Qualidade do Sequenciamento de Lançamento"
squad: movement
type: checklist
category: quality-gate
version: "1.0"
tags: [lançamento, fases, sequência, pré-lançamento, ignição, sustentação]
---

# Qualidade do Sequenciamento de Lançamento

## Objetivo

Garantir que o lançamento do movimento siga uma sequência estratégica de quatro fases —
pré-aquecimento, ignição, sustentação e expansão — com gatilhos de transição claros,
assets prontos para cada fase e métricas que determinam quando avançar, manter ou recuar.
Lançamentos sem sequenciamento queimam munição cedo demais e perdem momento.

## Quando Usar

- Antes de iniciar qualquer atividade de pré-lançamento
- Na transição entre cada fase do lançamento
- Quando métricas indicarem que uma fase não atingiu o threshold esperado
- Em post-mortems de lançamentos concluídos
- Quando um movimento precisar de relançamento após pausa

## Agentes Responsáveis

- **Movement Strategist Agent** — Arquiteto do sequenciamento geral
- **Distribution & Growth Agent** — Executor do plano fase a fase
- **Community Agent** — Ativa a comunidade em cada fase
- **Review & QA Agent** — Executa este checklist como quality gate em cada transição

## Checklist

### 1. Pré-Aquecimento (Pre-Heat)

- [ ] 1.1 A duração do pré-aquecimento está definida (recomendado: 2-4 semanas)
- [ ] 1.2 Os sinais culturais e teasers estão produzidos e agendados
- [ ] 1.3 A lista de early adopters/insiders foi construída (mín. 50 pessoas comprometidas)
- [ ] 1.4 Os insiders receberam acesso antecipado ao manifesto ou material exclusivo
- [ ] 1.5 Existe mecanismo de waitlist ou pré-registro com contagem pública
- [ ] 1.6 A métrica de sucesso do pré-aquecimento está definida (ex.: 200 inscritos, 50 shares)

### 2. Ignição (Launch)

- [ ] 2.1 A data de ignição está fixada e comunicada aos stakeholders e parceiros
- [ ] 2.2 Todos os assets de lançamento estão prontos e aprovados (manifesto, vídeo, posts)
- [ ] 2.3 O "momento de impacto" está planejado (evento, live, drop simultâneo)
- [ ] 2.4 Os creators e parceiros estão alinhados com horários exatos de publicação
- [ ] 2.5 A equipe de moderação está de plantão durante as primeiras 48 horas
- [ ] 2.6 Existe plano B para os 3 riscos mais prováveis (queda de plataforma, crise, baixa adesão)

### 3. Sustentação (Sustain)

- [ ] 3.1 O conteúdo para as 4 semanas pós-ignição está produzido ou em produção avançada
- [ ] 3.2 A cadência de publicação pós-lançamento está definida e é menor que na ignição
- [ ] 3.3 Os rituais comunitários da fase de sustentação estão agendados
- [ ] 3.4 O mecanismo de user-generated content está ativo e incentivado
- [ ] 3.5 As métricas de sustentação estão definidas (retenção, engajamento recorrente)

### 4. Expansão (Scale)

- [ ] 4.1 Os critérios para entrar na fase de expansão estão quantificados (gatilho numérico)
- [ ] 4.2 Novos segmentos de audiência para expansão estão identificados e priorizados
- [ ] 4.3 A adaptação de mensagem para novos segmentos está planejada (sem perder essência)
- [ ] 4.4 O orçamento adicional para expansão está aprovado ou contingenciado
- [ ] 4.5 Os guardrails de expansão estão definidos (quando parar de expandir)

### 5. Gatilhos de Transição

- [ ] 5.1 O threshold numérico para transição de cada fase está documentado
- [ ] 5.2 Existe critério de "abort" para cada fase (quando recuar ou pausar)
- [ ] 5.3 As decisões de transição têm dono definido (quem aprova avançar)

## Critérios de Aprovação

- **Aprovado:** Todos os 25 itens completos com datas e responsáveis atribuídos
- **Aprovado com ressalvas:** Até 3 itens pendentes, nenhum do grupo "Ignição"
- **Reprovado:** 4+ itens pendentes, ou fase de ignição sem assets prontos

## Ação se Falhar

1. Adiar data de ignição até todos os itens críticos estarem resolvidos
2. Se pré-aquecimento falhar em atingir threshold, estender a fase em 1-2 semanas
3. Se ignição falhar, acionar plano B imediatamente (não esperar 48h para reagir)
4. Se sustentação falhar, avaliar se o problema é de conteúdo, distribuição ou produto
5. Documentar aprendizados por fase para calibrar próximos lançamentos

## Cross-references

- `distribution-plan-quality.md` — Distribuição é executada fase a fase
- `community-activation-quality.md` — Comunidade é ativada progressivamente nas fases
- `ritual-design-quality.md` — Rituais são introduzidos na fase de sustentação
- `movement-scaling-quality.md` — Expansão deve seguir guardrails de scaling
- `crisis-and-backlash-quality.md` — Crises são mais prováveis na fase de ignição
- Framework: Launch Sequencing Playbook v1
- Template: Timeline de Lançamento (template-launch-timeline.md)
