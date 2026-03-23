---
id: script-experiment-calc
name: Calculadora de Experimentos
squad: movement
type: script
tags:
  - experimento
  - uplift
  - significância
  - teste
---

# Calculadora de Experimentos

## Propósito

Calcular uplift e significância prática em experimentos do movimento.
Responde: a diferença observada é real ou ruído? Se real, é grande o bastante?

## Conceitos

**Uplift:** `((Resultado Teste - Resultado Controle) / Resultado Controle) × 100`

**Significância estatística:** p < 0.05 = resultado provavelmente real.

**Significância prática:** Mesmo que estatisticamente real, justifica o investimento?

## Passo a Passo

### 1. Definir Experimento

| Campo             | Valor                                 |
|-------------------|---------------------------------------|
| Hipótese          | [o que esperamos]                     |
| Métrica primária  | [1 métrica principal]                 |
| Controle          | [versão atual]                        |
| Teste             | [nova versão]                         |
| Tamanho amostra   | [n por grupo]                         |
| Duração           | [dias/semanas]                        |
| Uplift mínimo     | [menor diferença relevante]           |

### 2. Tamanho de Amostra Necessário (95% confiança)

| Baseline | Uplift 20% rel. | Uplift 50% rel. |
|----------|-----------------|-----------------|
| 5%       | ~4.900/grupo    | ~800/grupo      |
| 10%      | ~2.200/grupo    | ~320/grupo      |
| 20%      | ~950/grupo      | ~140/grupo      |

Sem amostra suficiente, use avaliação qualitativa.

### 3. Calcular Resultados

```
Uplift = ((Teste - Controle) / Controle) × 100
Erro padrão ≈ √(p × (1-p) / n)
IC 95% = proporção ± 1.96 × erro padrão
```

### 4. Interpretar

| Cenário                              | Decisão              |
|--------------------------------------|----------------------|
| Estatística + praticamente sig.      | Implementar          |
| Estatística sig. mas efeito trivial  | Provavelmente não    |
| Não sig. mas efeito grande           | Retestar com +amostra|
| Não sig. e efeito pequeno            | Não implementar      |

## Uplifts Mínimos Relevantes para Movimentos

| Métrica               | Mínimo Relevante |
|-----------------------|-----------------|
| Taxa de engajamento   | 15-20% relativo |
| Retenção dia 7        | 10-15% relativo |
| Compartilhamento      | 25-30% relativo |
| Conversão para membro | 20-25% relativo |

## Template de Resultado

```
Experimento: [nome]
Hipótese: [esperado] | Período: [datas] | Amostra: [n/n]
Controle: [X%] | Teste: [Y%] | Uplift: [Z%] (IC: [min-max])
Significância: [p-value]
Decisão: [implementar/retestar/descartar]
Aprendizado: [insight independente do resultado]
```

## Armadilhas

- Encerrar teste cedo porque "já dá pra ver"
- Testar muitas variáveis ao mesmo tempo
- Ignorar efeito de novidade (resultado cai após semana 1)
- Não considerar custo de implementação no cálculo de valor
