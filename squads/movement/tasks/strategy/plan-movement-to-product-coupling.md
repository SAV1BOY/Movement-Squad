---
id: plan-movement-to-product-coupling
name: "Planejar Acoplamento Movimento-Produto"
squad: movement
type: task
category: strategy
agents: [arquiteto-movimento, estrategista-movimento, analista-impacto]
frameworks: [movement-product-coupling-framework, conversion-funnel-model]
checklists: [coupling-integrity-checklist]
templates: [coupling-map-template, conversion-pathway-template]
version: "1.0"
tags: [strategy, produto, conversao, acoplamento, negocio]
---

# Planejar Acoplamento Movimento-Produto

## Objetivo

Projetar a conexão orgânica entre o movimento cultural e o produto/serviço da empresa — como o engajamento com o movimento conduz naturalmente à consideração e adoção do produto sem que a transição pareça forçada ou oportunista.

## Contexto

O maior risco de um movimento de marca é a desconexão: o movimento é incrível, mas ninguém compra o produto. Ou pior: o movimento é incrível, mas quando tentam vender, a comunidade se sente traída. O acoplamento movimento-produto deve ser tão natural que o produto pareça consequência lógica do movimento, não o motivo oculto.

## Inputs Necessários

- Thesis Document do movimento
- Dados de produto (features, benefícios, diferenciais)
- Jornada de compra atual do cliente
- Win Conditions com métricas de negócio
- Feedback da comunidade sobre percepção do produto
- Dados de conversão e retention atuais

## Processo

1. **Mapear conexão thesis-produto** — Responder: como o produto é uma manifestação concreta do sonho do movimento? Como usar o produto é um ato de adesão ao movimento? Se não há resposta natural, há um problema de coupling.

2. **Identificar momentos de transição** — Na jornada do membro, mapear: em quais momentos a menção ao produto é natural? Quando o membro sente vontade espontânea de experimentar? Quais experiências do movimento criam necessidade do produto?

3. **Projetar conversion pathways** — Criar 3-5 caminhos de conversão orgânicos: (a) Membro descobre funcionalidade via ritual, (b) Champion recomenda como ferramenta da causa, (c) Conteúdo educativo resolve problema que produto endereça, (d) Experiência comunitária demonstra valor.

4. **Definir regras de menção** — Estabelecer guidelines claros: quando mencionar o produto (e como), quando nunca mencionar, como responder perguntas sobre produto, como champions podem recomendar autenticamente.

5. **Criar conteúdo-ponte** — Planejar conteúdo que faz a transição natural de "valor do movimento" para "valor do produto": tutoriais, case studies da comunidade, comparações honestas, demos contextualizados.

6. **Projetar benefícios exclusivos** — Definir benefícios de produto exclusivos para membros do movimento: early access, descontos de comunidade, features beta, personalização identitária.

7. **Medir atribuição** — Definir como rastrear: qual porcentagem de clientes veio do movimento, qual é o LTV de clientes vindos do movimento vs. outros canais, qual é o CAC do movimento.

8. **Testar sensibilidade** — Rodar testes de sensibilidade: testar diferentes níveis de menção a produto em diferentes contextos e medir: engajamento pós-menção, sentiment shift, churn de comunidade.

9. **Criar feedback loop** — Estabelecer canal para a comunidade influenciar o produto: sugestões de features, co-criação, beta testing. O produto deve evoluir com o movimento, não independente dele.

10. **Documentar coupling map** — Compilar tudo em documento com: pontos de conexão, conversion pathways, regras de menção, métricas de atribuição, feedback loop.

## Outputs Esperados

- **Coupling Map** visual movimento-produto
- **Conversion Pathways** documentados (3-5 caminhos)
- **Regras de menção** para todo o squad
- **Plano de benefícios exclusivos** para membros
- **Modelo de atribuição** configurado
- **Feedback loop** estruturado

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Conexão thesis-produto | Clara e documentada |
| Conversion pathways | >= 3 caminhos projetados |
| Regras de menção | Definidas e distribuídas |
| Atribuição | Modelo configurado e funcionando |
| Teste de sensibilidade | >= 1 teste executado |
| Feedback loop | Canal ativo e monitorado |

## Decision Points

- **Coupling natural e forte** → Integrar produto como parte dos rituais do movimento
- **Coupling forçado** → Refinar thesis ou reposicionar produto antes de insistir
- **Comunidade rejeita menção a produto** → Reduzir frequência e focar em valor puro por mais tempo
- **Conversão alta mas retention baixa** → Produto não está entregando a promessa do movimento

## Integração

| Tipo | Referência |
|------|-----------|
| **Frameworks** | `frameworks/movement-to-product-coupling.md`, `frameworks/product-led-movement-framework.md` |
| **Checklists** | `checklists/movement-to-product-fit-quality.md`, `checklists/chief/chief-alignment-with-business.md` |
| **Templates** | — |
| **Registries** | `data/registries/decision-log.yaml` |
| **Workflows** | `workflows/01-thesis-forge.md` |

### Regras de Fluxo
- **Rework:** Se quality gate reprovar → retornar ao passo que falhou, incorporar feedback e resubmeter para aprovação do Movement Chief
- **Escalation:** Se bloqueio ou decisão fora de escopo → escalar para Movement Architect
- **Handoff:** Output vai para → tasks de Creation (write-manifesto, create-memetic-assets)
