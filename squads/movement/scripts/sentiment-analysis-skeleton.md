---
id: script-sentiment
name: Skeleton de Análise de Sentimento
squad: movement
type: script
tags:
  - sentimento
  - análise
  - percepção
  - monitoramento
---

# Skeleton de Análise de Sentimento

## Propósito

Conduzir análise de sentimento em torno do movimento — manual e automatizada.
Revela como as pessoas realmente se sentem, além do que dizem publicamente.

## Fontes de Dados

| Fonte                | Tipo       | Coleta                         |
|----------------------|------------|--------------------------------|
| Comentários públicos | Espontâneo | Social listening, APIs         |
| Menções ao movimento | Espontâneo | Alertas, monitoramento         |
| Pesquisa com membros | Solicitado | Forms, enquetes                |
| Conversas internas   | Espontâneo | Análise de comunidade          |

## Classificação

| Categoria | Subcategorias                                         |
|-----------|-------------------------------------------------------|
| Positivo  | Entusiasmo ativo, identificação pessoal, apoio passivo|
| Negativo  | Crítica construtiva, rejeição, hostilidade, decepção  |
| Neutro    | Observação, pergunta genuína, menção sem opinião      |
| Ambíguo   | Misto ou difícil de classificar                       |

## Processo

### 1. Coletar Amostra
- Mínimo 100 menções para análise robusta
- Incluir todas as plataformas relevantes
- Não filtrar pelo sentimento esperado

### 2. Classificar Cada Menção

```
ID: SENT-[n] | Fonte: [plataforma] | Data: YYYY-MM-DD
Texto: [citação]
Sentimento: [positivo/negativo/neutro/ambíguo]
Intensidade: [1-5] | Tema: [sobre o quê]
```

### 3. Calcular

```
Net Sentiment = % Positivo - % Negativo
```

### 4. Analisar
- Top 3 motivos de sentimento positivo
- Top 3 motivos de sentimento negativo
- Citações mais representativas
- Mudanças vs. análise anterior

## Ferramentas Automatizadas

Social listening (Brandwatch, Sprinklr), APIs de NLP (Google Cloud,
AWS Comprehend), open source (VADER, TextBlob). Sempre validar 10-20%
da amostra manualmente — sarcasmo e contexto cultural escapam.

## Template de Relatório

```
Período: [datas] | Fontes: [lista] | Amostra: [n]

Positivo: [X%] | Negativo: [Y%] | Neutro: [Z%]
Net Sentiment: [X-Y]% | Tendência: [↑↓→]

TEMAS POSITIVOS: 1.[tema] 2.[tema] 3.[tema]
TEMAS NEGATIVOS: 1.[tema] 2.[tema] 3.[tema]
ALERTAS: [picos ou anomalias]
AÇÕES: 1.[recomendação] 2.[recomendação]
```

## Benchmarks

| Contexto              | Net Sentiment Saudável |
|-----------------------|------------------------|
| Movimento em lançamento| > +30%                |
| Movimento maduro       | > +40%                |
| Pós-crise              | > +10%                |
| Território polêmico    | > +15%                |
