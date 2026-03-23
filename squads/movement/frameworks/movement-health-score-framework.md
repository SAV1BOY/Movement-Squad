---
id: movement-health-score-framework
name: "Movement Health Score Framework"
squad: movement
type: framework
category: core
version: "1.0"
tags: [metricas, saude, score, dashboard, monitoramento, kpis]
---

# Movement Health Score Framework

## Overview

O Movement Health Score Framework e o framework de medicao e diagnostico do Movement Squad. Ele define um score composto que avalia a saude geral do movimento em uma unica metrica (0-100), com 5 dimensoes ponderadas e thresholds claros de acao.

A tese central: movimentos que nao medem saude morrem de causas preveniveis. Metricas isoladas (seguidores, likes, revenue) contam historias parciais. Um score composto revela a saude real do organismo — e permite intervencao antes que o problema se torne irreversivel.

As 5 dimensoes:

1. **Adoption (Adocao):** Novos membros entrando no movimento
2. **Repetition (Repeticao):** Membros participando de rituais e voltando
3. **Conversation (Conversa):** Conteudo gerando dialogo real
4. **Defense (Defesa):** Membros defendendo o movimento espontaneamente
5. **Business (Negocio):** Impacto comercial (leads, trials, revenue)

Cada dimensao recebe um score de 0-100. O Health Score final e a media ponderada das 5 dimensoes. Os pesos variam conforme a fase do movimento.

---

## Principios

### 1. Score composto, diagnostico granular
O numero final (0-100) e util para visao rapida. Mas a acao vem do diagnostico por dimensao. "Health Score 65" nao diz o que fazer. "Adoption 80, Repetition 40" diz exatamente onde agir.

### 2. Thresholds claros, sem ambiguidade
Green (80-100): saudavel, manter cadencia. Yellow (50-79): atencao, investigar. Red (0-49): critico, intervencao imediata. Sem zona cinza.

### 3. Tendencia importa mais que ponto absoluto
Health Score 60 subindo e melhor que 75 descendo. Sempre analise tendencia de 4 semanas, nao apenas o numero da semana.

### 4. Meça o que importa, nao o que e facil
Followers e facil de medir mas nao indica saude. Defesa espontanea e dificil de medir mas e o melhor indicador de saude real. Invista em instrumentar o que importa.

### 5. Revisao semanal, acao mensal
Atualize o score toda semana (quinta-feira no RalphLoop Kaizen). Tome acoes corretivas mensalmente — reacoes semanais a flutuacoes normais criam ruido.

### 6. Pesos mudam por fase
Na fase de Birth, Adoption tem mais peso. Na Maturity, Defense e Business pesam mais. Ajuste os pesos conforme o movimento evolui.

---

## Protocolo / Processo

### Fase 1 — Configurar as 5 Dimensoes

#### Dimensao 1: ADOPTION (Adocao) — "O movimento esta atraindo gente nova?"

**Metricas componentes:**
| Metrica | Como medir | Peso interno |
|---|---|---|
| Novos membros da comunidade/semana | Contagem direta | 30% |
| Crescimento de seguidores/assinantes | Delta semanal | 25% |
| Taxa de conversao visitante→membro | Membros novos / visitantes unicos | 25% |
| Diversidade de fontes | % vindos de canais diferentes (nao concentrar em 1) | 20% |

**Como calcular o score (0-100):**
1. → Defina o baseline: media das ultimas 8 semanas para cada metrica
2. → Compare a semana atual com o baseline
3. → Score 100 = 2x o baseline ou mais
4. → Score 50 = exatamente no baseline
5. → Score 0 = zero absoluto ou queda >80% vs baseline
6. → Interpole linearmente entre os pontos

#### Dimensao 2: REPETITION (Repeticao) — "Quem entrou esta voltando?"

**Metricas componentes:**
| Metrica | Como medir | Peso interno |
|---|---|---|
| Participacao em rituais semanais | % dos membros ativos que participam | 35% |
| Retencao de 30 dias | % dos membros que continuam ativos apos 30 dias | 30% |
| Frequencia de visita/interacao | Media de dias ativos por membro por semana | 20% |
| Streak de participacao | % de membros com 4+ semanas consecutivas | 15% |

**Thresholds de referencia:**
- Participacao em rituais > 30% dos membros ativos = saudavel
- Retencao 30 dias > 40% = saudavel
- Media 3+ dias ativos/semana = saudavel

#### Dimensao 3: CONVERSATION (Conversa) — "O conteudo esta gerando dialogo real?"

**Metricas componentes:**
| Metrica | Como medir | Peso interno |
|---|---|---|
| Taxa conteudo→comentario | Comentarios / impressoes (por post) | 30% |
| Profundidade de conversa | Media de replies por thread de comentario | 25% |
| DMs e mensagens privadas recebidas | Contagem semanal | 20% |
| UGC gerado | Conteudo criado por membros em resposta ao nosso | 25% |

**Como distinguir conversa real de vanity:**
- Like = nao conta como conversa
- Comentario generico ("otimo post!") = conta 0.25
- Comentario com opiniao propria = conta 1
- Comentario que gera thread = conta 2
- DM com pergunta ou depoimento = conta 3

#### Dimensao 4: DEFENSE (Defesa) — "Membros defendem o movimento sem pedir?"

**Metricas componentes:**
| Metrica | Como medir | Peso interno |
|---|---|---|
| Instancias de defesa espontanea | Contagem manual de membros defendendo publicamente | 40% |
| Recomendacoes organicas | Membros indicando o movimento para outros | 30% |
| NPS da comunidade | Net Promoter Score trimestral | 20% |
| Sentiment ratio | Mencoes positivas / mencoes totais | 10% |

**Como rastrear defesa:**
1. → Monitorar mencoes ao movimento em redes sociais
2. → Registrar quando membros respondem a criticas sem ser pedido
3. → Contar recomendacoes organicas (DMs encaminhadas, tags de amigos)
4. → Pesquisa trimestral: "Voce recomendaria este movimento? De 0-10"

#### Dimensao 5: BUSINESS (Negocio) — "O movimento esta gerando impacto comercial?"

**Metricas componentes:**
| Metrica | Como medir | Peso interno |
|---|---|---|
| Leads qualificados do movimento | Contagem de MQLs com atribuicao ao movimento | 30% |
| Trials / signups do produto | Conversoes vindo de canais do movimento | 30% |
| Revenue atribuida | MRR/ARR de clientes que vieram do movimento | 25% |
| Pipeline gerado | Valor total de oportunidades com origem no movimento | 15% |

**Nota importante:** Na fase de Birth, Business pode ser zero — isso e normal. Nao force conversao antes de construir confianca.

---

### Fase 2 — Definir Pesos por Fase

| Dimensao | Birth | Growth | Maturity | Renewal |
|---|---|---|---|---|
| Adoption | 35% | 25% | 15% | 25% |
| Repetition | 20% | 30% | 25% | 20% |
| Conversation | 30% | 20% | 15% | 25% |
| Defense | 5% | 10% | 25% | 10% |
| Business | 10% | 15% | 20% | 20% |
| **Total** | 100% | 100% | 100% | 100% |

**Calculo do Health Score:**
```
Health Score = (Adoption * peso_adoption) + (Repetition * peso_repetition) +
              (Conversation * peso_conversation) + (Defense * peso_defense) +
              (Business * peso_business)
```

---

### Fase 3 — Definir Thresholds e Acoes

| Score | Status | Significado | Acao |
|---|---|---|---|
| 80-100 | GREEN | Saudavel | Manter cadencia. Buscar otimizacao incremental. Documentar o que esta funcionando. |
| 50-79 | YELLOW | Atencao | Investigar qual(is) dimensao(oes) estao abaixo de 50. Planejar intervencao para o mes seguinte. |
| 0-49 | RED | Critico | Intervencao imediata. Reuniao extraordinaria. Diagnosticar causa-raiz. Priorizar a dimensao mais critica. |

**Acoes por dimensao em RED:**

| Dimensao em RED | Diagnostico provavel | Acao imediata |
|---|---|---|
| Adoption | Conteudo nao esta alcancando gente nova | Revisar Distribution Trident. Testar novos canais. Investir em parcerias. |
| Repetition | Membros entram mas nao ficam | Revisar Ritual-Reward Loop. Melhorar onboarding. Investigar churn (entrevistar quem saiu). |
| Conversation | Conteudo e consumido mas nao gera dialogo | Revisar formato de conteudo. Fazer mais perguntas. Criar conteudo polemico (com cuidado). |
| Defense | Membros nao sentem ownership do movimento | Fortalecer Identity-Belief-Action Chain. Criar mais momentos de contribuicao. Aumentar reconhecimento. |
| Business | Movimento nao converte em negocio | Revisar Movement-to-Product Coupling. Verificar se ha pontos de conversao naturais. Se fase Birth, ignorar temporariamente. |

---

### Fase 4 — Implementar Dashboard

1. → Crie um dashboard semanal com:
   - Health Score geral (numero grande + cor + seta de tendencia)
   - Score por dimensao (5 numeros com cores individuais)
   - Grafico de tendencia das ultimas 12 semanas
   - Destaques: melhor e pior dimensao da semana
   - Acao recomendada baseada no diagnostico
2. → Atualize toda quinta-feira (dia de Medir no RalphLoop Kaizen)
3. → Compartilhe com todo o time + stakeholders relevantes
4. → Revisao profunda mensal com analise de tendencia

**Template de report semanal:**

```
=== MOVEMENT HEALTH SCORE — SEMANA [N] ===

SCORE GERAL: [XX/100] [GREEN/YELLOW/RED] [↑↓→ vs semana anterior]

DIMENSOES:
  Adoption:     [XX] [cor] [tendencia]
  Repetition:   [XX] [cor] [tendencia]
  Conversation: [XX] [cor] [tendencia]
  Defense:      [XX] [cor] [tendencia]
  Business:     [XX] [cor] [tendencia]

DESTAQUES:
  Melhor: [dimensao] — [motivo]
  Pior:   [dimensao] — [motivo]

ACAO RECOMENDADA:
  [1 frase sobre o que priorizar na proxima semana]
```

---

## Quando Usar

- Toda semana como parte do RalphLoop Kaizen (quinta-feira)
- Na reuniao mensal de revisao estrategica
- Para reportar saude do movimento a stakeholders/lideranca
- Na decisao de investir mais ou realocar recursos
- No diagnostico de problemas ("o que esta errado com nosso movimento?")

---

## Quando NAO Usar

- Nas primeiras 4 semanas do movimento (dados insuficientes para baseline)
- Como unica metrica para decisoes de investimento (combine com analise qualitativa)
- Para comparar movimentos diferentes (cada um tem seu baseline)
- Como ferramenta de cobranca/pressao sobre o time (e diagnostico, nao julgamento)

---

## Integracao

| Dimensao | Frameworks que alimentam |
|---|---|
| Adoption | distribution-trident, memetic-variation-selection, tension-to-movement-framework |
| Repetition | ritual-reward-loop, community-flywheel |
| Conversation | memetic-variation-selection, narrative-graph-framework |
| Defense | identity-belief-action-chain, community-flywheel, narrative-graph-framework |
| Business | movement-to-product-coupling |
| Geral | movement-engine-5-loop (Prova), ralphloop-kaizen (Medir) |

---

## Exemplo Aplicado

**Contexto:** Movimento de "Codigo Aberto para PMEs" — promover adocao de open-source por pequenas e medias empresas. Fase: Growth. Semana 24.

**Dados da semana:**
- Adoption: 45 novos membros Discord (baseline 35) + 680 novos seguidores (baseline 500) + conversao 3.2% (baseline 2.5%) + 4 fontes diferentes. Score: 78
- Repetition: Ritual semanal com 35% participacao (baseline 28%) + retencao 30d de 45% + media 3.2 dias ativos + 22% com streak 4+. Score: 72
- Conversation: Taxa comentario 2.1% (baseline 1.8%) + profundidade 3.4 replies (baseline 2.8) + 18 DMs (baseline 12) + 8 UGCs (baseline 5). Score: 81
- Defense: 4 instancias de defesa (baseline 2) + 12 recomendacoes (baseline 8) + NPS 72 + sentiment 85% positivo. Score: 70
- Business: 15 MQLs (baseline 10) + 8 trials (baseline 6) + R$4.200 MRR novo (baseline R$3.000) + R$18k pipeline. Score: 75

**Calculo (pesos Growth):**
```
Health Score = (78 * 0.25) + (72 * 0.30) + (81 * 0.20) + (70 * 0.10) + (75 * 0.15)
            = 19.5 + 21.6 + 16.2 + 7.0 + 11.25
            = 75.55 → 76
```

**Report:**
```
=== MOVEMENT HEALTH SCORE — SEMANA 24 ===

SCORE GERAL: 76/100 YELLOW ↑ (+3 vs semana anterior)

DIMENSOES:
  Adoption:     78 YELLOW ↑
  Repetition:   72 YELLOW ↑
  Conversation: 81 GREEN ↑
  Defense:      70 YELLOW →
  Business:     75 YELLOW ↑

DESTAQUES:
  Melhor: Conversation — Thread sobre migracao de Windows Server para Linux gerou recorde de engajamento
  Pior:   Defense — Crescendo mas ainda abaixo do ideal. Poucos membros defendem espontaneamente.

ACAO RECOMENDADA:
  Fortalecer Defense: criar programa de embaixadores e equipar comunidade com argumentos (Narrative Graph) para defender open-source em debates corporativos.
```

---

## Cross-references

- [[movement-engine-5-loop]] — Health Score e a entrega principal da etapa de Prova
- [[ralphloop-kaizen]] — Score atualizado na quinta-feira do ciclo Kaizen
- [[ritual-reward-loop]] — Participacao em rituais alimenta dimensao Repetition
- [[community-flywheel]] — Estagios do flywheel mapeiam para dimensoes do score
- [[distribution-trident]] — Performance de distribuicao alimenta Adoption
- [[identity-belief-action-chain]] — Forca da cadeia IBA se reflete em Defense
- [[movement-to-product-coupling]] — Coupling saudavel se reflete em Business
- [[narrative-graph-framework]] — Coerencia narrativa impacta Conversation e Defense
- [[movement-lifecycle-framework]] — Pesos do score mudam por fase do ciclo de vida
