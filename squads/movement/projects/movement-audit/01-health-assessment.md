---
id: ma-01
name: Avaliação de Saúde
squad: movement
type: project-phase
category: movement-audit
phase: 1-health
tags:
  - saúde
  - métricas
  - health-score
  - quantitativo
---

# 01 · Avaliação de Saúde

## Objetivo da Fase

Avaliar a saúde geral do movimento usando métricas quantitativas objetivas.
O health score funciona como exame de sangue: revela o estado real, independente
de como o paciente se sente. Números não mentem, mas precisam de interpretação.

## Inputs

- Documento de escopo da auditoria (fase 00)
- Acesso a analytics de todas as plataformas
- Dados de comunidade (membros, atividade, retenção)
- Histórico de métricas para comparação temporal
- Benchmarks de movimentos similares (se disponíveis)
- Scripts de cálculo preparados

## Processo

1. **Coleta de Métricas Brutas** — Extrair dados de todas as plataformas
   e fontes. Para cada métrica, coletar: valor atual, valor histórico
   (30, 60, 90 dias), tendência. Organizar em planilha centralizada.

2. **Cálculo do Health Score** — Usar `movement-health-score-calculator.md`
   para calcular score em 6 dimensões:
   - Alcance: crescimento, impressões, share of voice
   - Engajamento: taxa, profundidade, frequência
   - Comunidade: tamanho ativo, retenção, participação
   - Sentimento: positivo/negativo/neutro, tendência
   - Viralidade: orgânico vs. pago, compartilhamentos, UGC
   - Impacto: ações geradas, conversões, behavior change

3. **Análise de Retenção** — Executar `cohort-retention-calculator.md`
   para cada coorte significativa. Identificar padrões de retenção e
   momentos de churn. Visualizar em gráfico de cohort.

4. **Análise de Concentração** — Quanto da atividade é concentrada em
   poucos membros? Calcular distribuição: top 1%, top 10%, top 20%.
   Alta concentração = risco de dependência.

5. **Benchmark Comparativo** — Se disponível, comparar métricas com
   benchmarks do setor ou movimentos similares. Se não disponível,
   usar evolução temporal como benchmark próprio.

6. **Análise de Eficiência** — Calcular métricas de eficiência:
   custo por membro ativo, custo por peça de conteúdo, custo por
   conversão, horas investidas vs. resultado gerado.

7. **Identificação de Tendências** — Para cada métrica, classificar
   tendência: melhora acelerada, melhora lenta, estável, piora lenta,
   piora acelerada. Tendência importa mais que valor absoluto.

8. **Relatório de Saúde** — Consolidar em relatório visual: health score
   geral e por dimensão, top 5 pontos fortes, top 5 pontos de atenção,
   tendências-chave, comparativo temporal.

## Outputs

- [ ] Planilha de métricas brutas consolidadas
- [ ] Health score calculado (geral + por dimensão)
- [ ] Análise de retenção por coorte com gráficos
- [ ] Análise de concentração de atividade
- [ ] Benchmark comparativo (externo ou temporal)
- [ ] Métricas de eficiência calculadas
- [ ] Mapa de tendências por métrica
- [ ] Relatório de saúde visual

## Quality Gate

| Critério                          | Mínimo Aceitável                         |
|-----------------------------------|------------------------------------------|
| Métricas coletadas                | Todas as fontes do escopo incluídas      |
| Health score completo             | 6 dimensões calculadas                   |
| Cohort analysis                   | Mínimo 3 coortes analisadas              |
| Tendências mapeadas               | Para todas as métricas-chave             |
| Comparativo                       | Temporal ou benchmark externo            |
| Relatório visual                  | Compreensível por não-especialistas      |

## Próxima Fase

→ `02-narrative-audit.md` — Com saúde quantitativa avaliada, auditar
a qualidade e consistência da narrativa do movimento.

### Interpretação do Health Score

- **9-10:** Excepcional. Raro. Cuidado com complacência.
- **7-8:** Saudável. Bom momento para escalar.
- **5-6:** Atenção. Funciona mas tem fragilidades.
- **3-4:** Alerta. Precisa de intervenção.
- **1-2:** Crítico. Avaliar viabilidade de continuação.

### Métricas que Enganam

- Total de seguidores (inclui inativos e bots)
- Impressões totais (sem contexto de engajamento)
- Número de eventos realizados (sem participação)
- Volume de conteúdo produzido (sem impacto)
- Crescimento bruto (sem considerar churn)

### Métricas que Revelam

- Ratio DAU/MAU (frequência real de uso)
- Retenção dia 30 por coorte (real stickiness)
- % de membros que criam conteúdo (creator ratio)
- Crescimento orgânico vs. pago
- Tempo médio de permanência em rituais/eventos
