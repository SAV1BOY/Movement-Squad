---
id: activate-community
name: "Ativar Comunidade"
squad: movement
type: task
category: activation
agents: [community-builder, ativador-chefe]
frameworks: [community-activation-framework, engagement-loop-model]
checklists: [community-activation-checklist]
templates: [community-activation-plan-template, engagement-calendar-template]
version: "1.0"
tags: [activation, comunidade, engajamento, membros, participacao]
---

# Ativar Comunidade

## Objetivo

Executar as ações de ativação da comunidade do movimento — desde a abertura de espaços até a dinamização contínua de conversas, rituais e participação — garantindo que membros não apenas entrem, mas se tornem participantes ativos e contribuidores.

## Contexto

Abrir uma comunidade não é ativá-la. Ativação comunitária é o trabalho diário de acender conversas, provocar participação, reconhecer contribuições e manter a energia viva. Os primeiros 90 dias são críticos — se a comunidade não ganha vida própria nesse período, provavelmente não ganhará nunca.

## Inputs Necessários

- Community Structure e Blueprint
- Onboarding Experience desenhada
- Rituais comunitários prontos
- Champion Program ativo
- Conteúdo de movimento produzido
- Channel Architecture configurada

## Processo

1. **Abrir espaços comunitários** — Configurar e lançar os espaços definidos na arquitetura: grupo principal, sub-espaços temáticos, canal de boas-vindas, espaço VIP de champions. Garantir que estejam acolhedores antes de convidar pessoas.

2. **Semear primeiras conversas** — Antes de abrir ao público amplo, popular com conversas reais: inner circle discutindo, perguntas provocativas, primeiros conteúdos. Ninguém quer entrar em sala vazia.

3. **Executar primeira onda de convites** — Convidar inner circle (50-100 pessoas). Ativar onboarding experience para cada novo membro. Acompanhar de perto as primeiras interações.

4. **Dinamizar diariamente** — Nos primeiros 30 dias, o community builder inicia pelo menos 1 conversa/dia: pergunta provocativa, compartilhamento de insight, pedido de opinião, spotlight de membro, link de referência relevante.

5. **Ativar rituais semanais** — Iniciar os rituais definidos: check-in de segunda, troca de quarta, celebração de sexta. Garantir facilitadores preparados e comunicação antecipada.

6. **Provocar contribuições dos membros** — Lançar: challenges semanais, pedidos de co-criação, enquetes de decisão, templates para membros compartilharem suas histórias, convites para propor temas.

7. **Reconhecer e amplificar** — Diariamente: destacar contribuições de membros, repostar conteúdo criado por eles, agradecer publicamente, mencionar no ritual semanal. Reconhecimento é o combustível da comunidade.

8. **Monitorar saúde em tempo real** — Acompanhar diariamente: número de mensagens, membros ativos, ratio de lurkers vs. participantes, sentimento das conversas, pontos de atrito, membros em risco de abandono.

9. **Intervir em pontos de atrito** — Quando detectar: conflito entre membros (mediar), silêncio prolongado (re-energizar), membro tóxico (abordar privadamente), confusão sobre regras (esclarecer publicamente).

10. **Reportar e iterar** — Semanalmente: compilar métricas, highlights, problemas e aprendizados. Mensalmente: relatório completo com evolução e recomendações.

## Outputs Esperados

- **Espaços comunitários** abertos e ativos
- **Onboarding** rodando para novos membros
- **Rituais** semanais em execução
- **Métricas diárias** de saúde comunitária
- **Report semanal** de ativação
- **Report mensal** de evolução

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Espaços abertos | 100% dos planejados |
| Membros onboarded | >= 50 no primeiro mês |
| Rituais ativos | >= 2 semanais rodando |
| Taxa de participação | >= 20% dos membros ativos/semana |
| Contribuições de membros | >= 10/semana orgânicas |
| Report semanal | 100% entregues |

## Decision Points

- **Comunidade vibrante e autossustentável** → Reduzir intervenção do squad e empoderar champions
- **Comunidade silenciosa** → Intensificar dinamização e reavaliar formato dos espaços
- **Crescimento muito rápido** → Ativar mais champions e reforçar onboarding
- **Conflitos recorrentes** → Reforçar código de conduta e moderação

## Integração

- **Alimenta:** `measure-community-health`, `create-champion-program`
- **Recebe de:** `design-community-structure`, `create-onboarding-experience`, `create-community-rituals`, `launch-activation`
- **Workflow relacionado:** `08-community-build-and-nurture`, `03-activation-sprint`
- **Cadência:** Diária (dinamização), semanal (report e ajustes), mensal (revisão)
- **Handoff:** Reports vão para Arquiteto de Movimento e analista de métricas
