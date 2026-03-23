---
id: script-memetic-spread
name: Rastreador de Spread Memético
squad: movement
type: script
tags:
  - memético
  - viralidade
  - propagação
  - rastreamento
---

# Rastreador de Spread Memético

## Propósito

Rastrear como a tese e artefatos do movimento se espalham organicamente.
Propagação memética é o indicador mais forte de movimento real — quando pessoas
replicam e remixam a mensagem sem serem pedidas.

## Tipos de Propagação

| Tipo        | Descrição                                     | Exemplo                          |
|-------------|-----------------------------------------------|----------------------------------|
| Replicação  | Cópia fiel da mensagem                        | Share/RT, screenshot, citação    |
| Adaptação   | Modificação criativa que preserva essência     | Remix, paráfrase, novo contexto  |
| Mutação     | Variação que mantém DNA reconhecível           | Meme derivado, contra-narrativa  |

## Processo

### 1. Definir Elementos Rastreáveis

```
Elemento: [nome] | Tipo: [frase/visual/hashtag/formato]
Variações conhecidas: [lista]
Termos de busca: [palavras-chave para monitorar]
```

### 2. Registrar Ocorrências

```
ID: MEM-[n] | Data: YYYY-MM-DD | Plataforma: [onde]
Tipo: [replicação/adaptação/mutação]
Alcance: [views estimadas]
Fidelidade: [alta/média/baixa]
Sentimento: [positivo/negativo/neutro]
URL: [link]
```

### 3. Calcular Métricas

```
Taxa de replicação = Compartilhamentos / Impressões originais
Coeficiente viral = Réplicas secundárias / Réplicas primárias
Multiplicador = Impressões orgânicas / Impressões originais
Fidelidade média = Média dos scores de fidelidade (1-10)
```

## Interpretação

| Métrica          | Saudável | Atenção  | Alerta    |
|------------------|----------|----------|-----------|
| Multiplicador    | > 3x     | 1-3x    | < 1x      |
| Fidelidade       | > 7/10   | 5-7/10  | < 5/10    |
| Coef. viral      | > 0.5    | 0.1-0.5 | < 0.1     |
| % Adaptações     | 20-40%   | < 10%   | > 60% mut.|

## Template de Relatório

```
Período: [datas] | Elemento: [qual]

VOLUME: Replicações [n] | Adaptações [n] | Mutações [n]
ALCANCE: Original [n] → Orgânico [n] = Multiplicador [X]x
FIDELIDADE: [X/10] | COEF. VIRAL: [X]

DESTAQUES:
  Mais alcançada: [link]
  Mais criativa: [link]
  Mais inesperada: [link]

ALERTAS: [distorções preocupantes ou uso negativo]
TENDÊNCIA: [↑↓→] vs. período anterior
```

## Monitoramento

- **Manual:** Buscar termos em plataformas semanalmente
- **Automatizado:** Social listening + Google Alerts + APIs
- Sempre incluir adaptações e mutações, não só cópias diretas
- Contra-narrativas também são spread — monitorar sentimento
