---
id: mp-04
name: Medição Pós-Pivot
squad: movement
type: project-phase
category: movement-pivot
phase: 4-measure
tags:
  - medição
  - pivot
  - resultados
  - validação
---

# 04 · Medição Pós-Pivot

## Objetivo da Fase

Medir os resultados da nova tese e comparar com o desempenho anterior para
validar se o pivot funcionou. Esta é a fase da verdade: os dados mostram se
a decisão foi acertada. Medição honesta evita que continuemos investindo
em algo que não funciona.

## Inputs

- Métricas do movimento antes do pivot (baseline)
- Métricas coletadas durante e após a execução do pivot (fase 03)
- Win conditions revisadas para a nova tese
- Health score pré-pivot para comparação
- Feedback qualitativo da comunidade pós-transição
- Timeline de estabilização e marcos

## Processo

1. **Definição do Período de Avaliação** — Pivot precisa de tempo para
   mostrar resultados. Definir período mínimo de avaliação: tipicamente
   30-60 dias após estabilização. Não julgar pivot por resultados da
   primeira semana.

2. **Comparação Antes vs. Depois** — Para cada métrica-chave, comparar
   performance pré-pivot vs. pós-pivot:
   - Alcance e crescimento
   - Engajamento (profundidade, não superfície)
   - Retenção de comunidade por coorte
   - Sentimento geral e tendência
   - Conteúdo orgânico gerado
   - Aquisição de novos membros

3. **Health Score Pós-Pivot** — Calcular health score completo usando
   `movement-health-score-calculator.md`. Comparar com score pré-pivot
   e com score durante a crise que motivou o pivot.

4. **Análise de Nova Audiência** — Quem está sendo atraído pela nova
   tese? É a audiência que planejamos? Mapear perfil dos novos membros
   e comparar com persona desejada.

5. **Análise de Retenção Pós-Pivot** — Usar `cohort-retention-calculator.md`
   para separar coortes: membros antigos que ficaram, membros antigos
   que saíram, membros novos pós-pivot. Cada coorte conta uma história.

6. **Validação da Tese** — A nova tese está ressoando? Indicadores:
   - Pessoas usam a linguagem da tese espontaneamente?
   - Conteúdo da nova tese é compartilhado organicamente?
   - A tese gera conversas e debate genuíno?
   - Novos membros citam a tese como motivo de adesão?

7. **Avaliação de ROI do Pivot** — O pivot valeu o investimento? Calcular:
   custo total da transição, perda de membros/engajamento, ganho de
   novos membros/engajamento, projeção de trajetória.

8. **Decisão sobre Próximo Passo** — Com base nos dados:
   - **Consolidar:** Nova tese funciona, investir em escala
   - **Ajustar:** Direção certa, execução precisa refinamento
   - **Re-pivotar:** Nova tese também não funciona, voltar ao diagnóstico
   - **Descontinuar:** Evidência insuficiente para continuar

## Outputs

- [ ] Comparativo antes vs. depois para todas as métricas-chave
- [ ] Health score pós-pivot com comparativo
- [ ] Análise de perfil da nova audiência
- [ ] Análise de retenção por coorte (antigos/novos)
- [ ] Avaliação de ressonância da nova tese
- [ ] Cálculo de ROI do pivot
- [ ] Decisão documentada sobre próximo passo
- [ ] Relatório completo para stakeholders

## Quality Gate

| Critério                          | Mínimo Aceitável                         |
|-----------------------------------|------------------------------------------|
| Período de avaliação              | Mínimo 30 dias pós-estabilização         |
| Métricas comparadas               | Antes vs. depois para todas as chave     |
| Health score calculado            | Com comparativo detalhado                |
| Coortes analisadas                | Separação clara antigos/novos            |
| Decisão fundamentada              | Baseada em dados, não opinião            |
| Stakeholders informados           | Relatório entregue e discutido           |

## Próxima Fase

→ Depende da decisão:
- **Consolidar** → `movement-scaling/00-health-assessment.md`
- **Ajustar** → Retornar a `01-new-thesis.md` com aprendizados
- **Re-pivotar** → Retornar a `00-diagnosis.md` com dados novos
- **Descontinuar** → Encerrar com retrospectiva e arquivo

### Framework de Avaliação do Pivot

**Pivot bem-sucedido quando:**
- Health score pós-pivot > pré-pivot
- Retenção de pelo menos 50% da base anterior
- Novos membros chegando por causa da nova tese
- Tração orgânica visível em 30-60 dias
- Time motivado com a nova direção

**Pivot fracassado quando:**
- Perdeu base anterior sem ganhar nova
- Health score pior que antes do pivot
- Nenhuma tração orgânica após 60 dias

### Viés a Evitar

- Confirmação: buscar só evidências de que funcionou
- Sunk cost: continuar porque "já gastamos tanto"
- Impaciência: julgar cedo demais sem dar tempo
