---
id: design-rituals
name: "Projetar Rituais e Scripts"
squad: movement
type: task
category: creation
agents: [manifestador, movement-architect]
frameworks: [ritual-reward-loop, manifestor-ritual-design]
checklists: [ritual-design-quality, manifesto/artifact-kit-completeness]
templates: [outputs/ritual-playbook]
registry: [data/registries/rituals]
version: "1.0"
tags: [creation, rituais, scripts, comunidade, habitos, pertencimento]
---

# Projetar Rituais e Scripts

## Objetivo

Criar rituais — ações repetíveis que geram pertencimento e identidade — com scripts detalhados que permitam a qualquer membro facilitar ou participar, fortalecendo a cultura do movimento através da prática coletiva.

## Contexto

Rituais são o que transforma grupo em tribo. Não são eventos — são práticas recorrentes que criam memória compartilhada, vocabulário comum e senso de pertencimento. Um movimento sem rituais é um grupo de pessoas que concordam. Um movimento com rituais é uma comunidade que vive junto.

## Inputs Necessários

- Identity System com códigos rituais definidos
- Community Structure com camadas de participação
- Insights de entrevistas sobre hábitos e rotinas do público
- Benchmarks de rituais em comunidades referência
- Platform Briefs (para rituais digitais)
- Thesis Document para alinhamento temático

## Processo

1. **Inventariar rituais espontâneos** — Antes de criar, mapear: o público já tem rituais? Quais práticas repetitivas fazem espontaneamente? O que compartilham com regularidade? Capturar e formalizar rituais que já existem é mais poderoso que inventar do zero.

2. **Definir tipologia de rituais** — Categorizar rituais necessários: (a) Ritual de entrada (onboarding), (b) Ritual diário (micro-ação), (c) Ritual semanal (check-in coletivo), (d) Ritual mensal (celebração/review), (e) Ritual de marco (milestones), (f) Ritual de reconhecimento (destaque de membros).

3. **Projetar cada ritual** — Para cada tipo, definir: nome identitário, propósito, duração, formato (online/offline/híbrido), número de participantes ideal, materiais necessários, nível de facilidade para participar.

4. **Escrever scripts detalhados** — Para cada ritual, criar script passo-a-passo: abertura, desenvolvimento, encerramento. Incluir: falas sugeridas para facilitador, momentos de participação, transições, timing de cada etapa.

5. **Criar elementos sensoriais** — Definir para cada ritual: playlist/som associado, visual padrão, gesto/saudação, frase de abertura e fechamento, artefato compartilhado (template, challenge, badge).

6. **Testar com grupo piloto** — Executar cada ritual com 5-15 pessoas do inner circle. Observar: engajamento, momentos de energia vs. queda, facilidade de entendimento, vontade de repetir.

7. **Iterar com base em feedback** — Ajustar duração, formato, linguagem e elementos sensoriais com base no teste. Rodar pelo menos 2 iterações antes de lançar para a comunidade ampla.

8. **Criar facilitator guide** — Produzir guia para que qualquer champion possa facilitar o ritual: checklist de preparação, script simplificado, troubleshooting, exemplos de adaptação.

9. **Projetar escalabilidade** — Para cada ritual, responder: funciona com 10 pessoas e com 1000? Se não, como adaptar? Criar versões para diferentes tamanhos de grupo.

10. **Definir cadência e calendário** — Montar calendário de rituais: quais acontecem quando, quem facilita, como são comunicados, como são registrados.

## Outputs Esperados

- **Ritual Cards** para cada ritual (mínimo 6 tipos)
- **Scripts detalhados** com passo-a-passo
- **Facilitator Guides** por ritual
- **Elementos sensoriais** definidos e produzidos
- **Calendário de rituais** publicado
- **Resultados do teste piloto** documentados

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Tipos de ritual | >= 6 tipos definidos |
| Scripts completos | 100% dos rituais com script |
| Teste piloto | >= 2 iterações por ritual |
| Facilitator guide | 100% dos rituais públicos |
| Escalabilidade | Testada para 2 faixas de tamanho |
| Satisfação piloto | >= 8/10 vontade de repetir |

## Decision Points

- **Ritual com alta adesão espontânea** → Escalar e incorporar como ritual core
- **Ritual com baixa participação** → Avaliar se é problema de formato, timing ou relevância
- **Comunidade criando rituais próprios** → Incorporar e reconhecer oficialmente
- **Ritual se tornando obrigação** → Simplificar ou tornar mais leve antes que gere fadiga

## Integração

| Tipo | Referência |
|------|-----------|
| **Frameworks** | `frameworks/ritual-reward-loop.md`, `frameworks/manifestor-ritual-design.md` |
| **Checklists** | `checklists/ritual-design-quality.md`, `checklists/manifesto/artifact-kit-completeness.md` |
| **Templates** | `templates/outputs/ritual-playbook.md` |
| **Registries** | `data/registries/rituals/` |
| **Workflows** | `workflows/02-artifact-foundry.md` |

### Regras de Fluxo
- **Rework:** Se quality gate reprovar → revisar com feedback específico do quality gate, iterar o artefato e resubmeter
- **Escalation:** Se bloqueio ou decisão fora de escopo → escalar para Movement Chief
- **Handoff:** Output vai para → tasks de Activation (launch-activation, activate-community)
