---
id: monthly-movement-review
name: "Review Mensal do Movimento"
squad: movement
type: task
category: operations
agents: [arquiteto-movimento, estrategista-movimento, analista-impacto, community-builder]
frameworks: [monthly-review-framework, health-assessment-model]
checklists: [monthly-review-checklist]
templates: [monthly-review-template, stakeholder-report-template]
version: "1.0"
tags: [operations, mensal, review, relatorio, stakeholders]
---

# Review Mensal do Movimento

## Objetivo

Conduzir review mensal abrangente que consolide todos os dados, learnings e resultados do mês, produza relatório para stakeholders e defina as prioridades e ajustes para o mês seguinte.

## Contexto

O review mensal é o checkpoint operacional principal. Enquanto o kaizen semanal faz micro-ajustes e o review trimestral faz direcionamento estratégico, o mensal é onde se avalia: estamos no caminho certo? O ritmo está adequado? Os recursos estão bem alocados?

## Inputs Necessários

- Health Score com tendência do mês
- Community Health Report mensal
- Business Impact Report mensal
- Content-to-Conversation Report
- Learning Logs das 4 semanas
- Resultados de experimentos do mês
- Status das ações definidas no mês anterior

## Processo

1. **Consolidar dados do mês** — Reunir todos os reports e métricas. Preparar dashboard comparativo: este mês vs. mês anterior vs. meta.

2. **Apresentar Health Score e tendência** — Começar com o big picture: Health Score atual, evolução mês a mês, dimensões que subiram e caíram.

3. **Revisar Win Conditions** — Para cada win condition: onde estamos vs. onde deveríamos estar? Estamos on track, adiantados ou atrasados?

4. **Analisar top 5 wins do mês** — Selecionar e discutir os 5 maiores sucessos: o que fez funcionar, o que aprendemos, como replicar.

5. **Analisar top 5 desafios do mês** — Selecionar e discutir os 5 maiores desafios: o que não funcionou, por que, o que faremos diferente.

6. **Revisar comunidade** — Apresentar: crescimento, retenção, saúde dos champions, highlights de membros, incidentes.

7. **Revisar impacto em negócio** — Apresentar: métricas de conversão, CAC via movimento, LTV de membros, ROI estimado.

8. **Priorizar próximo mês** — Definir: top 3 prioridades do squad, ações específicas por prioridade, responsáveis, recursos necessários.

9. **Produzir relatório para stakeholders** — Compilar: resumo executivo (1 página), métricas-chave, highlights, desafios, próximos passos, pedidos/necessidades.

10. **Documentar decisões** — Registrar todas as decisões tomadas, razões, responsáveis e prazos no Decision Log.

## Outputs Esperados

- **Monthly Review Report** completo
- **Relatório para stakeholders** (1-2 páginas)
- **Prioridades do próximo mês** definidas
- **Decision Log** atualizado
- **Ações com responsáveis** e prazos

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Dados consolidados | 100% dos reports disponíveis |
| Participação | Todo o squad core |
| Duração | 60-90 minutos máximo |
| Relatório stakeholders | Entregue em até 48h |
| Prioridades definidas | Top 3 com responsáveis |
| Decision Log | Atualizado no mesmo dia |

## Decision Points

- **Mês excelente** → Manter curso e avaliar aceleração
- **Mês medíocre** → Ajustar prioridades e focar no que move o ponteiro
- **Mês ruim** → Diagnóstico profundo e possível revisão de estratégia
- **Stakeholders insatisfeitos** → Alinhar expectativas antes de ajustar execução

## Integração

| Tipo | Referência |
|------|-----------|
| **Frameworks** | `frameworks/movement-health-score-framework.md`, `frameworks/impact-metrics-model.md` |
| **Checklists** | `checklists/impact-dashboard-quality.md` |
| **Templates** | `templates/reports/monthly-movement-report.md` |
| **Registries** | `data/metrics/movement-health-score.md` |
| **Workflows** | `workflows/05-ralphloop-kaizen-weekly.md` |

### Regras de Fluxo
- **Rework:** Se quality gate reprovar → identificar bloqueio, resolver dependência e reexecutar no próximo ciclo
- **Escalation:** Se bloqueio ou decisão fora de escopo → escalar para Movement Architect
- **Handoff:** Output vai para → todas as tasks que dependem dos registros atualizados
