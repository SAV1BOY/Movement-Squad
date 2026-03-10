---
id: impact-cohort-analysis
name: "Cohort Analysis"
squad: movement
type: framework
category: agent-specific
agent: impact
version: "1.0"
tags: [cohort, análise, retenção, segmentação, impact]
---

# Cohort Analysis

## Overview

Nem todos os membros de um movimento são iguais. Quem entrou pelo viral do TikTok se comporta diferente de quem veio pela newsletter. Quem entrou em janeiro pode ter retenção diferente de quem entrou em março. Este framework ensina o agente de Impact a analisar o movimento por cohorts — grupos de pessoas que compartilham uma característica de entrada — para entender padrões de retenção, ativação e valor ao longo do tempo.

Cohort analysis revela o que métricas agregadas escondem.

## Princípios

1. **Agregado mente, cohort revela** — A média total pode estar estável enquanto cohorts antigos retêm mal e novos compensam. Sem cohort, você não vê a erosão.

2. **Data de entrada é o primeiro corte** — O momento em que alguém entra define muito do comportamento futuro. Comece sempre por cohort temporal.

3. **Fonte de aquisição é o segundo** — De onde a pessoa veio (canal, campanha, viral) influencia profundamente retenção e engajamento.

4. **Ação é o terceiro** — O que a pessoa fez nos primeiros 7 dias é o melhor preditor de retenção de longo prazo.

5. **Padrão visual** — Cohort charts (tabelas de retenção) contam histórias que números soltos não contam. Aprenda a ler o mapa de calor.

6. **Ação imediata** — Análise de cohort sem ação é academia. Cada insight deve gerar uma mudança no movimento.

## Protocolo

### Passo 1: Definir os Cohorts

1. Escolher a dimensão de agrupamento:

**Cohort temporal (obrigatório):**
- Agrupar por semana ou mês de entrada.
- Ex: "Cohort Jan/26", "Cohort Fev/26", "Cohort Semana 10".

**Cohort por fonte (recomendado):**
- Agrupar por canal de aquisição.
- Ex: "Cohort Instagram", "Cohort Newsletter", "Cohort Viral TikTok Mar/26".

**Cohort por comportamento (avançado):**
- Agrupar por ação nos primeiros 7 dias.
- Ex: "Fez ritual de entrada", "Apenas seguiu", "Comentou no manifesto".

2. Começar com cohort temporal. Adicionar as outras dimensões conforme maturidade de dados.

### Passo 2: Definir Métricas por Cohort

3. Para cada cohort, medir:

**Retenção:** % de pessoas do cohort ativas após N dias/semanas.
- Período: D7 (7 dias), D14, D30, D60, D90.
- Ativo = definir ação mínima (comentou, postou, acessou, usou hashtag).

**Ativação:** % que completou ação-chave nos primeiros N dias.
- Ações-chave: ritual de entrada, primeiro UGC, entrou na comunidade.
- Medir D1, D3, D7.

**Valor:** contribuição acumulada por cohort.
- UGC gerado, membros indicados, conversões ao negócio.
- Medir cumulativamente por mês.

### Passo 3: Construir a Tabela de Retenção

4. Formato padrão da tabela:

| Cohort | Tamanho | Semana 1 | Semana 2 | Semana 3 | Semana 4 | Semana 8 |
|--------|---------|----------|----------|----------|----------|----------|
| Jan S1 | 120 | 100% | 45% | 32% | 28% | 18% |
| Jan S2 | 150 | 100% | 52% | 40% | 35% | 22% |
| Jan S3 | 200 | 100% | 48% | 35% | 30% | 20% |
| Fev S1 | 180 | 100% | 55% | 42% | 38% | - |

5. Colorir: verde (>40%), amarelo (20-40%), vermelho (<20%).
6. Ler padrões: a retenção melhora com o tempo (cohorts mais novos retêm melhor)? Ou piora?

### Passo 4: Analisar Padrões

7. Perguntas-chave:
   - **A retenção melhora ao longo do tempo?** Se sim, o movimento está evoluindo. Se não, algo está degradando.
   - **Qual cohort retém melhor?** O que esse cohort tem de especial? (Fonte? Evento? Artefato que encontrou primeiro?)
   - **Onde está a maior queda?** Geralmente entre semana 1 e 2 (o "momento da verdade"). O que acontece nesse período?
   - **Cohorts de fontes diferentes se comportam diferente?** Se sim, qual fonte traz membros de maior qualidade?

8. Análise de ativação:
   - Pessoas que completaram o ritual de entrada nos primeiros 7 dias retêm X% melhor?
   - Qual é a "ação mágica" que prediz retenção de longo prazo?

### Passo 5: Gerar Insights Acionáveis

9. Para cada padrão, gerar recomendação:

**Padrão:** Cohorts do TikTok retêm 50% menos que os de newsletter.
**Insight:** O público do TikTok entra por curiosidade mas não é o público central.
**Ação:** Não parar de postar no TikTok (aquisição), mas criar ponte mais forte para newsletter (retenção).

**Padrão:** Membros que fazem ritual de entrada nos primeiros 3 dias retêm 3x mais.
**Insight:** O ritual de entrada é o momento de ativação crítico.
**Ação:** Investir em onboarding que incentive ritual de entrada imediato. Enviar lembrete D1 e D3.

**Padrão:** A retenção D30 caiu nos últimos 3 cohorts.
**Insight:** Algo mudou no movimento que afeta a experiência de longo prazo.
**Ação:** Investigar: conteúdo repetitivo? Comunidade menos ativa? Ritual perdendo energia?

### Passo 6: Cadência de Análise

10. **Semanal:** Atualizar tabela de retenção com novos dados. Flaggar anomalias.
11. **Mensal:** Análise profunda com comparação de cohorts. Apresentar à squad.
12. **Trimestral:** Revisão de fontes de aquisição por qualidade. Recomendar mudanças ao Chief.

## Quando Usar

- A partir do mês 2 do movimento (antes disso não há cohorts para comparar).
- Quando a retenção geral parece estável mas o crescimento desacelera.
- Para avaliar qualidade de diferentes fontes de aquisição.
- Para identificar a "ação mágica" que prediz retenção.

## Quando Não Usar

- Se o movimento tem menos de 100 membros — amostra muito pequena.
- Para decisões de conteúdo diário — use métricas de input.
- Se não há tracking mínimo de comportamento por pessoa.

## Integração

- **Chief** usa insights de cohort para decisões de portfólio e investimento por canal.
- **Architect** usa os padrões para otimizar loops e onboarding.
- **Manifestor** ajusta artefatos de entrada baseado em dados de ativação.
- **Cycle** identifica se timing de entrada afeta retenção.
- **Phenomenology** investiga qualitativamente por que cohorts se comportam diferente.
- **Identity** verifica se a narrativa está ressoando igualmente em todos os cohorts.

## Exemplo Aplicado

**Contexto:** Análise de cohort do movimento #NinguémMeEnsinou, mês 4.

**Tabela de retenção (por fonte):**

| Fonte | N | D7 | D14 | D30 | D60 |
|-------|---|-----|------|------|------|
| Instagram orgânico | 800 | 52% | 38% | 25% | 18% |
| TikTok viral | 2.200 | 30% | 15% | 8% | 4% |
| Newsletter | 300 | 72% | 60% | 48% | 38% |
| Indicação de champion | 150 | 68% | 55% | 45% | 35% |

**Insights:**
1. TikTok traz volume (2.200) mas retenção péssima (4% D60). Custo por membro retido é alto.
2. Newsletter e indicação de champion retêm 8-10x melhor que TikTok.
3. Ação mágica: membros que postaram com a hashtag nos primeiros 7 dias (ritual de entrada) retêm 3.5x mais independente da fonte.

**Ações recomendadas:**
1. Manter TikTok como funil de topo, mas criar ponte imediata para newsletter.
2. Investir em programa de indicação por champions (melhor qualidade).
3. Criar onboarding automatizado que incentive ritual de entrada em D1.
4. Enviar push/DM D3 para quem não fez o ritual ainda.
