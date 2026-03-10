---
id: memetic-spread-rubric
name: "Rubrica de Espalhamento Memético"
squad: movement
type: utility
category: lib/utilities
version: 1.0.0
tags: [rubrica, meme, viralidade, espalhamento, utilidade]
---

# Rubrica de Espalhamento Memético

## Propósito

Ferramenta para avaliar o potencial e o desempenho de espalhamento memético dos artefatos de um movimento. Mede quão eficazmente as ideias se propagam de pessoa a pessoa.

## Critérios de Avaliação

### 1. Simplicidade (0-10)

| Pontuação | Descrição |
|-----------|-----------|
| 0-2 | Mensagem complexa que exige explicação longa |
| 3-4 | Compreensível mas requer contexto |
| 5-6 | Entendida em uma leitura rápida |
| 7-8 | Entendida em 5 segundos |
| 9-10 | Entendida instantaneamente, sem contexto prévio |

### 2. Emoção (0-10)

| Pontuação | Descrição |
|-----------|-----------|
| 0-2 | Neutro — sem reação emocional |
| 3-4 | Interesse leve |
| 5-6 | Uma emoção identificável (humor, surpresa) |
| 7-8 | Emoção forte que motiva compartilhamento |
| 9-10 | Emoção visceral — impossível não reagir |

**Emoções que mais espalham (ordem):**
1. Indignação / raiva moral
2. Inspiração / esperança
3. Humor / diversão
4. Surpresa / insight
5. Pertencimento / orgulho

### 3. Replicabilidade (0-10)

| Pontuação | Descrição |
|-----------|-----------|
| 0-2 | Impossível de replicar — muito específico |
| 3-4 | Replicável com esforço significativo |
| 5-6 | Replicável com alguma adaptação |
| 7-8 | Fácil de replicar e adaptar |
| 9-10 | Template natural — pessoas criam variações espontaneamente |

### 4. Moeda Social (0-10)

| Pontuação | Descrição |
|-----------|-----------|
| 0-2 | Compartilhar não diz nada sobre quem compartilha |
| 3-4 | Compartilhar mostra interesse leve |
| 5-6 | Compartilhar sinaliza uma opinião |
| 7-8 | Compartilhar sinaliza identidade e valores |
| 9-10 | Compartilhar é uma declaração pessoal forte |

### 5. Gatilho (0-10)

| Pontuação | Descrição |
|-----------|-----------|
| 0-2 | Sem conexão com gatilhos do cotidiano |
| 3-4 | Conecta a eventos raros |
| 5-6 | Conecta a eventos mensais |
| 7-8 | Conecta a eventos semanais |
| 9-10 | Conecta a eventos diários — lembrado constantemente |

**Exemplo:** "Got Milk?" é lembrado toda vez que alguém abre a geladeira (gatilho diário).

## Classificação

| Total | Potencial | Expectativa |
|-------|-----------|-------------|
| 0-10 | Inerte | Não vai se espalhar |
| 11-20 | Baixo | Espalhamento limitado ao grupo |
| 21-30 | Moderado | Espalhamento em nicho |
| 31-40 | Alto | Potencial de viralização em público-alvo |
| 41-50 | Viral | Potencial de transcender o público-alvo |

## Métricas de Espalhamento Real

| Métrica | Fórmula | Meta |
|---------|---------|------|
| Taxa de compartilhamento | Compartilhamentos / Impressões | > 3% |
| Coeficiente viral (K) | Convites × Taxa de conversão | > 1.0 |
| Tempo de pico | Horas até pico de compartilhamento | < 24h |
| Cauda longa | Compartilhamentos após 7 dias / Total | > 20% |
| Variações criadas | Número de adaptações pela comunidade | > 10 |

## Template de Avaliação

```yaml
avaliação_memética:
  data: YYYY-MM-DD
  artefato: "" # nome ou ID do conteúdo
  tipo: "" # meme | slogan | manifesto | vídeo
  avaliador: ""
  pontuações:
    simplicidade: 0
    emoção: 0
    replicabilidade: 0
    moeda_social: 0
    gatilho: 0
  total: 0
  potencial: ""
  emoção_dominante: ""
  gatilho_principal: ""
  recomendação: ""
```

## Integração

- Avalia artefatos classificados pela `artifact-taxonomy`
- Resultado alimenta `movement-scoring-rubric` (dimensão Distribuição)
- Orienta produção via `creator-brief-component`
- Conecta ao padrão `meme-to-manifesto-pattern`
