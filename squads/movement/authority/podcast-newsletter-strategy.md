---
id: podcast-newsletter-strategy
name: "Estratégia de Podcast e Newsletter"
squad: movement
type: authority
category: authority
version: 1.0.0
tags: [autoridade, podcast, newsletter, conteúdo, distribuição]
---

# Estratégia de Podcast e Newsletter

## Propósito

Framework para usar podcast e newsletter como canais-âncora de construção de autoridade e nutrição da comunidade do movimento.

## Por Que Podcast + Newsletter

Juntos, formam o combo mais poderoso para movimentos:
- **Podcast:** Profundidade, intimidade, conversa — constrói confiança
- **Newsletter:** Consistência, curadoria, ação — mantém engajamento
- **Juntos:** O podcast atrai, a newsletter retém

## Estratégia de Newsletter

### Formato Recomendado

```yaml
newsletter:
  nome: "" # nome memorável, não genérico
  frequência: "" # semanal é o sweet spot
  dia_e_hora: "" # consistência absoluta
  extensão: "" # 500-1000 palavras (5 min de leitura)
  tom: "" # pessoal, como carta a um amigo
  estrutura:
    - abertura: "" # reflexão pessoal ou observação da semana
    - conteúdo_principal: "" # insight, análise ou framework
    - curadoria: "" # 3-5 links relevantes com comentário
    - cta: "" # uma ação para o leitor
```

### Tipos de Newsletter para Movimentos

| Tipo | Foco | Exemplo | Frequência |
|------|------|---------|-----------|
| Curadoria | Melhor conteúdo do tema | "5 coisas que você precisa saber" | Semanal |
| Ensaio | Reflexão profunda original | "O que aprendi essa semana" | Semanal/quinzenal |
| Comunidade | Destaques de membros | "O que nossos membros criaram" | Quinzenal |
| Tática | Como fazer algo específico | "Template da semana" | Semanal |
| Mista | Combinação dos acima | Abertura + insight + curadoria | Semanal |

### Métricas de Newsletter

| Métrica | Saudável | Preocupante |
|---------|----------|-------------|
| Taxa de abertura | > 40% | < 25% |
| Taxa de clique | > 5% | < 2% |
| Taxa de resposta | > 1% | 0% |
| Crescimento mensal | > 10% | < 3% |
| Taxa de cancelamento | < 1% | > 3% |

## Estratégia de Podcast

### Formato Recomendado

```yaml
podcast:
  nome: "" # memorável, buscável, conectado ao movimento
  formato: "" # entrevista | solo | co-host | mesa redonda | narrativo
  duração: "" # 30-60 min (sweet spot)
  frequência: "" # semanal ou quinzenal
  estrutura:
    - intro: "" # 1-2 min, contexto do episódio
    - conteúdo: "" # 25-50 min, o coração
    - encerramento: "" # 3-5 min, resumo + CTA
```

### Tipos de Episódio

| Tipo | Descrição | Frequência Sugerida |
|------|-----------|-------------------|
| Entrevista | Conversa com expert ou membro | 2x mês |
| Solo | Reflexão ou framework do host | 1x mês |
| Case study | Análise detalhada de um caso | 1x mês |
| Comunidade | Perguntas de membros | Ocasional |
| Especial | Evento, lançamento, marco | Conforme necessidade |

### Escolha de Convidados

```yaml
convidado_ideal:
  relevância: "" # conectado ao tema do movimento
  audiência: "" # traz público complementar
  história: "" # tem experiência prática, não apenas teoria
  generosidade: "" # disposto a compartilhar insights reais
  diversidade: "" # variar perfis de convidados
```

### Métricas de Podcast

| Métrica | Saudável (nicho) | Bom |
|---------|-----------------|-----|
| Downloads por episódio | > 500 | > 2.000 |
| Taxa de conclusão | > 60% | > 75% |
| Reviews/ratings | > 4.5 estrelas | > 50 reviews |
| Crescimento mensal | > 10% | > 20% |
| Citações por convidados | > 50% | > 80% |

## Sinergia Podcast + Newsletter

```
PODCAST (gera conteúdo profundo)
    ↓
NEWSLETTER (distribui + contextualiza)
    ↓
REDES SOCIAIS (clips + destaques)
    ↓
COMUNIDADE (discussão + ação)
```

### Fluxo de Conteúdo

1. **Podcast grava na terça**
2. **Newsletter de quarta** destaca insight do episódio + curadoria
3. **Clips nas redes** quinta e sexta
4. **Discussão na comunidade** sobre o tema do episódio no fim de semana
5. **Feedback da comunidade** alimenta próximo episódio

## Monetização (quando aplicável)

| Modelo | Requisito | Exemplo |
|--------|-----------|---------|
| Patrocínio | > 2.000 downloads/episódio | Sponsor read no início |
| Membership | Comunidade engajada | Episódios exclusivos para membros |
| Produtos | Autoridade estabelecida | Cursos, mentorias, eventos |
| Afiliados | Audiência que confia | Recomendações genuínas |

## Integração

- Conteúdo usa `thesis-component` e `proof-component`
- Distribuição via `distribution-channel-component`
- Complementa `thought-leadership-strategy`
- Convidados podem ser formados via `community-champion-pattern`
- Métricas alimentam `memetic-spread-rubric`
