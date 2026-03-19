---
id: onboard-new-member
name: "Onboarding de Novo Membro do Squad"
squad: movement
type: task
category: operations
agents: [movement-chief]
frameworks: [identity-belonging-gradient]
checklists: [comunidade/onboarding-and-roles]
templates: [outputs/movement-onboarding-kit]
registry: [data/registries/community-roles]
version: "1.0"
tags: [operations, onboarding, squad, novo-membro, integracao]
---

# Onboarding de Novo Membro do Squad

## Objetivo

Integrar um novo membro ao Movement Squad de forma estruturada — transmitindo contexto, cultura, processos e ferramentas — para que esteja produtivo e alinhado em até 2 semanas, sem perder a essência e sem depender exclusivamente de um mentor.

## Contexto

Novo membro sem onboarding adequado leva meses para se alinhar e produz trabalho inconsistente enquanto isso. Novo membro com onboarding excelente se sente parte do squad em 1 semana e contribui com qualidade em 2. O investimento em onboarding interno se paga em semanas de produtividade não perdida.

## Inputs Necessários

- Perfil e papel do novo membro
- Documentos-base do squad (thesis, guidelines, playbooks)
- Acesso a ferramentas e plataformas
- Calendar do squad e rituais
- Projeto/task designado para primeira contribuição
- Buddy designado dentro do squad

## Processo

1. **Preparar antes da chegada** — Antes do dia 1: configurar acessos a ferramentas, adicionar em canais de comunicação, criar pasta com documentos essenciais, designar buddy, agendar sessões de imersão.

2. **Dia 1: Welcome e Contexto** — Sessão de 2h com Arquiteto de Movimento: história do movimento, thesis atual, por que existimos, quem é nosso público, como o squad funciona, cultura do time. Fazer sentir, não apenas explicar.

3. **Dia 1: Tour de documentação** — Apresentar: onde encontrar cada documento, como navegar o swipe file, como acessar dashboards, onde está o glossário, onde registrar aprendizados.

4. **Dia 2: Deep dive no papel** — Sessão focada no papel específico do novo membro: o que se espera, como medir sucesso, quais tasks são responsabilidade dele, com quem colabora, qual autonomia tem.

5. **Dia 2-3: Imersão no público** — Consumir: 50 verbatims do público, 10 entrevistas (resumos), glossário de linguagem, empathy maps. O novo membro precisa sentir o público na pele antes de produzir qualquer coisa.

6. **Dia 3-4: Shadowing** — Acompanhar buddy em 2-3 atividades reais: participar de ritual comunitário, acompanhar produção de conteúdo, assistir revisão de artefato. Aprender observando.

7. **Dia 5: Primeira contribuição** — Designar task pequena e completa para o novo membro executar sozinho (com buddy disponível para dúvidas). Pode ser: produzir 3 signal cards, escrever 1 meme, facilitar 1 check-in.

8. **Semana 2: Progressão** — Ampliar escopo gradualmente: participar das rotinas do squad (kaizen, rituais), assumir tasks regulares, receber feedback do buddy e do lead.

9. **Dia 14: Check-in de integração** — Sessão de 30min com Arquiteto: como está se sentindo? O que ficou claro? O que ainda confunde? Precisa de algo? Está pronto para voar solo?

10. **Documentar feedback** — Registrar: o que funcionou no onboarding deste membro, o que faltou, sugestões de melhoria. Usar para iterar o processo para o próximo novo membro.

## Outputs Esperados

- **Novo membro integrado** e produtivo em 2 semanas
- **Acessos configurados** a todas as ferramentas
- **Sessões de imersão** realizadas
- **Primeira contribuição** entregue e revisada
- **Check-in de integração** documentado
- **Feedback de onboarding** registrado

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Acessos configurados | Dia 1 (100%) |
| Sessão de contexto | Realizada no dia 1 |
| Imersão no público | >= 50 verbatims consumidos |
| Primeira contribuição | Entregue na semana 1 |
| Check-in dia 14 | Realizado |
| Feedback documentado | Registrado em até 3 dias |

## Decision Points

- **Novo membro se integra rápido** → Acelerar progressão e dar mais autonomia
- **Novo membro confuso após semana 1** → Intensificar suporte do buddy e simplificar primeiras tasks
- **Desalinhamento cultural** → Conversa honesta sobre fit antes que se agrave
- **Feedback revela gap no onboarding** → Corrigir processo para próximos membros

## Integração

| Tipo | Referência |
|------|-----------|
| **Frameworks** | `frameworks/identity-belonging-gradient.md` |
| **Checklists** | `checklists/comunidade/onboarding-and-roles.md` |
| **Templates** | `templates/outputs/movement-onboarding-kit.md` |
| **Registries** | `data/registries/community-roles.yaml` |
| **Workflows** | `workflows/05-ralphloop-kaizen-weekly.md` |

### Regras de Fluxo
- **Rework:** Se quality gate reprovar → identificar bloqueio, resolver dependência e reexecutar no próximo ciclo
- **Escalation:** Se bloqueio ou decisão fora de escopo → escalar para Movement Architect
- **Handoff:** Output vai para → todas as tasks que dependem dos registros atualizados
