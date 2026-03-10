---
id: measurement-layer
name: "Measurement Layer — Health Score e Métricas"
squad: movement
type: framework
category: stack-layer
version: "1.0"
tags: [métricas, health-score, cohorts, experimentos, atribuição, measurement]
---

# Measurement Layer — Health Score e Métricas

## Overview

O Measurement Layer responde à pergunta: **o movimento está vivo, saudável e crescendo?** Diferente de métricas de marketing tradicionais (impressões, cliques, conversões), um movimento exige métricas que capturem **saúde cultural, profundidade de engajamento e sustentabilidade**.

Três camadas de medição:
1. **Health Score**: índice composto que indica a saúde geral do movimento.
2. **Cohort Analysis**: entender como diferentes gerações de membros se comportam.
3. **Experiments & Attribution**: testar hipóteses e entender o que está causando resultados.

O Measurement Layer não julga — ilumina. Dados ruins não significam fracasso; significam aprendizado.

## Princípios Aplicáveis ao MMOS

1. **Meça profundidade, não só amplitude**. 1.000 membros que agem valem mais que 100.000 que observam.
2. **Health Score > vanity metrics**. Seguidores e impressões são input; saúde do movimento é output.
3. **Cohorts revelam tendências**. A saúde dos membros de janeiro é diferente dos de julho.
4. **Experimentar é medir**. Cada ativação deve ser um experimento com hipótese.
5. **Atribuição é humilde**. Em movimentos, causa e efeito são complexos. Aceite aproximações.

## Protocolo de Aplicação

### Passo 1 — Construir o Movement Health Score
O Health Score é composto por 5 dimensões:

| Dimensão              | O que mede                               | Peso  | Métrica                        |
|----------------------|------------------------------------------|-------|--------------------------------|
| Alcance              | Quantas pessoas o movimento toca          | 15%   | Impressões totais + menções    |
| Penetração           | Quantas pessoas aderem                    | 20%   | Novos membros/mês              |
| Engajamento          | Quão profundamente interagem              | 25%   | Ações por membro/mês           |
| Contágio             | Quanto se espalha organicamente           | 25%   | % de novos via referência      |
| Retenção             | Quantos permanecem ativos                 | 15%   | % ativos após 30/60/90 dias    |

Cálculo: média ponderada dos scores normalizados (0-100) de cada dimensão.

Interpretação:
- 80-100: movimento saudável e vibrante.
- 60-79: saudável com pontos de atenção.
- 40-59: sinais de enfraquecimento. Investigar.
- 0-39: crise. Ação urgente necessária.

### Passo 2 — Definir Métricas por Camada

| Camada          | Métricas-chave                                             |
|-----------------|-------------------------------------------------------------|
| Radar           | Nº de sinais capturados, tensões mapeadas                   |
| Thesis          | Score de ressonância da tese (teste com público)            |
| Creation        | Nº de artefatos criados, taxa de remix pela comunidade       |
| Activation      | CAC (custo por adesão), LTV do membro, canais ativos        |
| Measurement     | Acurácia de previsões, tempo para insight                   |
| Learning        | Nº de iterações, playbooks gerados                          |
| Scaling         | Taxa de crescimento sem diluição de engajamento             |
| Governance      | Incidentes éticos, tempo de resposta a crises               |

### Passo 3 — Implementar Cohort Analysis
Agrupe membros por data de entrada e compare:

| Cohort (mês entrada) | Membros | Ativos 30d | Ativos 60d | Ativos 90d | Evangelizadores |
|-----------------------|---------|------------|------------|------------|-----------------|
| Janeiro               | 200     | 85%        | 60%        | 45%        | 15%             |
| Fevereiro             | 350     | 80%        | 55%        | 40%        | 12%             |
| Março                 | 500     | 75%        | ?          | ?          | ?               |

Perguntas-chave:
- Cohorts mais recentes retêm melhor ou pior? (qualidade da aquisição)
- Quanto tempo leva para um membro se tornar evangelizador?
- Que ação do onboarding mais prediz retenção?

### Passo 4 — Framework de Experimentos
Cada ativação deve ser estruturada como experimento:

**Formato**: "Acreditamos que [hipótese]. Vamos testar fazendo [ação] com [grupo] durante [período] e medindo [indicador]. Sucesso = [critério]."

Exemplo: "Acreditamos que ritual semanal aumenta retenção. Vamos testar lançando 'Quinta do Movimento' (post semanal interativo) com o cohort de março durante 4 semanas e medindo retenção de 30 dias. Sucesso = retenção ≥ 70% (vs. 55% do baseline)."

Documentar: hipótese → ação → resultado → aprendizado → próximo passo.

### Passo 5 — Modelo de Atribuição
Dado que movimentos são sistemas complexos, use atribuição multicamada:

| Nível           | Pergunta                              | Método                      |
|-----------------|---------------------------------------|-----------------------------|
| Macro           | O movimento está crescendo?            | Health Score trend           |
| Canal           | Que canal gera mais membros?           | UTM + first touch            |
| Conteúdo        | Que tipo de conteúdo engaja mais?      | Engagement rate por formato  |
| Ação            | Que ação prediz retenção?              | Cohort + correlação          |
| Membro          | O membro está saudável?               | Score individual de atividade|

Aceite que atribuição em movimentos é aproximada. Triangule múltiplas fontes.

## Quando Usar / Não Usar

### Usar quando:
- Sempre. Measurement é contínuo.
- Reporting mensal para stakeholders.
- Decidindo onde investir mais ou menos.
- Diagnosticando problemas de saúde do movimento.

### Não usar quando:
- O movimento tem menos de 50 membros (dados insuficientes para análise robusta).
- Buscando "a métrica perfeita" — aceite imperfeição e itere.

## Agentes Responsáveis

| Agente    | Papel no Measurement Layer                                  |
|-----------|-------------------------------------------------------------|
| Impacto   | Líder da camada. Define métricas, constrói Health Score, reporta.|
| Ciclo     | Executa experimentos e coleta dados.                        |
| Chief     | Define metas e usa dados para decisão estratégica.          |
| Architect | Interpreta dados à luz da tese e propõe ajustes.            |

## Inputs e Outputs

**Inputs**:
- Dados de todos os canais (analytics, CRM, comunidade).
- Resultados de experimentos.
- Feedback qualitativo de membros.

**Outputs**:
- Movement Health Score (mensal).
- Relatório de cohorts (mensal).
- Log de experimentos com aprendizados.
- Recomendações de ação baseadas em dados.
- Dashboard acessível a todo o time.

## Exemplo Aplicado

### Caso: Health Score de movimento de inclusão tech

**Score do mês**:
- Alcance: 72/100 (crescimento de impressões estável).
- Penetração: 65/100 (novos membros desacelerando).
- Engajamento: 85/100 (membros ativos muito engajados).
- Contágio: 45/100 (poucos novos via referência — alerta).
- Retenção: 78/100 (boa retenção de 60 dias).

**Health Score composto**: 68/100 — saudável com ponto de atenção.

**Diagnóstico**: contágio baixo. Membros adoram o movimento mas não estão convidando outros. Hipótese: falta ferramenta de convite fácil e incentivo social.

**Experimento proposto**: criar botão "Convide um amigo" + badge "Recrutador" para quem trouxer 3+ pessoas. Testar por 30 dias. Meta: elevar contágio de 45 para 60.
