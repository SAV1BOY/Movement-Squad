---
id: design-identity-system
name: "Projetar Sistema de Identidade Coletiva"
squad: movement
type: task
category: strategy
agents: [identitario, movement-architect, manifestador]
frameworks: [identity-collective-narrative, identity-symbol-design, identity-belonging-gradient]
checklists: [identity-system-quality, identidade/symbol-system, identidade/boundary-and-belonging, identidade/identity-toxic-exclusion-check]
templates: [outputs/identity-charter]
registry: [data/registries/identity-codes]
version: "1.0"
tags: [strategy, identidade, codigos, pertencimento, tribo]
---

# Projetar Sistema de Identidade Coletiva

## Objetivo

Criar o sistema completo de identidade coletiva do movimento — os códigos visuais, verbais, comportamentais e rituais que permitem aos membros se reconhecerem mutuamente, sentirem pertencimento e sinalizarem adesão ao grupo.

## Contexto

Pessoas não aderem a movimentos por argumentos lógicos. Aderem porque querem pertencer. O sistema de identidade é o que transforma "pessoas que concordam com uma ideia" em "tribo que se reconhece". Sem códigos de identidade, não há comunidade — há apenas audiência.

## Inputs Necessários

- Thesis Document aprovado
- Mapa de linguagem do público
- Tension Map e espaços narrativos vazios
- Referências visuais e estéticas do universo do público
- Audit de identidades de movimentos concorrentes
- Entrevistas com membros da comunidade

## Processo

1. **Definir arquétipos do movimento** — Identificar os 2-3 arquétipos culturais centrais que o movimento encarna. Não arquétipos de marca genéricos — arquétipos de movimento: o Rebelde, o Visionário, o Guardião, o Criador, o Curador, etc.

2. **Criar vocabulário identitário** — Definir: como os membros se chamam, como chamam outsiders, como nomeiam as práticas do grupo, quais palavras são "sagradas" e quais são "proibidas".

3. **Projetar códigos visuais** — Desenvolver: símbolo/logo do movimento, paleta de cores identitárias, tipografia distintiva, elementos gráficos recorrentes, estilo fotográfico, gestos visuais reconhecíveis.

4. **Projetar códigos verbais** — Criar: saudações do grupo, frases de rally, hashtags identitárias, formato de bio padrão, maneiras de se apresentar, humor interno.

5. **Projetar códigos comportamentais** — Definir: como membros agem em público (online e offline), quais práticas demonstram adesão, quais hábitos o movimento promove, como membros ajudam outros membros.

6. **Projetar códigos rituais** — Estabelecer: rituais de entrada (onboarding), rituais regulares (weekly/monthly), rituais de celebração (marcos), rituais de reconhecimento (champions), rituais de passagem (níveis).

7. **Testar reconhecibilidade** — Criar cenário: "Se um membro vê outro na rua, como reconhece?" Se não há resposta clara, os códigos ainda não são fortes o suficiente.

8. **Validar acessibilidade** — Garantir que os códigos de identidade são: fáceis de adotar (baixa barreira de entrada), gratuitos ou acessíveis, não excludentes de forma problemática, adaptáveis a contextos diversos.

9. **Criar Identity Kit** — Produzir kit distribuível com: assets visuais, templates, guia de uso, exemplos, do's e don'ts. Formatos: digital (Figma/Canva), imprimível, editável.

10. **Definir governança da identidade** — Estabelecer: quem pode evoluir os códigos, processo para propor mudanças, critérios para aprovar adaptações, limites de customização por membros.

## Outputs Esperados

- **Identity System Document** completo
- **Cultural Code Cards** (visual, verbal, comportamental, ritual)
- **Identity Kit** distribuível para membros
- **Governança da identidade** documentada
- **Guia de uso** com exemplos e anti-exemplos

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Códigos visuais | >= 5 elementos definidos |
| Códigos verbais | >= 5 elementos definidos |
| Códigos comportamentais | >= 3 práticas definidas |
| Códigos rituais | >= 4 rituais definidos |
| Teste de reconhecibilidade | Aprovado |
| Acessibilidade validada | Todos os códigos acessíveis |
| Identity Kit produzido | Completo e distribuível |

## Decision Points

- **Identidade forte mas elitista** → Simplificar códigos de entrada mantendo profundidade para membros avançados
- **Identidade fraca / genérica** → Intensificar diferenciação com códigos mais distintivos
- **Conflito com identidade da marca corporativa** → Sessão de harmonização com Brand Squad
- **Comunidade pedindo adaptações** → Avaliar via processo de governança

## Integração

| Tipo | Referência |
|------|-----------|
| **Frameworks** | `frameworks/identity-collective-narrative.md`, `frameworks/identity-symbol-design.md`, `frameworks/identity-belonging-gradient.md` |
| **Checklists** | `checklists/identity-system-quality.md`, `checklists/identidade/symbol-system.md`, `checklists/identidade/boundary-and-belonging.md`, `checklists/identidade/identity-toxic-exclusion-check.md` |
| **Templates** | `templates/outputs/identity-charter.md` |
| **Registries** | `data/registries/identity-codes.yaml` |
| **Workflows** | `workflows/01-thesis-forge.md` |

### Regras de Fluxo
- **Rework:** Se quality gate reprovar → retornar ao passo que falhou, incorporar feedback e resubmeter para aprovação do Movement Chief
- **Escalation:** Se bloqueio ou decisão fora de escopo → escalar para Movement Chief
- **Handoff:** Output vai para → tasks de Creation (write-manifesto, create-memetic-assets)
