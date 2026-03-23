---
id: create-creator-briefs
name: "Criar Briefs para Creators e Influenciadores"
squad: movement
type: task
category: creation
agents: [manifestador, estrategista-de-ciclo]
frameworks: [creator-movement-framework, distribution-trident]
checklists: [creator-influencer-brief-quality, partner-alignment-quality]
templates: [outputs/creator-brief-package]
registry: [data/registries/creator-partners]
version: "1.0"
tags: [creation, briefs, creators, influenciadores, co-criacao]
---

# Criar Briefs para Creators e Influenciadores

## Objetivo

Produzir briefs de alta qualidade para creators e influenciadores que transmitam a essência do movimento sem engessar a criatividade — dando direção clara sobre o "o quê" e o "por quê" enquanto deixam total liberdade sobre o "como".

## Contexto

O pior erro com creators é transformá-los em atores lendo script. O segundo pior é dar zero direção e esperar que adivinhem o que o movimento precisa. O brief ideal inspira o creator a fazer o melhor conteúdo da carreira dele — porque genuinamente se conecta com a causa.

## Inputs Necessários

- Thesis Document e manifesto
- Perfis de creators selecionados (ou a selecionar)
- Platform Briefs com formatos nativos
- Slogans e verdades compartilháveis
- Regras de menção ao produto
- Budget aprovado para creators
- Calendário de ativação

## Processo

1. **Segmentar creators por perfil** — Categorizar: (a) Macro-creators (alcance), (b) Micro-creators (engajamento), (c) Nano-creators/membros (autenticidade), (d) Creators de nicho (expertise). Cada segmento recebe brief com nível de detalhe diferente.

2. **Definir objetivo por creator** — Para cada parceria, especificar: awareness do movimento, credibilidade por associação, conteúdo de profundidade, alcance para novo público, conversão para comunidade.

3. **Redigir contexto do movimento** — Escrever seção do brief que explica: o que é o movimento (não o produto), contra o quê lutamos, pelo que acreditamos, por que isso importa. Linguagem inspiradora, não corporativa.

4. **Definir mensagens-chave** — Listar 3-5 mensagens que gostaríamos que o conteúdo transmita. Formular como verdades, não como talking points de marketing. Ex: "Gostaríamos que o público sentisse que..." não "Gostaríamos que você dissesse que..."

5. **Especificar do's e don'ts** — Listar claramente: o que encorajamos (personalizar, contar história pessoal, ser honesto sobre o que sente), o que evitamos (linguagem corporativa, unboxing genérico, promessa exagerada, copy-paste do slogan).

6. **Incluir referências e inspiração** — Anexar: exemplos de conteúdo que amamos (do próprio creator e de outros), moodboard visual, tom de voz com exemplos, slogans que podem usar livremente.

7. **Definir deliverables e specs** — Especificar: número de peças, formatos, durações, plataformas, timeline, processo de aprovação (mínimo possível — confiar no creator), hashtags e tags obrigatórias.

8. **Criar Creator Kit** — Montar kit complementar ao brief: assets visuais usáveis, filtros/efeitos, produtos para demonstração (se aplicável), links de tracking, contato do squad para dúvidas.

9. **Definir processo de aprovação** — Estabelecer: quantas rodadas de revisão (idealmente 1), critérios de aprovação (alinhamento com valores, não com estética pessoal), SLA de resposta, quem aprova.

10. **Planejar debrief pós-publicação** — Definir: como coletar dados de performance, como dar feedback ao creator, como compartilhar resultados internamente, como decidir sobre continuidade da parceria.

## Outputs Esperados

- **Briefs customizados** por creator ou segmento
- **Creator Kit** com assets e guidelines
- **Processo de aprovação** documentado
- **Template de debrief** pós-publicação
- **Calendário de entregas** por creator

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Contexto do movimento | Claro e inspirador (não corporativo) |
| Mensagens-chave | 3-5 formuladas como verdades |
| Do's e don'ts | Lista completa e específica |
| Referências incluídas | >= 3 exemplos de inspiração |
| Creator Kit | Completo e acessível |
| Processo de aprovação | Definido com SLA |

## Decision Points

- **Creator não se conecta com o movimento** → Não forçar parceria — autenticidade é inegociável
- **Conteúdo desalinhado com valores** → Conversa direta, ajuste ou cancelamento
- **Creator quer mudar briefing significativamente** → Ouvir — muitas vezes o creator entende melhor o público
- **Performance abaixo do esperado** → Avaliar se é problema de brief, fit ou timing

## Integração

| Tipo | Referência |
|------|-----------|
| **Frameworks** | `frameworks/creator-movement-framework.md`, `frameworks/distribution-trident.md` |
| **Checklists** | `checklists/creator-influencer-brief-quality.md`, `checklists/partner-alignment-quality.md` |
| **Templates** | `templates/outputs/creator-brief-package.md` |
| **Registries** | `data/registries/creator-partners.yaml` |
| **Workflows** | `workflows/02-artifact-foundry.md` |

### Regras de Fluxo
- **Rework:** Se quality gate reprovar → revisar com feedback específico do quality gate, iterar o artefato e resubmeter
- **Escalation:** Se bloqueio ou decisão fora de escopo → escalar para Movement Chief
- **Handoff:** Output vai para → tasks de Activation (launch-activation, activate-community)
