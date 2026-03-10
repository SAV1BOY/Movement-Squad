---
id: impact-review
name: "Review de Impacto e Decisões"
squad: movement
type: task
category: review
agents: [arquiteto-movimento, estrategista-movimento, analista-impacto]
frameworks: [impact-review-framework, decision-matrix-model]
checklists: [impact-review-checklist]
templates: [impact-review-template, decision-log-template]
version: "1.0"
tags: [review, impacto, decisoes, estrategia, avaliacao]
---

# Review de Impacto e Decisões

## Objetivo

Conduzir sessão estruturada de review que analise o impacto real do movimento no período, compare com as win conditions, identifique o que funcionou e o que não funcionou, e tome decisões estratégicas sobre os próximos passos.

## Contexto

Impact review não é reunião de status. É sessão de julgamento honesto: o movimento está gerando o impacto que prometemos? Os recursos investidos estão justificados? As hipóteses que tínhamos estavam certas? Sem review honesto, o squad opera no escuro — repetindo erros e celebrando métricas de vaidade.

## Inputs Necessários

- Health Score atualizado com tendência
- Business Impact Report do período
- Community Health Report
- Content-to-Conversation Report
- Resultados de experimentos recentes
- Win Conditions com metas vs. realizados
- Feedback qualitativo de stakeholders

## Processo

1. **Preparar pré-read** — 48h antes da sessão, distribuir: dashboard atualizado, reports consolidados, comparação metas vs. realizados. Todos devem chegar lidos e com opinião formada.

2. **Abrir com dados, não opiniões** — Começar a sessão apresentando: Health Score atual vs. anterior, top 3 métricas que subiram, top 3 que caíram, win conditions atingidas vs. não atingidas.

3. **Analisar o que funcionou** — Para cada métrica que subiu ou meta atingida: por que funcionou? O que fizemos diferente? Foi mérito ou sorte? É replicável? Documentar os fatores de sucesso.

4. **Analisar o que não funcionou** — Para cada métrica que caiu ou meta não atingida: por que não funcionou? O que subestimamos? O que faríamos diferente? Não buscar culpados — buscar causas raiz.

5. **Revisar experiments e learnings** — Apresentar readouts de todos os experimentos do ciclo. Quais hipóteses foram confirmadas? Quais refutadas? O que aprendemos que muda nossa forma de operar?

6. **Avaliar saúde da thesis** — A thesis ainda é relevante? Os sinais culturais mudaram? O público ainda se identifica? Há necessidade de ajuste, evolução ou pivot?

7. **Tomar decisões** — Para cada item que exige decisão, usar framework: (a) Qual é o problema/oportunidade? (b) Quais são as opções? (c) Qual recomendamos e por quê? (d) Decisão: aprovar, rejeitar ou investigar mais?

8. **Definir ações para próximo ciclo** — Para cada decisão tomada, especificar: ação concreta, responsável, prazo, como medir sucesso, recursos necessários.

9. **Atualizar registros** — Documentar todas as decisões no Decision Log. Atualizar Win Conditions se recalibradas. Atualizar playbooks com novos aprendizados.

10. **Comunicar stakeholders** — Produzir resumo executivo do review para stakeholders: impacto do período, decisões tomadas, próximos passos, riscos identificados.

## Outputs Esperados

- **Impact Review Report** completo
- **Decision Log** atualizado
- **Ações para próximo ciclo** com responsáveis
- **Win Conditions** recalibradas (se necessário)
- **Resumo executivo** para stakeholders
- **Playbooks atualizados** com learnings

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Dados atualizados | 100% dos reports disponíveis |
| Pré-read enviado | 48h antes da sessão |
| Participação | Todos os leads presentes |
| Decisões documentadas | 100% no Decision Log |
| Ações definidas | Com responsável e prazo |
| Comunicação stakeholders | Em até 48h pós-review |

## Decision Points

- **Impacto acima do esperado** → Solicitar mais recursos e acelerar scaling
- **Impacto abaixo do esperado** → Diagnosticar causa e ajustar antes do próximo ciclo
- **Thesis precisa de ajuste** → Iniciar ciclo de thesis forge com urgência
- **Kill criteria atingido** → Iniciar processo de sunset ou pivot

## Integração

- **Alimenta:** Todas as tasks de estratégia e criação do próximo ciclo
- **Recebe de:** Todas as tasks de measurement
- **Workflow relacionado:** `04-measure-and-learn`, `16-quarterly-movement-review`
- **Cadência:** Mensal (review operacional), trimestral (review estratégico)
- **Handoff:** Decisões e ações vão para todo o squad e stakeholders
