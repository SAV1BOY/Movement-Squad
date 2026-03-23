---
id: movement-scoring-rubric
name: "Rubrica de Pontuação de Movimento"
squad: movement
type: utility
category: lib/utilities
version: 1.0.0
tags: [rubrica, pontuação, avaliação, movimento, utilidade]
---

# Rubrica de Pontuação de Movimento

## Propósito

Ferramenta padronizada para avaliar a saúde e maturidade de um movimento em suas múltiplas dimensões. Permite diagnóstico rápido e priorização de esforços.

## Dimensões de Avaliação

### 1. Tese (0-20 pontos)

| Pontuação | Critério |
|-----------|----------|
| 0-4 | Sem tese clara ou tese vaga |
| 5-8 | Tese existe mas inimigo ou sonho não são claros |
| 9-12 | Tese clara com inimigo, sonho e mecanismo definidos |
| 13-16 | Tese forte, defensável e compartilhável em uma frase |
| 17-20 | Tese magnética — pessoas se mobilizam ao ouvi-la |

### 2. Identidade (0-20 pontos)

| Pontuação | Critério |
|-----------|----------|
| 0-4 | Sem linguagem, símbolos ou código de identidade |
| 5-8 | Elementos básicos existem mas não são adotados |
| 9-12 | Linguagem e símbolos usados por membros ativos |
| 13-16 | Identidade forte — membros se reconhecem mutuamente |
| 17-20 | Identidade cultural — transcende o grupo original |

### 3. Comunidade (0-20 pontos)

| Pontuação | Critério |
|-----------|----------|
| 0-4 | Sem comunidade organizada |
| 5-8 | Grupo existe mas depende totalmente dos fundadores |
| 9-12 | Comunidade com papéis definidos e alguma autonomia |
| 13-16 | Comunidade autogerida com campeões ativos |
| 17-20 | Comunidade que cresce organicamente e se auto-regula |

### 4. Narrativa (0-20 pontos)

| Pontuação | Critério |
|-----------|----------|
| 0-4 | Sem manifesto, slogan ou narrativa coerente |
| 5-8 | Narrativa básica mas inconsistente entre canais |
| 9-12 | Manifesto publicado e narrativa consistente |
| 13-16 | Narrativa memorável com memes e slogans adotados |
| 17-20 | Narrativa que outros replicam sem coordenação |

### 5. Distribuição (0-20 pontos)

| Pontuação | Critério |
|-----------|----------|
| 0-4 | Sem presença em canais relevantes |
| 5-8 | Presença em 1-2 canais com alcance limitado |
| 9-12 | Presença multicanal com estratégia definida |
| 13-16 | Alcance significativo com engajamento alto |
| 17-20 | Distribuição orgânica — membros amplificam sem pedir |

## Classificação Geral

| Pontuação Total | Classificação | Recomendação |
|----------------|---------------|--------------|
| 0-20 | Pré-movimento | Voltar ao brief e tese |
| 21-40 | Nascente | Focar em tese e identidade |
| 41-60 | Emergente | Fortalecer comunidade e narrativa |
| 61-80 | Estabelecido | Escalar distribuição |
| 81-100 | Maduro | Proteger essência, inovar na borda |

## Como Usar

1. **Avalie cada dimensão** com honestidade (peça input de 3+ pessoas)
2. **Some os pontos** para classificação geral
3. **Identifique a dimensão mais fraca** — essa é a prioridade
4. **Reavalie a cada 90 dias** para medir progresso
5. **Documente a avaliação** com data e avaliadores

## Template de Avaliação

```yaml
avaliação:
  data: YYYY-MM-DD
  avaliadores: []
  movimento: ""
  pontuações:
    tese: 0
    identidade: 0
    comunidade: 0
    narrativa: 0
    distribuição: 0
  total: 0
  classificação: ""
  dimensão_prioritária: ""
  próximos_passos: []
```

## Integração

- Tese avaliada em detalhe pelo `thesis-strength-rubric`
- Comunidade avaliada pelo `community-health-rubric`
- Narrativa avaliada pelo `manifesto-scoring-rubric`
- Distribuição avaliada pelo `memetic-spread-rubric`
