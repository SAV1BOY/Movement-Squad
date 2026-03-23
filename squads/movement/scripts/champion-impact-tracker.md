---
id: script-champion-impact
name: Rastreador de Impacto de Champions
squad: movement
type: script
tags:
  - champions
  - impacto
  - métricas
  - rastreamento
---

# Rastreador de Impacto de Champions

## Propósito

Medir o impacto individual e coletivo dos champions do movimento. Identificar
alto desempenho, diagnosticar problemas e justificar investimento com dados.

## Métricas por Champion

| Categoria    | Métrica                    | Como Medir                         |
|-------------|----------------------------|------------------------------------|
| Atividade   | Conteúdos criados          | Contagem por período               |
| Atividade   | Participação em rituais    | Presença em eventos recorrentes    |
| Atividade   | Iniciativas propostas      | Atividades sugeridas pelo champion |
| Alcance     | Impressões de conteúdo     | Views do conteúdo criado           |
| Alcance     | Engajamento gerado         | Interações no conteúdo             |
| Recrutamento| Membros trazidos           | Novos membros indicados            |
| Recrutamento| Conversão de indicados     | % dos indicados que ficaram ativos |
| Qualidade   | Alinhamento narrativo      | Score de consistência              |
| Qualidade   | Sentimento gerado          | Sentimento nos comentários         |

## Cálculo do Impact Score (0-100)

```
Atividade (0-25):    Conteúdos×2 + Rituais(%)×10 + Iniciativas×5
Alcance (0-25):      log10(Impressões)×3 + Taxa engajamento×100
Recrutamento (0-25): Membros trazidos×5 + Taxa retenção indicados×15
Qualidade (0-25):    Alinhamento×2 + Melhorias implementadas×3
```

## Template de Ficha Individual

```
Champion: [nome]  |  Desde: [data]  |  Tier: [aspirante/ativo/destaque]
Período: [data início — data fim]

ATIVIDADE:  Conteúdos [n] | Rituais [n/n] | Iniciativas [n]
ALCANCE:    Impressões [n] | Engajamento [n] ([X%])
RECRUTAMENTO: Trazidos [n] | Retenção indicados [X%]
QUALIDADE:  Alinhamento [X/10] | Feedback [pos/misto/neg]

IMPACT SCORE: [X/100]  |  Tendência: [↑↓→]
```

## Dashboard Coletivo

```
CHAMPIONS ATIVOS: [n]  |  PERÍODO: [data]

Impact Score médio: [X/100]
Alto impacto (>70): [n] | Médio (40-70): [n] | Baixo (<40): [n]

TOP 3: 1.[nome]:[X] 2.[nome]:[X] 3.[nome]:[X]
ATENÇÃO: [champions com atividade em queda]

ROI: Custo [R$] / Valor gerado [R$] = [X]x
```

## Ações por Score

| Score   | Status      | Ação                                    |
|---------|-------------|-----------------------------------------|
| 80-100  | Excepcional | Reconhecer publicamente, promover tier   |
| 60-79   | Forte       | Manter, oferecer novas missões           |
| 40-59   | Adequado    | Check-in, identificar bloqueios          |
| 20-39   | Abaixo      | Conversa individual, oferecer suporte    |
| 0-19    | Inativo     | Avaliar permanência no programa          |

## Cadência

- **Semanal:** Atualizar métricas de atividade e alcance
- **Mensal:** Ficha individual completa + impact score
- **Trimestral:** Análise coletiva + decisão de renovação/graduação
