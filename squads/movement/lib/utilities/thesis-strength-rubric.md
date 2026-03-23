---
id: thesis-strength-rubric
name: "Rubrica de Força da Tese"
squad: movement
type: utility
category: lib/utilities
version: 1.0.0
tags: [rubrica, tese, avaliação, força, utilidade]
---

# Rubrica de Força da Tese

## Propósito

Ferramenta para avaliar a força de uma tese de movimento em profundidade. Uma tese fraca produz um movimento fraco — esta rubrica identifica onde fortalecer.

## Critérios de Avaliação

### 1. Clareza (0-10)

| Pontuação | Descrição |
|-----------|-----------|
| 0-2 | Impossível entender a tese em uma leitura |
| 3-4 | Compreensível mas ambígua |
| 5-6 | Clara para quem já conhece o tema |
| 7-8 | Clara para qualquer pessoa em 30 segundos |
| 9-10 | Cristalina — impossível de interpretar errado |

**Teste:** Peça a 5 pessoas para parafrasear a tese. Se 4+ dizem a mesma coisa, clareza ≥ 7.

### 2. Tensão (0-10)

| Pontuação | Descrição |
|-----------|-----------|
| 0-2 | Sem tensão — ninguém discordaria |
| 3-4 | Tensão leve — incomoda poucos |
| 5-6 | Tensão moderada — divide opiniões |
| 7-8 | Tensão forte — provoca debate |
| 9-10 | Tensão magnética — impossível ser indiferente |

**Teste:** Se ninguém discorda da tese, ela não é forte o suficiente.

### 3. Evidência (0-10)

| Pontuação | Descrição |
|-----------|-----------|
| 0-2 | Sem dados ou evidências |
| 3-4 | Anedotas e opiniões apenas |
| 5-6 | Alguns dados mas sem narrativa |
| 7-8 | Dados + narrativa + evidência observável |
| 9-10 | Prova irrefutável com múltiplas fontes |

**Teste:** Um cético inteligente seria convencido?

### 4. Acionabilidade (0-10)

| Pontuação | Descrição |
|-----------|-----------|
| 0-2 | Diagnóstico puro sem caminho de ação |
| 3-4 | Ação vaga — "devemos mudar" |
| 5-6 | Ação clara mas sem primeiros passos |
| 7-8 | Ação clara com primeiros passos definidos |
| 9-10 | Ação imediata que qualquer pessoa pode tomar |

**Teste:** Uma pessoa convencida sabe o que fazer nos próximos 5 minutos?

### 5. Compartilhabilidade (0-10)

| Pontuação | Descrição |
|-----------|-----------|
| 0-2 | Impossível resumir — precisa de contexto extenso |
| 3-4 | Resumível mas não memorável |
| 5-6 | Cabe em um parágrafo com impacto |
| 7-8 | Cabe em uma frase memorável |
| 9-10 | Cabe em um tweet que se espalha sozinho |

**Teste:** A tese pode ser escrita em um guardanapo e ainda funcionar?

## Classificação

| Total | Nível | Status |
|-------|-------|--------|
| 0-10 | Embrionária | Repensar do zero |
| 11-20 | Fraca | Fortalecer urgentemente |
| 21-30 | Promissora | Refinar 1-2 dimensões |
| 31-40 | Forte | Pronta para manifesto |
| 41-50 | Magnética | Pronta para escalar |

## Diagnóstico por Padrão

| Se baixo em... | Provável causa | Ação recomendada |
|----------------|---------------|-----------------|
| Clareza | Tese tenta abranger demais | Estreitar o foco |
| Tensão | Inimigo genérico ou ausente | Nomear o inimigo com especificidade |
| Evidência | Tese baseada em intuição | Coletar sinais com `signal-to-claim-pattern` |
| Acionabilidade | Mecanismo não definido | Desenhar a escada de ação |
| Compartilhabilidade | Linguagem acadêmica | Reescrever na linguagem do público |

## Template de Avaliação

```yaml
avaliação_de_tese:
  data: YYYY-MM-DD
  tese: ""
  avaliador: ""
  pontuações:
    clareza: 0
    tensão: 0
    evidência: 0
    acionabilidade: 0
    compartilhabilidade: 0
  total: 0
  classificação: ""
  dimensão_mais_fraca: ""
  recomendação: ""
```

## Integração

- Avalia teses criadas com `thesis-component`
- Provas construídas com `proof-component`
- Resultado alimenta `movement-scoring-rubric` (dimensão Tese)
- Teses fracas podem ser arquivadas em `archive/deprecated-theses/`
