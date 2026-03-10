---
id: movement-type-taxonomy
name: "Taxonomia de Tipos de Movimento"
squad: movement
type: taxonomy
category: lib/taxonomies
version: 1.0.0
tags: [taxonomia, movimento, classificação, tipo, estratégia]
---

# Taxonomia de Tipos de Movimento

## Propósito

Sistema de classificação para os tipos fundamentais de movimento. Cada tipo tem dinâmicas, riscos e estratégias distintas. Classificar corretamente orienta toda a execução.

## Tipos Fundamentais

### 1. Movimento de Produto

```yaml
tipo: produto
definição: "Movimento que nasce ao redor de um produto/serviço que carrega um ponto de vista"
motor: "Experiência de uso → Advocacia → Cultura"
exemplos: ["Apple", "CrossFit", "Notion", "Tesla"]
risco_principal: "Depender do produto — se o produto falha, o movimento morre"
duração_típica: "Enquanto o produto for relevante"
métrica_central: "% de usuários que se identificam com a marca"
```

### 2. Movimento de Crença

```yaml
tipo: crença
definição: "Movimento unido por uma crença compartilhada sobre como o mundo deveria ser"
motor: "Tese forte → Narrativa → Comunidade de crentes"
exemplos: ["Slow Food", "Minimalismo", "FIRE (Financial Independence)"]
risco_principal: "Tornar-se dogmático ou sectário"
duração_típica: "Décadas se a crença evolui"
métrica_central: "Adoção da crença em práticas reais"
```

### 3. Movimento de Missão

```yaml
tipo: missão
definição: "Movimento com objetivo concreto e mensurável a ser alcançado"
motor: "Problema urgente → Solução proposta → Mobilização para resultado"
exemplos: ["Ice Bucket Challenge (ALS)", "Wikipedia", "One Laptop Per Child"]
risco_principal: "Alcançar o objetivo e perder razão de existir"
duração_típica: "Até o objetivo ser alcançado ou abandonado"
métrica_central: "Progresso em direção ao objetivo declarado"
```

### 4. Movimento Anti (Contra)

```yaml
tipo: anti
definição: "Movimento definido pela oposição a algo — sistema, prática, instituição"
motor: "Indignação → Mobilização → Resistência organizada"
exemplos: ["Occupy Wall Street", "Anti-fast fashion", "Adblock"]
risco_principal: "Definir-se apenas pelo que é contra, sem proposta positiva"
duração_típica: "Enquanto o inimigo existir"
métrica_central: "Impacto mensurável no alvo de oposição"
```

### 5. Movimento de Identidade

```yaml
tipo: identidade
definição: "Movimento que dá nome e voz a um grupo que existia mas não se reconhecia"
motor: "Nomeação → Reconhecimento → Orgulho → Ação coletiva"
exemplos: ["#MeToo", "Black Lives Matter", "Neurodivergência"]
risco_principal: "Cooptação por interesses externos ou comercialização"
duração_típica: "Gerações — identidades são permanentes"
métrica_central: "Mudança de normas sociais e legislação"
```

### 6. Movimento Cultural

```yaml
tipo: cultural
definição: "Movimento que busca mudar normas culturais, estéticas ou comportamentais"
motor: "Nova estética/prática → Adoção por early adopters → Mainstream"
exemplos: ["Punk", "Maker Movement", "Remote Work", "Creator Economy"]
risco_principal: "Diluição ao se tornar mainstream"
duração_típica: "5-15 anos como movimento, depois vira cultura"
métrica_central: "Adoção da nova norma/prática pela maioria"
```

## Matriz Comparativa

| Aspecto | Produto | Crença | Missão | Anti | Identidade | Cultural |
|---------|---------|--------|--------|------|------------|----------|
| Início rápido | ★★★★★ | ★★☆☆☆ | ★★★☆☆ | ★★★★☆ | ★★★☆☆ | ★★☆☆☆ |
| Sustentabilidade | ★★★☆☆ | ★★★★★ | ★★☆☆☆ | ★★☆☆☆ | ★★★★★ | ★★★★☆ |
| Monetização | ★★★★★ | ★★★☆☆ | ★★☆☆☆ | ★☆☆☆☆ | ★★☆☆☆ | ★★★☆☆ |
| Impacto social | ★★☆☆☆ | ★★★☆☆ | ★★★★★ | ★★★★☆ | ★★★★★ | ★★★★☆ |
| Risco de cooptação | ★★☆☆☆ | ★★★☆☆ | ★★☆☆☆ | ★★★☆☆ | ★★★★★ | ★★★★☆ |

## Movimentos Híbridos

A maioria dos movimentos combina 2-3 tipos:
- **Patagonia** = Produto + Crença + Anti
- **Tesla** = Produto + Missão
- **#MeToo** = Identidade + Anti + Missão
- **CrossFit** = Produto + Crença + Cultural

## Como Classificar

1. Pergunte: "O que mantém esse movimento vivo se tiramos o fundador?"
2. Pergunte: "As pessoas se juntam POR algo ou CONTRA algo?"
3. Pergunte: "Existe um objetivo finito ou uma crença permanente?"
4. O tipo dominante determina a estratégia central

## Integração

- Tipo informa a estrutura do `movement-brief-component`
- Tipo influencia o tom do `manifesto-block-component`
- Tipo determina métricas no `movement-scoring-rubric`
- Exemplos documentados em `archive/iconic-movements/`
