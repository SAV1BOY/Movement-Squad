---
id: narrative-consistency-review
name: "Review de Consistência Narrativa"
squad: movement
type: task
category: review
agents: [analista-semiotico, arquiteto-movimento]
frameworks: [narrative-consistency-framework, brand-voice-audit-model]
checklists: [narrative-audit-checklist]
templates: [narrative-review-template, consistency-scorecard-template]
version: "1.0"
tags: [review, narrativa, consistencia, tom, voz, alinhamento]
---

# Review de Consistência Narrativa

## Objetivo

Auditar a consistência da narrativa do movimento em todos os pontos de contato — conteúdos, artefatos, comunicações de creators, PR, comunidade e cross-squad — garantindo que a mensagem central permaneça coerente mesmo quando adaptada para diferentes contextos.

## Contexto

Movimentos morrem de inconsistência. Quando o manifesto diz uma coisa, o content de Instagram diz outra, o creator diz uma terceira e o PR pitch uma quarta, o público sente que algo é falso — mesmo que não saiba explicar o quê. Consistência não é rigidez. É garantir que 100 vozes diferentes contem a mesma história.

## Inputs Necessários

- Thesis Document como referência central
- Manifesto e slogans aprovados
- Amostra de conteúdo publicado no período (todas as plataformas)
- Conteúdo de creators publicado
- Matérias de PR publicadas
- Comunicações de comunidade (posts de champions, respostas)
- Outputs de squads parceiros que mencionam o movimento

## Processo

1. **Selecionar amostra de auditoria** — Coletar amostra representativa: 20-30 peças de conteúdo publicado, 5-10 conteúdos de creators, 3-5 matérias de PR, 10-15 comunicações de comunidade, 5-10 outputs de squads parceiros.

2. **Definir critérios de consistência** — Auditar cada peça contra: (a) Alinhamento com thesis (inimigo/sonho/mecanismo), (b) Tom de voz correto, (c) Linguagem do glossário, (d) Identidade visual correta, (e) Mensagem central preservada, (f) Nenhuma contradição com outras peças.

3. **Pontuar cada peça** — Para cada item da amostra, dar score de consistência (1-5) em cada critério. Registrar observações específicas para pontuações baixas.

4. **Mapear desvios** — Catalogar todos os desvios encontrados: desvios de tom (ex: peça corporativa quando deveria ser rebelde), desvios de mensagem (ex: foco em produto quando deveria ser causa), desvios visuais (ex: fora da paleta identitária).

5. **Classificar severidade** — Para cada desvio: (a) Crítico (contradiz a thesis), (b) Moderado (tom errado mas mensagem correta), (c) Leve (ajuste estético necessário).

6. **Identificar padrões de desvio** — Buscar: desvios concentrados em algum canal? Em algum agente? Em algum tipo de conteúdo? Em algum squad parceiro? Padrões indicam problemas sistêmicos.

7. **Calcular Consistency Score** — Agregar pontuações em score geral de consistência (0-100). Comparar com ciclo anterior. Meta: >= 80.

8. **Recomendar correções** — Para cada desvio crítico e moderado: o que deveria ser, como corrigir, quem precisa ser treinado, qual guideline atualizar.

9. **Atualizar guidelines** — Se padrões de desvio indicam que guidelines estão incompletos ou confusos, atualizar: adicionar exemplos, esclarecer áreas cinzentas, criar do's e don'ts mais específicos.

10. **Apresentar e treinar** — Compartilhar resultados com o squad e squads parceiros. Realizar sessão de alinhamento para corrigir desvios sistêmicos.

## Outputs Esperados

- **Narrative Consistency Scorecard** com pontuação por critério
- **Lista de desvios** catalogados por severidade
- **Padrões de desvio** identificados
- **Recomendações de correção** específicas
- **Guidelines atualizados** (se necessário)
- **Sessão de alinhamento** realizada

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Amostra auditada | >= 50 peças de conteúdo |
| Critérios avaliados | Todos os 6 critérios |
| Consistency Score | >= 80/100 |
| Desvios críticos | 0 (zero tolerância) |
| Correções recomendadas | 100% dos desvios moderados+ |
| Guidelines atualizados | Se necessário, em até 1 semana |

## Decision Points

- **Consistency Score > 90** → Manter práticas atuais e reconhecer o squad
- **Consistency Score 70-90** → Ajustes pontuais e treinamento focado
- **Consistency Score < 70** → Alerta — pausar criação até realinhamento
- **Desvios críticos encontrados** → Corrigir imediatamente e investigar como aconteceu

## Integração

- **Alimenta:** `create-movement-content`, `create-creator-briefs`, cross-squad guidelines
- **Recebe de:** Todos os outputs de criação e ativação
- **Workflow relacionado:** `20-monthly-narrative-sync`, `14-cross-squad-narrative-handoff`
- **Cadência:** Mensal (auditoria), trimestral (revisão profunda)
- **Handoff:** Scorecard e correções vão para todos os criadores e squads parceiros
