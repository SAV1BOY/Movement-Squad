---
id: script-health-score
name: Calculadora de Health Score do Movimento
squad: movement
type: script
tags:
  - health-score
  - métricas
  - saúde
  - dashboard
---

# Calculadora de Health Score do Movimento

## Propósito

Calcular o score de saúde geral do movimento em 6 dimensões. Indicador
principal para decisões de escala, pivot ou investimento.

## As 6 Dimensões

### D1: Alcance (Peso 0.15)

Crescimento de audiência, share of voice, orgânico vs. pago, diversidade.
- 9-10: Crescimento acelerado, dominância no território
- 5-6: Crescimento modesto, presença adequada
- 1-2: Declínio, presença irrelevante

### D2: Engajamento (Peso 0.20)

Taxa de engajamento, profundidade, frequência de retorno, qualidade.
- 9-10: Engajamento profundo e recorrente
- 5-6: Engajamento adequado, espaço para melhora
- 1-2: Audiência passiva, quase sem interação

### D3: Comunidade (Peso 0.25)

Membros ativos, retenção por coorte, UGC, auto-organização.
- 9-10: Comunidade auto-sustentável e generativa
- 5-6: Comunidade funcional com dependência do time
- 1-2: Comunidade inexistente ou morta

### D4: Sentimento (Peso 0.15)

Sentimento geral, tendência, advocacy espontâneo, ausência de crises.
- 9-10: Amplamente positivo, advocacy forte
- 5-6: Misto mas sem problemas graves
- 1-2: Predominantemente negativo, crise ativa

### D5: Viralidade Orgânica (Peso 0.15)

Compartilhamento, conteúdo derivado, menções espontâneas, indicações.
- 9-10: Crescimento primariamente orgânico
- 5-6: Mix equilibrado orgânico/investido
- 1-2: Sem tração orgânica

### D6: Impacto (Peso 0.10)

Ações geradas, mudança de comportamento, impacto de marca, impacto cultural.
- 9-10: Impacto transformador mensurável
- 5-6: Impacto moderado, algumas ações geradas
- 1-2: Sem impacto mensurável

## Cálculo

```
Health Score = (D1×0.15) + (D2×0.20) + (D3×0.25) +
              (D4×0.15) + (D5×0.15) + (D6×0.10)
```

## Template de Registro

```
Movimento: [nome] | Data: YYYY-MM-DD | Avaliador: [nome]

D1 Alcance:      [X.X/10]
D2 Engajamento:  [X.X/10]
D3 Comunidade:   [X.X/10]
D4 Sentimento:   [X.X/10]
D5 Viralidade:   [X.X/10]
D6 Impacto:      [X.X/10]

HEALTH SCORE:    [X.X/10]
Anterior: [X.X] ([data]) | Tendência: [↑↓→]
Mais forte: [dimensão] | Mais fraca: [dimensão]
Ação prioritária: [o que fazer para melhorar a mais fraca]
```

## Interpretação

| Score | Status    | Recomendação                        |
|-------|-----------|-------------------------------------|
| 8-10  | Excelente | Escalar com confiança               |
| 6-7   | Saudável  | Otimizar antes de escalar           |
| 4-5   | Atenção   | Intervir em dimensões fracas        |
| 2-3   | Alerta    | Plano de recuperação ou pivot       |
| 0-1   | Crítico   | Avaliar descontinuação              |
