---
id: community-health-rubric
name: "Rubrica de Saúde da Comunidade"
squad: movement
type: utility
category: lib/utilities
version: 1.0.0
tags: [rubrica, comunidade, saúde, engajamento, utilidade]
---

# Rubrica de Saúde da Comunidade

## Propósito

Ferramenta para medir a saúde de uma comunidade de movimento em suas dimensões vitais. Diagnóstico precoce de problemas permite intervenção antes que se tornem crises.

## Dimensões de Saúde

### 1. Atividade (0-10)

| Pontuação | Descrição |
|-----------|-----------|
| 0-2 | Comunidade inativa — poucos posts por semana |
| 3-4 | Atividade esporádica — depende de poucos |
| 5-6 | Atividade regular mas concentrada em horários |
| 7-8 | Atividade consistente com múltiplos contribuidores |
| 9-10 | Atividade constante — comunidade nunca dorme |

**Métricas:** mensagens/dia, posts/semana, eventos/mês

### 2. Diversidade de Participação (0-10)

| Pontuação | Descrição |
|-----------|-----------|
| 0-2 | 1-2 pessoas geram 90%+ do conteúdo |
| 3-4 | 5-10 pessoas geram 80% do conteúdo |
| 5-6 | 20%+ dos membros contribuem mensalmente |
| 7-8 | 40%+ dos membros contribuem mensalmente |
| 9-10 | Contribuição distribuída — não depende de ninguém |

**Métrica:** coeficiente de Gini da participação (quanto menor, mais distribuído)

### 3. Retenção (0-10)

| Pontuação | Descrição |
|-----------|-----------|
| 0-2 | < 20% dos membros ainda ativos após 90 dias |
| 3-4 | 20-35% ativos após 90 dias |
| 5-6 | 35-50% ativos após 90 dias |
| 7-8 | 50-65% ativos após 90 dias |
| 9-10 | > 65% ativos após 90 dias |

### 4. Qualidade das Interações (0-10)

| Pontuação | Descrição |
|-----------|-----------|
| 0-2 | Interações tóxicas ou inexistentes |
| 3-4 | Interações superficiais (emojis, "legal") |
| 5-6 | Conversas relevantes mas sem profundidade |
| 7-8 | Conversas profundas, membros se ajudam |
| 9-10 | Membros formam relações reais e colaboram fora da plataforma |

### 5. Crescimento Orgânico (0-10)

| Pontuação | Descrição |
|-----------|-----------|
| 0-2 | Sem novos membros ou apenas por convite direto |
| 3-4 | Crescimento lento e dependente de promoção |
| 5-6 | Crescimento moderado com mix orgânico/pago |
| 7-8 | Maioria do crescimento é orgânico (referência) |
| 9-10 | Crescimento viral — membros trazem membros ativamente |

## Classificação

| Total | Saúde | Ação |
|-------|-------|------|
| 0-10 | Crítica | Intervenção urgente ou encerramento |
| 11-20 | Fraca | Diagnosticar causa raiz e agir |
| 21-30 | Estável | Investir na dimensão mais fraca |
| 31-40 | Saudável | Manter e otimizar |
| 41-50 | Vibrante | Escalar com cuidado |

## Sinais de Alerta Precoce

| Sinal | O que indica | Ação |
|-------|-------------|------|
| Tempo de resposta aumentando | Desengajamento | Ativar campeões |
| Mesmas pessoas sempre | Dependência | Diversificar participação |
| Aumento de conflitos | Tensão interna | Mediar e revisar regras |
| Queda de novos membros | Perda de relevância | Revisar proposta de valor |
| Campeões saindo | Burnout ou desalinhamento | Conversa individual urgente |

## Frequência de Medição

| Métrica | Frequência | Responsável |
|---------|-----------|-------------|
| Atividade | Semanal | Automatizado |
| Diversidade | Mensal | Líder de comunidade |
| Retenção | Mensal | Automatizado |
| Qualidade | Trimestral | Amostragem manual |
| Crescimento | Mensal | Automatizado |

## Template de Avaliação

```yaml
saúde_comunidade:
  data: YYYY-MM-DD
  comunidade: ""
  membros_totais: 0
  membros_ativos_30d: 0
  pontuações:
    atividade: 0
    diversidade: 0
    retenção: 0
    qualidade: 0
    crescimento: 0
  total: 0
  saúde: ""
  alerta_principal: ""
  ação_prioritária: ""
```

## Integração

- Alimentada por métricas do `community-role-component`
- Resultado alimenta `movement-scoring-rubric` (dimensão Comunidade)
- Alertas ativam `crisis-to-opportunity-pattern` quando necessário
- Diagnóstico orienta `community-champion-pattern`
