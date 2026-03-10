---
id: script-cohort-retention
name: Calculadora de Retenção por Coorte
squad: movement
type: script
tags:
  - coorte
  - retenção
  - churn
  - análise
---

# Calculadora de Retenção por Coorte

## Propósito

Calcular e visualizar retenção por coorte para entender quando e por que
membros deixam de participar. Separa "quando a pessoa entrou" de "quanto
tempo ficou" — essencial para diagnosticar problemas de retenção.

## Definições

- **Coorte:** Grupo que entrou no mesmo período (semana ou mês)
- **Retenção:** % da coorte ainda ativa após N dias
- **Ativo:** Realizou 1+ ação significativa no período
- **Churn:** % que deixou de ser ativo

## Passo a Passo

### 1. Definir Parâmetros

```
Período: [início — fim] | Granularidade: [semanal/mensal]
Definição de ativo: [critério específico]
Intervalos: dia 1, 7, 14, 30, 60, 90
```

### 2. Montar Tabela de Coorte

| Coorte   | n    | Dia 1 | Dia 7 | Dia 14 | Dia 30 | Dia 60 | Dia 90 |
|----------|------|-------|-------|--------|--------|--------|--------|
| Set 2025 | 100  | 80%   | 55%   | 42%    | 30%    | 22%    | 18%    |
| Out 2025 | 120  | 82%   | 60%   | 48%    | 35%    | 25%    | —      |
| Nov 2025 | 95   | 78%   | 52%   | 40%    | 28%    | —      | —      |

### 3. Calcular Métricas

```
Retenção média dia N = Soma(retenção dia N por coorte) / Nº coortes
Churn por intervalo = Retenção dia X - Retenção dia Y
Maior ponto de churn = Intervalo com maior queda %
```

### 4. Análise de Padrões

- **Maior churn dia 1-7?** Problema de onboarding
- **Maior churn dia 30-60?** Problema de engajamento longo prazo
- **Coortes recentes retêm melhor?** Algo melhorou no processo
- **Sazonalidade?** Coortes de férias retêm diferente?

## Benchmarks

| Intervalo | Média  | Boa    | Excepcional |
|-----------|--------|--------|-------------|
| Dia 1     | 60-70% | 75-85% | > 85%       |
| Dia 7     | 35-45% | 50-60% | > 65%       |
| Dia 30    | 20-30% | 30-40% | > 45%       |
| Dia 90    | 10-15% | 18-25% | > 30%       |

## Template de Relatório

```
Período: [datas]  |  Coortes: [n]  |  Membros: [n]

RETENÇÃO MÉDIA: D1 [X%] | D7 [X%] | D30 [X%] | D90 [X%]
MAIOR CHURN: Dia [N]→[M] ([X%] de perda)
TENDÊNCIA: Coortes recentes [melhoram/pioram/estáveis]
MELHOR COORTE: [qual] — Hipótese: [por quê]
PIOR COORTE: [qual] — Hipótese: [por quê]

AÇÕES:
1. [Se churn alto D1-7]: Melhorar onboarding
2. [Se churn alto D7-30]: Mais rituais de engajamento
3. [Se churn alto D30+]: Investigar perda de valor
```

## Dicas

- Mínimo 5 coortes para padrões confiáveis
- Coortes < 20 membros geram dados não confiáveis
- Separar coortes por canal de aquisição revela qualidade por fonte
- Mudanças no onboarding devem ser avaliadas comparando coortes
