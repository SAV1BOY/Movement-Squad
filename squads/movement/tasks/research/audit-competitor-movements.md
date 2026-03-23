---
id: audit-competitor-movements
name: "Auditar Movimentos dos Concorrentes"
squad: movement
type: task
category: research
agents: [fenomenologo, analista-de-impacto]
frameworks: [holt-cultural-strategy, sharp-how-brands-grow]
checklists: [cultural-insight-quality]
templates: [reports/narrative-audit-report]
registry: [data/research/competitor-movements]
version: "1.0"
tags: [research, concorrentes, auditoria, posicionamento, narrativa]
---

# Auditar Movimentos dos Concorrentes

## Objetivo

Analisar sistematicamente como concorrentes diretos e indiretos estão tentando criar movimentos culturais, identificando seus posicionamentos narrativos, pontos fortes, vulnerabilidades e espaços que deixam abertos para o nosso movimento ocupar.

## Contexto

Não operamos no vácuo. Concorrentes também tentam se posicionar culturalmente — alguns com autenticidade, outros de forma oportunista. Entender o cenário competitivo narrativo é tão importante quanto entender o cenário competitivo de produto. O objetivo não é copiar, mas encontrar o espaço vazio onde nosso movimento será único e incontestável.

## Inputs Necessários

- Lista de concorrentes diretos e indiretos (mínimo 8)
- Canais e perfis sociais dos concorrentes
- Campanhas e ações recentes dos concorrentes (últimos 6 meses)
- Dados de share of voice e share of conversation
- Tension Map atual do setor

## Processo

1. **Definir universo de análise** — Listar concorrentes em 3 camadas: (a) diretos (mesmo produto/serviço), (b) indiretos (mesma necessidade, solução diferente), (c) culturais (não competem em produto, mas competem em narrativa e atenção do mesmo público).

2. **Coletar artefatos narrativos** — Para cada concorrente, reunir: manifestos, taglines, campanhas de marca, posts de maior engajamento, parcerias com creators, ações comunitárias, tom de voz, identidade visual de movimento.

3. **Analisar posicionamento narrativo** — Para cada concorrente, responder: Qual é o "inimigo" declarado ou implícito? Qual é o "sonho" prometido? Qual é o "mecanismo" proposto? Em qual tensão cultural se posicionam?

4. **Avaliar autenticidade** — Pontuar de 1-5 a autenticidade percebida de cada movimento concorrente: (a) Consistência no tempo, (b) Coerência entre discurso e prática, (c) Recepção do público (engajamento genuíno vs. artificial), (d) Profundidade da comunidade.

5. **Mapear reações do público** — Analisar comentários e conversas sobre as ações de movimento dos concorrentes. Identificar: o que o público elogia, o que critica, onde vê hipocrisia, o que desejaria que fosse diferente.

6. **Identificar vulnerabilidades** — Para cada concorrente, documentar: promessas não cumpridas, inconsistências narrativas, públicos negligenciados, tensões que ignoram, críticas recorrentes.

7. **Mapear espaços vazios** — Cruzar todos os posicionamentos e identificar: (a) tensões que ninguém aborda, (b) públicos que ninguém representa, (c) tons de voz que ninguém usa, (d) formatos que ninguém explora.

8. **Construir Narrative Position Map** — Criar mapa visual 2x2 ou multi-eixo posicionando todos os concorrentes segundo suas narrativas de movimento. Destacar nosso posicionamento atual e posicionamento-alvo.

9. **Gerar recomendações estratégicas** — Para cada espaço vazio identificado, avaliar: viabilidade, autenticidade para nós, potencial de diferenciação e risco de ser rapidamente copiado.

10. **Compilar Competitor Movement Audit** — Documento final com: mapa de posicionamento, fichas por concorrente, espaços vazios priorizados e recomendações.

## Outputs Esperados

- **Competitor Cards** preenchidos (1 por concorrente analisado)
- **Narrative Position Map** visual
- **Lista de espaços vazios** priorizados
- **Competitor Movement Audit Report** completo
- **Alertas de risco** (concorrentes que podem invadir nosso espaço)

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Concorrentes analisados | >= 8 (incluindo culturais) |
| Artefatos coletados por concorrente | >= 5 |
| Posicionamento narrativo documentado | 100% dos concorrentes |
| Espaços vazios identificados | >= 3 |
| Reações do público analisadas | >= 5 concorrentes |

## Decision Points

- **Espaço vazio com alta autenticidade para nós** → Priorizar como território do movimento
- **Concorrente entrando no nosso espaço** → Avaliar diferenciação ou reposicionamento
- **Concorrente com movimento muito forte** → Evitar confronto direto, buscar flanqueamento
- **Mercado saturado de narrativas similares** → Considerar abordagem contrarian

## Integração

| Tipo | Referência |
|------|-----------|
| **Frameworks** | `frameworks/holt-cultural-strategy.md`, `frameworks/sharp-how-brands-grow.md` |
| **Checklists** | `checklists/cultural-insight-quality.md` |
| **Templates** | `templates/reports/narrative-audit-report.md` |
| **Registries** | `data/research/competitor-movements/` |
| **Workflows** | `workflows/00-signal-radar-daily.md` |

### Regras de Fluxo
- **Rework:** Se quality gate reprovar → retornar à Fase 1 (varredura) com fontes ampliadas e reexecutar captura
- **Escalation:** Se bloqueio ou decisão fora de escopo → escalar para Movement Chief
- **Handoff:** Output vai para → tasks de Strategy (craft-movement-thesis, design-identity-system)
