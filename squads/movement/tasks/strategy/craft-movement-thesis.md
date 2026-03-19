---
id: craft-movement-thesis
name: "Gerar Thesis do Movimento"
squad: movement
type: task
category: strategy
agents: [arquiteto-movimento, estrategista-movimento]
frameworks: [enemy-dream-mechanism, thesis-forge-framework]
checklists: [thesis-quality-checklist, thesis-validation-checklist]
templates: [thesis-canvas-template, thesis-document-template]
version: "1.0"
tags: [strategy, thesis, inimigo, sonho, mecanismo, narrativa]
---

# Gerar Thesis do Movimento

## Objetivo

Formular a thesis central do movimento — a tríade Inimigo/Sonho/Mecanismo — que define contra o quê lutamos, pelo que sonhamos e como propomos chegar lá, servindo como norte absoluto para todas as decisões narrativas e criativas do squad.

## Contexto

A thesis é a alma do movimento. Não é um slogan nem um posicionamento de marca — é uma convicção profunda que articula uma tensão real e propõe uma visão de mundo alternativa. Marcas têm posicionamento. Movimentos têm thesis. A diferença é que a thesis convida as pessoas a lutar junto, não apenas a consumir.

## Inputs Necessários

- Signal Reports consolidados
- Tension Map atualizado com tensões priorizadas
- Mapa de linguagem do público
- Audit de movimentos concorrentes com espaços vazios
- Insights de entrevistas com membros da comunidade
- Trend Radar atualizado
- Propósito e valores da marca/empresa

## Processo

1. **Revisar insumos de pesquisa** — Consumir todos os inputs disponíveis. Marcar os 10 insights mais provocadores. Buscar o fio condutor que conecta tensões, linguagem e desejos do público.

2. **Definir o Inimigo** — O inimigo não é um concorrente. É uma crença, um sistema, uma prática ou uma mentalidade que impede o público de viver como deveria. Formular em 1-2 frases: "O mundo acredita que... / O sistema insiste em... / A norma dominante é..."

3. **Definir o Sonho** — O sonho é o mundo que existiria se o inimigo fosse derrotado. Não é utopia genérica — é específico, tangível e emocionalmente carregado. Formular: "Nós acreditamos que é possível... / O mundo que queremos é um onde..."

4. **Definir o Mecanismo** — O mecanismo é como o movimento propõe derrotar o inimigo e alcançar o sonho. Deve ser acionável e inclusivo — algo que qualquer membro pode fazer. Formular: "E fazemos isso através de... / Nosso caminho é..."

5. **Testar coerência interna** — Verificar: O inimigo é real e sentido pelo público? O sonho é desejado pelo público? O mecanismo conecta inimigo ao sonho? A marca/empresa tem legitimidade para propor isso?

6. **Testar potência narrativa** — A thesis gera conflito (alguém discordaria)? Ela é simples o suficiente para explicar em 30 segundos? Ela é profunda o suficiente para sustentar anos de conteúdo?

7. **Validar com linguagem do público** — Reescrever a thesis usando exclusivamente palavras e expressões do glossário de linguagem real. Se não funcionar na língua do público, retrabalhar até funcionar.

8. **Criar variações de articulação** — Produzir 5-7 formas de expressar a thesis: versão de elevador (15 seg), versão tweet (280 char), versão parágrafo (3-4 frases), versão manifesto (1 página), versão visual (1 imagem).

9. **Stress test com contra-narrativas** — Pegar as top contra-narrativas mapeadas e testar: a thesis resiste? A thesis incorpora? A thesis precisa ser ajustada?

10. **Formalizar documento de thesis** — Produzir documento oficial com: thesis completa (inimigo/sonho/mecanismo), variações de articulação, evidências que sustentam, guardrails de uso, critérios para revisão.

## Outputs Esperados

- **Thesis Document** formal com tríade Inimigo/Sonho/Mecanismo
- **Variações de articulação** (5-7 formatos)
- **Teste de coerência** documentado
- **Stress test** contra contra-narrativas
- **Guardrails de uso** para o squad

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Inimigo definido | Claro, específico, sentido pelo público |
| Sonho definido | Tangível, emocionalmente carregado |
| Mecanismo definido | Acionável, inclusivo, conectado |
| Teste de coerência | Todas as 4 perguntas = Sim |
| Validação com linguagem real | Aprovada |
| Variações produzidas | >= 5 formatos |
| Stress test | >= 3 contra-narrativas testadas |

## Decision Points

- **Thesis forte e coerente** → Avançar para criação de manifesto e identity system
- **Thesis com lacuna no mecanismo** → Iterar especificamente no mecanismo antes de avançar
- **Thesis não ressoa na linguagem do público** → Voltar para pesquisa de linguagem
- **Conflito com posicionamento da marca** → Sessão de alinhamento com stakeholders antes de seguir
- **Thesis precisa de pivot** → Documentar razões, arquivar versão anterior, iniciar novo ciclo

## Integração

| Tipo | Referência |
|------|-----------|
| **Frameworks** | `frameworks/enemy-dream-mechanism.md`, `frameworks/identity-collective-narrative.md`, `frameworks/identity-enemy-construction.md`, `frameworks/movement-engine-5-loop.md` |
| **Checklists** | `checklists/movement-thesis-quality.md`, `checklists/identidade/we-us-now-identity.md`, `checklists/architect/architect-movement-engine-audit.md` |
| **Templates** | `templates/outputs/movement-thesis.md`, `templates/outputs/identity-charter.md` |
| **Registries** | `data/registries/movement-theses.yaml`, `data/registries/identity-codes.yaml` |
| **Workflows** | `workflows/01-thesis-forge.md` |

### Regras de Fluxo
- **Rework:** Se quality gate reprovar → retornar ao passo que falhou, incorporar feedback e resubmeter para aprovação do Movement Chief
- **Escalation:** Se bloqueio ou decisão fora de escopo → escalar para Movement Chief
- **Handoff:** Output vai para → tasks de Creation (write-manifesto, create-memetic-assets)
