---
id: ms-00
name: Avaliação de Saúde Pré-Escala
squad: movement
type: project-phase
category: movement-scaling
phase: 0-assessment
tags:
  - saúde
  - avaliação
  - diagnóstico
  - pré-escala
---

# 00 · Avaliação de Saúde Pré-Escala

## Objetivo da Fase

Antes de investir em escala, garantir que o movimento está saudável o suficiente
para suportar crescimento. Escalar um movimento doente amplifica os problemas.
Esta avaliação funciona como check-up completo: se o diagnóstico revelar fragilidades,
tratar antes de acelerar.

## Inputs

- Health score do ciclo anterior
- Métricas de comunidade atualizadas
- Dados de retenção por coorte
- Análise de sentimento recente
- Feedback qualitativo da comunidade
- Relatório financeiro do ciclo anterior
- Contexto de mercado atualizado

## Processo

1. **Health Score Completo** — Calcular health score atualizado usando
   `movement-health-score-calculator.md`. Comparar com score do ciclo anterior.
   Identificar dimensões que melhoraram e pioraram.

2. **Auditoria de Comunidade** — Executar `community-health-audit.md` completo.
   Avaliar: atividade, diversidade de participação, qualidade das conversas,
   dependência do time central, capacidade de auto-organização.

3. **Análise de Retenção** — Usar `cohort-retention-calculator.md` para mapear
   retenção por coorte. Identificar padrões de churn e momentos críticos
   na jornada do membro.

4. **Análise de Sentimento** — Executar `sentiment-analysis-skeleton.md` para
   captar sentimento atual. Comparar com baseline. Identificar focos de
   insatisfação ou desgaste.

5. **Stress Test de Narrativa** — Usar `narrative-consistency-checker.md`
   para avaliar se a tese central ainda está intacta ou foi diluída pelo
   crescimento. A narrativa sobreviveria 3x mais audiência?

6. **Avaliação de Infraestrutura** — A plataforma, os processos e o time
   aguentam 3x o volume atual? Identificar gargalos de capacidade antes
   que se tornem crises.

7. **Análise Financeira** — Custo por membro ativo, custo de aquisição,
   custo de retenção. O modelo é sustentável em escala?

8. **Diagnóstico Consolidado** — Consolidar todas as avaliações em documento
   com classificação: pronto para escalar / precisa ajustes / não escalar.

## Outputs

- [ ] Health score atualizado com comparativo
- [ ] Relatório de auditoria de comunidade
- [ ] Análise de retenção por coorte
- [ ] Relatório de sentimento com tendências
- [ ] Avaliação de consistência narrativa
- [ ] Mapa de gargalos de infraestrutura
- [ ] Análise financeira de sustentabilidade
- [ ] Diagnóstico consolidado com recomendação

## Quality Gate

| Critério                          | Mínimo Aceitável                         |
|-----------------------------------|------------------------------------------|
| Health score geral                | Acima de 7/10 para prosseguir            |
| Retenção de comunidade            | Acima de 50% por coorte                  |
| Sentimento                        | Predominantemente positivo               |
| Narrativa consistente             | Score de consistência acima de 70%       |
| Infraestrutura                    | Sem gargalos críticos identificados      |
| Sustentabilidade financeira       | Custo projetado dentro do budget         |

## Próxima Fase

→ `01-scaling-strategy.md` — Se o diagnóstico confirmar prontidão, definir
estratégia de escala. Se identificar fragilidades, resolver antes de avançar.

### Red Flags que Impedem Escala

- Retenção abaixo de 40% em qualquer coorte
- Dependência de 1-2 pessoas para toda atividade
- Sentimento negativo crescente sem resolução
- Narrativa diluída ou contraditória
- Custos crescendo mais rápido que resultados
- Comunidade não se auto-organiza para nada

### Diferença entre Crescer e Escalar

- Crescer = mais do mesmo (linear)
- Escalar = mais resultado com menos esforço marginal (exponencial)
- Se crescer exige proporcionalmente mais investimento, não é escala
- Escala real acontece quando a comunidade se torna o motor de crescimento
