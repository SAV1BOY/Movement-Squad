---
id: script-signal-clustering
name: Ferramenta de Clustering de Sinais
squad: movement
type: script
tags:
  - sinais
  - clustering
  - padrões
  - análise
---

# Ferramenta de Clustering de Sinais

## Propósito

Agrupar sinais culturais em clusters temáticos que revelam padrões, tensões
e oportunidades. Sinais isolados são dados; clusters são inteligência.

## Pré-requisitos

Banco com 30+ sinais documentados via `signal-scrape-skeleton.md`, cada um
com descrição, fonte e sentimento. Território do movimento definido.

## Processo

### 1. Preparar Sinais
Exportar sinais para formato visual (post-its ou planilha). Cada sinal com:
ID, descrição curta (1 frase), plataforma, sentimento.

### 2. Agrupar por Afinidade
Cada membro do time agrupa sinais intuitivamente. Sem rótulos — apenas
juntar o que parece conectado. Mínimo 3 sinais por cluster, máximo 8-10
clusters. OK ter sinais soltos.

### 3. Consolidar (se em equipe)
Comparar agrupamentos. Identificar: clusters unânimes (forte), divergentes
(discutir), sinais que ninguém agrupou (ruído ou novidade).

### 4. Nomear e Documentar

```
Cluster: [Nome — 2-4 palavras]
Descrição: [1-2 frases]
Tensão central: [qual tensão cultural revela]
Sinais: [IDs] | Quantidade: [n]
Sentimento dominante: [pos/neg/misto]
Força: [forte/moderado/emergente]
```

### 5. Mapear Relações Entre Clusters

| Cluster A | Cluster B | Relação                         |
|-----------|-----------|----------------------------------|
| [nome]    | [nome]    | Complementar/Contraditório/Causal|

### 6. Priorizar

| Cluster | Relevância (1-5) | Oportunidade (1-5) | Urgência (1-5) | Score |
|---------|-------------------|---------------------|-----------------|-------|
| [nome]  | _                 | _                   | _               | _     |

### 7. Extrair Insights

Para cada cluster priorizado:
```
Insight: [Observação + interpretação]
Baseado em: [Cluster X, Y sinais]
Implicação: [O que significa para o movimento]
Oportunidade: [O que podemos fazer]
Risco de não agir: [O que acontece se ignorarmos]
```

## Template de Relatório

```
Data: YYYY-MM-DD | Sinais: [n] | Clusters: [n]

CLUSTERS (por prioridade):
1. [NOME] — Score [X/15] — [n] sinais — Insight: [...]
2. [NOME] — Score [X/15] — [n] sinais — Insight: [...]
3. [NOME] — Score [X/15] — [n] sinais — Insight: [...]

RELAÇÕES: [Cluster A]+[B]: [tipo] | [C]vs[D]: [tipo]
SINAIS SOLTOS: [n] — [possível significado]

TOP 3 INSIGHTS ACIONÁVEIS:
1. [insight + oportunidade]
2. [insight + oportunidade]
3. [insight + oportunidade]
```

## Dicas

- Clustering em grupo > individual
- Não forçar sinais em clusters
- Clusters pequenos podem ser emergentes, não irrelevantes
- Revisitar após 2-4 semanas com novos sinais
