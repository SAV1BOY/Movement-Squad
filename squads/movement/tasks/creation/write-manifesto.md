---
id: write-manifesto
name: "Escrever Manifesto + Slogans + Kit"
squad: movement
type: task
category: creation
agents: [manifestador, identitario, movement-chief]
frameworks: [manifestor-manifesto-architecture, manifestor-artifact-stack, memetic-variation-selection]
checklists: [manifesto-quality, manifesto/manifesto-structure, memetic-asset-quality]
templates: [outputs/manifesto, outputs/slogan-bank, outputs/artifact-kit]
registry: [data/registries/manifesto-library, data/registries/memetic-assets, data/registries/slogan-bank]
version: "1.0"
tags: [creation, manifesto, slogans, kit, narrativa, escrita]
---

# Escrever Manifesto + Slogans + Kit

## Objetivo

Criar o manifesto fundacional do movimento — o texto que articula a visão, a raiva, o sonho e o chamado à ação — acompanhado de slogans derivados e um kit de comunicação que permita a qualquer membro expressar e espalhar a mensagem.

## Contexto

O manifesto é o documento sagrado do movimento. Não é copy de marketing — é uma declaração de guerra contra o status quo e uma carta de amor para o futuro que queremos. Deve ser capaz de fazer alguém sentir um nó na garganta, raiva produtiva ou esperança concreta. Se não provoca emoção visceral, é apenas mais um texto.

## Inputs Necessários

- Thesis Document (inimigo/sonho/mecanismo) aprovado
- Glossário de linguagem real do público
- Frases-semente coletadas nas entrevistas e pesquisas
- Identity System com tom de voz
- Tension Map com tensão central escolhida
- Referências de manifestos que admira

## Processo

1. **Imergir na matéria-prima** — Reler todos os verbatims do público, frases-semente, insights de entrevistas. Anotar as expressões que mais arrepiam. Não começar a escrever até sentir a emoção do público no corpo.

2. **Definir estrutura do manifesto** — Escolher arco narrativo: (a) Denúncia → Visão → Chamado, (b) Antes → Agora → Depois, (c) Eles dizem → Nós sabemos → Por isso, (d) Pergunta → Verdade → Ação. Testar qual combina mais com o tom do público.

3. **Escrever primeiro draft em fluxo** — Escrever sem editar. Deixar a emoção conduzir. Usar linguagem do público, não linguagem de copywriter. Mirar em 300-800 palavras. Se ficou "bonito demais", provavelmente está falso.

4. **Refinar com critérios** — Revisar perguntando: (a) Alguém discordaria? (se não, é genérico demais), (b) Provoca emoção em 10 segundos? (c) Usa palavras do público? (d) O público postaria isso sem vergonha? (e) Funciona sem logo da marca?

5. **Criar versões de extensão** — Produzir: versão completa (300-800 palavras), versão meia-página (150 palavras), versão tweet (280 caracteres), versão 1 frase (headline), versão visual (para poster/grafismo).

6. **Derivar slogans** — Extrair do manifesto 10-15 slogans candidatos. Testar cada um com: memorabilidade, compartilhabilidade, ambiguidade zero, potência emocional, adaptabilidade a formatos.

7. **Selecionar slogans finais** — Escolher: 1 slogan primário (tagline do movimento), 3-5 slogans secundários (para variação e contextos), 2-3 rally cries (para ativação e comunidade).

8. **Montar Kit de Comunicação** — Criar kit com: manifesto em todos os formatos, slogans com guidelines de uso, templates editáveis (social, email, apresentação), assets visuais do manifesto.

9. **Testar com inner circle** — Compartilhar manifesto e slogans com 10-20 membros do inner circle. Coletar: reações emocionais, verbatims sobre o que sentiram, sugestões de linguagem, nível de identificação (1-10).

10. **Finalizar e publicar** — Incorporar feedback, fazer revisão final de tom e linguagem, aprovar com Arquiteto de Movimento e publicar internamente antes do lançamento externo.

## Outputs Esperados

- **Manifesto** em 5 versões de extensão
- **Slogans** primário (1) + secundários (3-5) + rally cries (2-3)
- **Kit de Comunicação** completo e distribuível
- **Teste com inner circle** documentado com feedback
- **Guidelines de uso** para manifesto e slogans

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Emoção provocada | Inner circle avalia >= 8/10 em média |
| Linguagem do público | >= 80% do texto usa palavras do glossário |
| Polarização | Pelo menos 1 pessoa discorda/se incomoda |
| Memorabilidade do slogan | Inner circle lembra após 24h sem reler |
| Versões produzidas | Todas as 5 extensões |
| Kit completo | Todos os assets incluídos |

## Decision Points

- **Manifesto não provoca emoção** → Reescrever do zero, não iterar — provavelmente é problema estrutural
- **Público acha linguagem artificial** → Voltar para glossário e reescrever com verbatims puros
- **Slogan primário não memoriza** → Testar mais 5 opções antes de fixar
- **Stakeholders pedem suavizar** → Defender polarização com dados de ressonância; suavizar mata o manifesto

## Integração

| Tipo | Referência |
|------|-----------|
| **Frameworks** | `frameworks/manifestor-manifesto-architecture.md`, `frameworks/manifestor-artifact-stack.md`, `frameworks/memetic-variation-selection.md` |
| **Checklists** | `checklists/manifesto-quality.md`, `checklists/manifesto/manifesto-structure.md`, `checklists/memetic-asset-quality.md` |
| **Templates** | `templates/outputs/manifesto.md`, `templates/outputs/slogan-bank.md`, `templates/outputs/artifact-kit.md` |
| **Registries** | `data/registries/manifesto-library/`, `data/registries/memetic-assets/`, `data/registries/slogan-bank.yaml` |
| **Workflows** | `workflows/02-artifact-foundry.md` |

### Regras de Fluxo
- **Rework:** Se quality gate reprovar → revisar com feedback específico do quality gate, iterar o artefato e resubmeter
- **Escalation:** Se bloqueio ou decisão fora de escopo → escalar para Movement Chief
- **Handoff:** Output vai para → tasks de Activation (launch-activation, activate-community)
