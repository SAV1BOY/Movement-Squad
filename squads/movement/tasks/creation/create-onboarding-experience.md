---
id: create-onboarding-experience
name: "Criar Experiência de Onboarding"
squad: movement
type: task
category: creation
agents: [community-builder, manifestador-criativo, designer-identitario]
frameworks: [onboarding-journey-framework, first-impression-model]
checklists: [onboarding-experience-checklist, welcome-flow-checklist]
templates: [onboarding-flow-template, welcome-kit-template]
version: "1.0"
tags: [creation, onboarding, comunidade, experiencia, boas-vindas]
---

# Criar Experiência de Onboarding

## Objetivo

Projetar a experiência completa de onboarding para novos membros do movimento — do primeiro contato até o momento em que se sentem verdadeiramente parte — garantindo que cada novo membro entenda a causa, encontre seu papel e tenha o primeiro momento de pertencimento.

## Contexto

Os primeiros 7 dias de um novo membro determinam se ele fica ou vai embora. Se ninguém o recebe, não entende como participar e não sente que pertence, desaparece. O onboarding é o ritual mais importante do movimento — é a diferença entre "visitei" e "pertenço".

## Inputs Necessários

- Community Structure com camadas e papéis
- Identity System com códigos de entrada
- Manifesto e artefatos de identidade prontos
- Rituais definidos (especialmente o de entrada)
- Member Journey Map
- Channel Architecture (para saber onde receber novos membros)

## Processo

1. **Mapear ponto de entrada** — Identificar de onde novos membros vêm: link de convite, descoberta orgânica, indicação de champion, creator, evento. Cada ponto de entrada pode ter welcome diferente.

2. **Projetar sequência de onboarding** — Criar fluxo dos primeiros 7 dias: Dia 0 (welcome imediato), Dia 1 (primeiros conteúdos), Dia 2-3 (primeira interação com a comunidade), Dia 4-5 (primeiro ritual), Dia 6-7 (primeira contribuição).

3. **Criar welcome message** — Escrever mensagem de boas-vindas que: apresenta o movimento em 3 frases, faz o novo membro se sentir especial, dá o próximo passo claro, usa linguagem do manifesto.

4. **Produzir Welcome Kit** — Montar kit digital para novos membros: (a) Mini-manifesto de boas-vindas, (b) Guia rápido de "como participar", (c) 3-5 artefatos de identidade para download imediato, (d) Links dos espaços de interação, (e) Nome e contato de um "buddy" da comunidade.

5. **Projetar primeiro momento wow** — Criar uma experiência nos primeiros 24h que faça o membro pensar "que incrível, nunca vi isso em outro lugar". Pode ser: mensagem personalizada, presente digital exclusivo, convite para sala VIP temporária, menção pública de boas-vindas.

6. **Definir buddy system** — Parear cada novo membro com um membro experiente que: dá boas-vindas pessoais, responde dúvidas, convida para o primeiro ritual, acompanha por 2 semanas.

7. **Criar conteúdo de formação** — Produzir sequência de 5-7 conteúdos educativos: história do movimento, valores e códigos, como contribuir, quem são os champions, próximos eventos/rituais.

8. **Definir marcos de integração** — Estabelecer checkpoints: (a) Completou perfil/bio, (b) Participou de primeira conversa, (c) Participou de primeiro ritual, (d) Fez primeira contribuição, (e) Convidou primeiro amigo.

9. **Automatizar onde possível** — Configurar automações para: welcome message, entrega de kit, sequência de conteúdos, lembretes de marcos, notificação para buddy. Manter tom humano nas automações.

10. **Medir e iterar** — Definir métricas de onboarding: taxa de conclusão de cada etapa, tempo até primeira interação, retention em 7/14/30 dias, NPS de onboarding. Iterar mensalmente.

## Outputs Esperados

- **Fluxo de onboarding** completo (7 dias)
- **Welcome Kit** digital pronto para distribuição
- **Welcome message** em variações por ponto de entrada
- **Buddy System** estruturado com guidelines
- **Conteúdo de formação** (5-7 peças)
- **Marcos de integração** definidos e trackáveis
- **Automações** configuradas

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Fluxo mapeado | 7 dias completos |
| Welcome Kit | Pronto e acessível |
| Buddy System | Operacional com buddies treinados |
| Conteúdo de formação | >= 5 peças produzidas |
| Automações | Core flow automatizado |
| Teste com novos membros | >= 10 membros passaram pelo fluxo |
| Retention 7 dias | >= 60% |

## Decision Points

- **Retention < 40% em 7 dias** → Redesenhar welcome experience (problema grave)
- **Buddies sobrecarregados** → Recrutar mais ou simplificar papel do buddy
- **Membros pulando etapas** → Avaliar se o fluxo é longo demais ou pouco engajante
- **Feedback positivo consistente** → Documentar e replicar para novos pontos de entrada

## Integração

| Tipo | Referência |
|------|-----------|
| **Frameworks** | `frameworks/identity-belonging-gradient.md`, `frameworks/community-flywheel.md` |
| **Checklists** | `checklists/comunidade/onboarding-and-roles.md`, `checklists/community-activation-quality.md` |
| **Templates** | `templates/outputs/movement-onboarding-kit.md` |
| **Registries** | `data/registries/community-roles.yaml` |
| **Workflows** | `workflows/02-artifact-foundry.md` |

### Regras de Fluxo
- **Rework:** Se quality gate reprovar → revisar com feedback específico do quality gate, iterar o artefato e resubmeter
- **Escalation:** Se bloqueio ou decisão fora de escopo → escalar para Movement Chief
- **Handoff:** Output vai para → tasks de Activation (launch-activation, activate-community)
