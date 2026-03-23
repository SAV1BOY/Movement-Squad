---
id: script-community-health
name: Auditoria de Saúde da Comunidade
squad: movement
type: script
tags:
  - comunidade
  - saúde
  - auditoria
  - diagnóstico
---

# Auditoria de Saúde da Comunidade

## Propósito

Avaliar saúde da comunidade em todas as dimensões. Resultado: diagnóstico
com scores e recomendações.

## Dimensões (Score 1-10 cada)

### 1. Vitalidade

| Métrica            | Benchmark     |
|--------------------|---------------|
| DAU/MAU ratio      | > 0.30        |
| Mensagens por dia  | Tendência ↑   |
| Tópicos novos/sem  | Tendência ↑   |

### 2. Engajamento

| Métrica              | Benchmark   |
|----------------------|-------------|
| Respostas por tópico | > 3         |
| Tempo até 1ª resposta| < 4h        |
| Participação rituais | > 15% MAU   |

### 3. Retenção

| Métrica        | Benchmark |
|----------------|-----------|
| Retenção D1    | > 70%     |
| Retenção D7    | > 50%     |
| Retenção D30   | > 35%     |
| Churn mensal   | < 15%     |

### 4. Distribuição

| Métrica           | Benchmark |
|-------------------|-----------|
| Creator ratio     | > 10%     |
| Top 10% share     | < 50%     |
| Lurker ratio      | < 60%     |

### 5. Sentimento

| Métrica           | Benchmark      |
|-------------------|----------------|
| Sentimento geral  | > 70% positivo |
| NPS comunidade    | > 7            |

### 6. Auto-Sustentação

| Métrica              | Benchmark |
|----------------------|-----------|
| Peer-to-peer ratio   | > 60%     |
| Hosts voluntários    | > 3       |
| Acolhimento novatos  | > 80%     |

## Cálculo do Score Final

```
Score = Vitalidade×0.20 + Engajamento×0.20 + Retenção×0.25
      + Distribuição×0.15 + Sentimento×0.10 + Auto-Sustentação×0.10
```

## Interpretação

| Score | Status    | Ação                               |
|-------|-----------|------------------------------------|
| 8-10  | Excelente | Manter e considerar escala         |
| 6-7   | Saudável  | Otimizar pontos fracos             |
| 4-5   | Atenção   | Intervenção em dimensões baixas    |
| 2-3   | Alerta    | Plano de recuperação urgente       |
| 0-1   | Crítico   | Avaliar viabilidade de continuação |

## Template de Relatório

```
Data: YYYY-MM-DD | Membros: [n] | MAU: [n]
Vitalidade [X/10] | Engajamento [X/10] | Retenção [X/10]
Distribuição [X/10] | Sentimento [X/10] | Auto-Sust. [X/10]
SCORE FINAL: [X/10]
FORÇAS: 1.[...] 2.[...] 3.[...]
ATENÇÃO: 1.[...] 2.[...] 3.[...]
AÇÕES: 1.[Ação]—[Responsável]—[Prazo]
```
