---
id: design-community-structure
name: "Estruturar Comunidade"
squad: movement
type: task
category: strategy
agents: [arquiteto-movimento, community-builder, estrategista-movimento]
frameworks: [community-layers-framework, member-journey-model]
checklists: [community-structure-checklist]
templates: [community-blueprint-template, role-definition-template]
version: "1.0"
tags: [strategy, comunidade, estrutura, papeis, jornada]
---

# Estruturar Comunidade

## Objetivo

Projetar a estrutura completa da comunidade do movimento — camadas de participação, papéis, sistemas de progressão, espaços de interação e mecanismos de governança — para que membros encontrem seu lugar e evoluam dentro do movimento.

## Contexto

Comunidades sem estrutura viram bagunça. Comunidades com estrutura rígida demais viram burocracia. O desafio é criar uma estrutura orgânica que guie sem sufocar — onde cada pessoa saiba como participar, como crescer e como contribuir.

## Inputs Necessários

- Identity System com códigos rituais
- Personas e segmentos do público
- Win Conditions relacionadas à comunidade
- Benchmarks de comunidades referência
- Entrevistas com membros sobre expectativas

## Processo

1. **Definir camadas de participação** — Criar modelo de camadas concêntricas: (a) Observadores (consomem mas não interagem), (b) Participantes (engajam regularmente), (c) Contribuidores (criam conteúdo/valor), (d) Champions (lideram iniciativas), (e) Council (governança).

2. **Definir papéis por camada** — Para cada camada, especificar: o que podem fazer, o que se espera deles, quais benefícios recebem, como ascendem à próxima camada.

3. **Projetar sistema de progressão** — Criar critérios objetivos para transição entre camadas: ações necessárias, tempo mínimo, reconhecimento de pares, convite de champions. Evitar gamificação superficial.

4. **Mapear espaços de interação** — Definir quais espaços existem para cada tipo de interação: (a) Espaço público (discovery), (b) Espaço de conversa (engagement), (c) Espaço de criação (contribution), (d) Espaço VIP (champions), (e) Espaço de decisão (council).

5. **Criar sistema de reconhecimento** — Definir como membros são reconhecidos: badges, destaque público, acesso exclusivo, participação em decisões, mentorship, merchandise exclusivo.

6. **Projetar governança participativa** — Estabelecer: como decisões são tomadas, quem tem voz, como propor mudanças, como resolver conflitos, como lidar com membros tóxicos.

7. **Definir normas comunitárias** — Criar código de conduta que reflita os valores do movimento: o que celebramos, o que não toleramos, como nos tratamos, como tratamos outsiders.

8. **Planejar operações comunitárias** — Definir: quem modera, em que horários, com quais ferramentas, com qual autonomia, com qual cadência de report.

9. **Criar member journey map** — Mapear a experiência ideal de um membro desde dia 1 até se tornar champion: touchpoints, marcos, momentos de aha, pontos de atrito, intervenções proativas.

10. **Documentar blueprint** — Compilar tudo em Community Blueprint distribuível para toda a equipe de operação comunitária.

## Outputs Esperados

- **Community Blueprint** completo
- **Modelo de camadas** com papéis e progressão
- **Member Journey Map** detalhado
- **Código de conduta** do movimento
- **Sistema de reconhecimento** definido
- **Modelo de governança** documentado

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Camadas definidas | >= 4 camadas com papéis claros |
| Progressão | Critérios objetivos para cada transição |
| Espaços de interação | >= 3 espaços diferenciados |
| Governança | Modelo documentado e aprovado |
| Código de conduta | Completo e revisado |
| Member journey | Mapeado do dia 1 ao champion |

## Decision Points

- **Comunidade crescendo sem estrutura** → Priorizar implementação antes de crescer mais
- **Membros estagnados em uma camada** → Revisar critérios de progressão e engajamento
- **Conflitos frequentes** → Reforçar governança e moderação
- **Champions desengajando** → Revisar sistema de reconhecimento e benefícios

## Integração

| Tipo | Referência |
|------|-----------|
| **Frameworks** | `frameworks/community-flywheel.md`, `frameworks/identity-belonging-gradient.md` |
| **Checklists** | `checklists/community-activation-quality.md`, `checklists/comunidade/onboarding-and-roles.md`, `checklists/comunidade/champion-program-quality.md` |
| **Templates** | `templates/outputs/community-playbook.md`, `templates/outputs/champion-program-blueprint.md` |
| **Registries** | `data/registries/community-roles.yaml` |
| **Workflows** | `workflows/01-thesis-forge.md` |

### Regras de Fluxo
- **Rework:** Se quality gate reprovar → retornar ao passo que falhou, incorporar feedback e resubmeter para aprovação do Movement Chief
- **Escalation:** Se bloqueio ou decisão fora de escopo → escalar para Movement Chief
- **Handoff:** Output vai para → tasks de Creation (write-manifesto, create-memetic-assets)
