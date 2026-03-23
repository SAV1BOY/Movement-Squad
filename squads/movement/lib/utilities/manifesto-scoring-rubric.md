---
id: manifesto-scoring-rubric
name: "Rubrica de Pontuação de Manifesto"
squad: movement
type: utility
category: lib/utilities
version: 1.0.0
tags: [rubrica, manifesto, avaliação, narrativa, utilidade]
---

# Rubrica de Pontuação de Manifesto

## Propósito

Ferramenta para avaliar a eficácia de um manifesto de movimento. Mede se o manifesto cumpre suas funções: emocionar, convencer e mobilizar.

## Critérios de Avaliação

### 1. Impacto Emocional (0-10)

| Pontuação | Descrição |
|-----------|-----------|
| 0-2 | Sem reação emocional — leitura indiferente |
| 3-4 | Interesse leve mas sem emoção forte |
| 5-6 | Provoca uma emoção identificável |
| 7-8 | Provoca emoção forte (raiva, esperança, pertencimento) |
| 9-10 | Provoca emoção que leva à ação imediata |

**Teste:** Leia em voz alta para 5 pessoas. Pelo menos 3 devem reagir visivelmente.

### 2. Clareza do Inimigo (0-10)

| Pontuação | Descrição |
|-----------|-----------|
| 0-2 | Sem inimigo identificável |
| 3-4 | Inimigo vago ou abstrato demais |
| 5-6 | Inimigo claro mas sem urgência |
| 7-8 | Inimigo claro, urgente e reconhecível |
| 9-10 | Inimigo que o leitor já sentia mas não sabia nomear |

### 3. Visão do Futuro (0-10)

| Pontuação | Descrição |
|-----------|-----------|
| 0-2 | Sem visão de futuro ou visão genérica |
| 3-4 | Visão existe mas é abstrata |
| 5-6 | Visão concreta mas não inspiradora |
| 7-8 | Visão concreta e inspiradora |
| 9-10 | Visão que o leitor quer habitar — vívida e desejável |

### 4. Chamada à Ação (0-10)

| Pontuação | Descrição |
|-----------|-----------|
| 0-2 | Sem CTA ou CTA vago |
| 3-4 | CTA existe mas é complexo ou distante |
| 5-6 | CTA claro mas com fricção moderada |
| 7-8 | CTA claro, imediato e com baixa fricção |
| 9-10 | CTA irresistível — custo de não agir parece maior |

### 5. Memorabilidade (0-10)

| Pontuação | Descrição |
|-----------|-----------|
| 0-2 | Nenhuma frase fica na memória |
| 3-4 | Uma frase é lembrada com esforço |
| 5-6 | 1-2 frases são citáveis |
| 7-8 | 3+ frases são naturalmente citáveis |
| 9-10 | Frases entram no vocabulário do grupo |

**Teste:** 24h depois, peça para recitar algo. Se lembram de 2+ frases, ≥ 7.

## Classificação

| Total | Nível | Recomendação |
|-------|-------|--------------|
| 0-10 | Rascunho | Reescrever do zero |
| 11-20 | Fraco | Reestruturar usando `manifesto-block-component` |
| 21-30 | Funcional | Refinar linguagem e CTA |
| 31-40 | Forte | Pronto para publicação |
| 41-50 | Memorável | Distribuir amplamente |

## Checklist Rápido

- [ ] O manifesto tem menos de 800 palavras?
- [ ] Pode ser lido em voz alta em menos de 4 minutos?
- [ ] A primeira frase captura atenção?
- [ ] O inimigo é nomeado nos primeiros 3 parágrafos?
- [ ] A visão é concreta o suficiente para ser visualizada?
- [ ] O CTA pode ser executado em menos de 2 minutos?
- [ ] Pelo menos 3 frases são citáveis isoladamente?

## Template de Avaliação

```yaml
avaliação_manifesto:
  data: YYYY-MM-DD
  manifesto: "" # título ou ID
  avaliador: ""
  pontuações:
    impacto_emocional: 0
    clareza_do_inimigo: 0
    visão_do_futuro: 0
    chamada_à_ação: 0
    memorabilidade: 0
  total: 0
  classificação: ""
  frase_mais_forte: ""
  ponto_mais_fraco: ""
  recomendação: ""
```

## Integração

- Avalia manifestos construídos com `manifesto-block-component`
- Resultado alimenta `movement-scoring-rubric` (dimensão Narrativa)
- Manifestos fracos voltam para revisão com `thesis-component`
