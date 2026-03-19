---
id: create-pr-angles
name: "Criar Ângulos de PR e Narrativas"
squad: movement
type: task
category: creation
agents: [manifestador, movement-chief]
frameworks: [narrative-graph-framework]
checklists: [pr/narrative-pitch-quality, pr/spokesperson-readiness]
templates: [outputs/pr-pitch]
registry: []
version: "1.0"
tags: [creation, pr, imprensa, narrativa, angulos, earned-media]
---

# Criar Ângulos de PR e Narrativas

## Objetivo

Desenvolver ângulos jornalísticos e narrativas de PR que traduzam a mensagem do movimento em histórias que a imprensa, podcasts e veículos de referência queiram contar — não porque a marca pediu, mas porque a história é genuinamente relevante.

## Contexto

PR de movimento não é press release sobre lançamento de produto. É oferecer ao jornalista uma história cultural que vale a pena contar — onde o movimento é protagonista de uma mudança real. Os melhores ângulos de PR fazem o jornalista pensar: "Isso é uma tendência que preciso cobrir" e não "Isso é publicidade que preciso recusar."

## Inputs Necessários

- Thesis Document e manifesto
- Tension Map com tensões de interesse público
- Dados e pesquisas que sustentam a narrativa
- Lista de porta-vozes e suas credenciais
- Mapa de veículos e jornalistas target
- Counter-Narrative Playbook (para antecipar perguntas difíceis)

## Processo

1. **Identificar ângulos noticiáveis** — Mapear 8-12 ângulos potenciais: (a) Tendência cultural que o movimento representa, (b) Dados exclusivos/surpreendentes, (c) Histórias de membros da comunidade, (d) Contra-narrativa ao mainstream, (e) Momento cultural oportuno, (f) Milestone do movimento.

2. **Testar newsworthiness** — Para cada ângulo, avaliar: (a) É novo? (b) É surpreendente? (c) Afeta muita gente? (d) Tem conflito/tensão? (e) Tem dados que sustentam? (f) Tem personagem humano? Se menos de 3 critérios = Sim, descartar o ângulo.

3. **Desenvolver narrativa por ângulo** — Para cada ângulo viável, escrever: headline sugerida, lead paragraph, dados de suporte, citações de porta-vozes, história humana associada, contexto cultural mais amplo.

4. **Identificar porta-vozes por ângulo** — Definir quem fala sobre o quê: fundador/líder para visão, membro da comunidade para história humana, especialista para credibilidade, champion para autenticidade.

5. **Preparar porta-vozes** — Para cada porta-voz designado, criar: key messages (3-5 por ângulo), bridging phrases para perguntas difíceis, soundbites memoráveis, limites do que pode/não pode dizer.

6. **Mapear veículos por ângulo** — Cruzar ângulos com veículos: qual ângulo funciona para qual tipo de veículo (mainstream, nicho, podcast, newsletter, TV, impresso, digital).

7. **Criar pitches customizados** — Para os top 5 ângulos x veículos, escrever pitch personalizado: subject line que abre email, primeiro parágrafo que prende, oferta clara (entrevista, dados, acesso exclusivo).

8. **Produzir press kit** — Montar kit: fact sheet do movimento, bios de porta-vozes, fotos em alta resolução, dados-chave, citações aprovadas, FAQ, contato de assessoria.

9. **Planejar timeline de PR** — Sequenciar: quais ângulos lançar quando, embargos se aplicável, exclusividades para veículos-chave, sustentação pós-publicação.

10. **Preparar para reativas** — Criar FAQ com respostas para: perguntas sobre a marca por trás do movimento, sobre comercialização, sobre autenticidade, sobre contra-narrativas conhecidas.

## Outputs Esperados

- **Ângulos de PR** desenvolvidos (8-12 candidatos, 5+ aprovados)
- **Pitches customizados** por veículo (top 5)
- **Press Kit** completo
- **Porta-vozes preparados** com key messages
- **Timeline de PR** planejada
- **FAQ reativa** pronta

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Ângulos desenvolvidos | >= 8 candidatos |
| Newsworthiness test | >= 5 ângulos aprovados |
| Pitches escritos | >= 5 customizados |
| Press kit | Completo e atualizado |
| Porta-vozes preparados | >= 2 por ângulo principal |
| FAQ reativa | >= 10 perguntas cobertas |

## Decision Points

- **Ângulo gera interesse de veículo tier-1** → Priorizar exclusividade e preparar porta-voz
- **Nenhum ângulo passa no teste** → Voltar à thesis e tensões para encontrar hooks mais fortes
- **Jornalista faz pergunta inesperada** → Acionar protocolo de reativa e atualizar FAQ
- **Cobertura negativa** → Ativar Counter-Narrative Playbook e workflow de crise

## Integração

| Tipo | Referência |
|------|-----------|
| **Frameworks** | `frameworks/narrative-graph-framework.md` |
| **Checklists** | `checklists/pr/narrative-pitch-quality.md`, `checklists/pr/spokesperson-readiness.md` |
| **Templates** | `templates/outputs/pr-pitch.md` |
| **Registries** | — |
| **Workflows** | `workflows/02-artifact-foundry.md` |

### Regras de Fluxo
- **Rework:** Se quality gate reprovar → revisar com feedback específico do quality gate, iterar o artefato e resubmeter
- **Escalation:** Se bloqueio ou decisão fora de escopo → escalar para Movement Chief
- **Handoff:** Output vai para → tasks de Activation (launch-activation, activate-community)
