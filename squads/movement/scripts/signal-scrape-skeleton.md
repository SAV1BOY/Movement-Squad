---
id: script-signal-scrape
name: Skeleton de Coleta de Sinais
squad: movement
type: script
tags:
  - sinais
  - coleta
  - pesquisa
  - social-listening
---

# Signal Scrape Skeleton

## Propósito

Guia para coleta sistemática de sinais culturais — manual e automatizada.
Sinais são fragmentos de comportamento e expressão que revelam tensões
culturais e oportunidades para o movimento.

## Definição de Sinal

Evidência observável de comportamento, sentimento ou tendência cultural.
Exemplos: post viral sobre tensão que o movimento endereça, vocabulário
emergente, produto concorrente, mudança de comportamento em dados.

## Processo Manual

### 1. Definir Território

```
Território: [tema cultural]
Palavras-chave: [10-15 termos + variações]
Plataformas: [TikTok, Reddit, X, Instagram, etc.]
Período: [janela temporal]
```

### 2. Rotina de Coleta por Plataforma

- **TikTok:** Hashtags + sons + termos. Salvar URL, views, comentários.
- **Reddit:** Subreddits relevantes. Threads com alto engajamento.
- **Twitter/X:** Termos + contas de referência. Tweets com ratio alto.
- **Instagram:** Hashtags, explore. Foco em comentários.
- **Google Trends:** Tendência de busca dos termos-chave.

Frequência: diária em fase de pesquisa, semanal em monitoramento.

### 3. Registrar Cada Sinal

```
ID: SIG-[n] | Data: YYYY-MM-DD | Plataforma: [onde]
URL: [link] | Métricas: [views, likes, shares]
Descrição: [1-2 frases]
Citação-chave: [trecho mais relevante]
Sentimento: [positivo/negativo/ambíguo]
Relevância: [alta/média/baixa]
Cluster: [tema ao qual pertence]
```

### 4. Classificar Sinais

| Tipo         | Descrição                              |
|-------------|----------------------------------------|
| Emergente    | Novo, pouca expressão ainda            |
| Crescente    | Em aceleração                          |
| Mainstream   | Amplamente adotado                     |
| Declinante   | Perdendo tração                        |
| Contra-sinal | Contradiz hipóteses do movimento       |

## Processo Automatizado

- **Social Listening:** Brandwatch, Sprinklr, Talkwalker
- **Alertas:** Google Alerts para cada palavra-chave
- **Custom:** Scripts Python com APIs de plataformas
- Revisar e ajustar termos semanalmente

## Análise

Após 30+ sinais, agrupar em clusters usando `signal-clustering-tool.md`.
Buscar: tensões recorrentes, linguagem emergente, oportunidades narrativas,
riscos e contra-narrativas, movimentos adjacentes.

## Critérios de Qualidade

- Mínimo 50 sinais para análise robusta
- Mínimo 3 plataformas diferentes
- Inclusão intencional de contra-sinais
- Cada sinal com fonte verificável
