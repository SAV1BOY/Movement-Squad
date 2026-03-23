# Movement Health Score — Score Composto de Saúde do Movimento

## Visão Geral

O Movement Health Score (MHS) é a métrica composta que representa a saúde geral
do movimento em um único número de 0 a 100. Não é uma métrica de vaidade — cada
componente é acionável e conectado a decisões específicas.

## Fórmula

```
MHS = (Engajamento × 0.25) + (Retenção × 0.25) + (Propagação × 0.20) +
      (Sentimento × 0.15) + (Conversão × 0.15)
```

## Componentes e Pesos

### 1. Engajamento (25%)
- **O que mede**: Profundidade das interações, não volume
- **Cálculo**: Média ponderada de comentários substantivos, participação em rituais e co-criações
- **Fonte de dados**: Plataformas sociais, comunidade, eventos
- **Acionável**: Se cair, investigar quais rituais perderam tração

### 2. Retenção (25%)
- **O que mede**: Pessoas que voltam semana após semana
- **Cálculo**: % de membros ativos que interagiram nas últimas 2 semanas
- **Fonte de dados**: Comunidade, rituais semanais
- **Acionável**: Se cair, revisar proposta de valor e frequência de rituais

### 3. Propagação (20%)
- **O que mede**: O movimento se espalha organicamente?
- **Cálculo**: Novos membros vindos de indicação + compartilhamentos orgânicos
- **Fonte de dados**: Tracking de referral, menções orgânicas
- **Acionável**: Se cair, revisar incentivos de sharing e qualidade do conteúdo

### 4. Sentimento (15%)
- **O que mede**: Como as pessoas se sentem sobre o movimento
- **Cálculo**: Análise de sentimento de comentários e menções
- **Fonte de dados**: Social listening, pesquisas periódicas
- **Acionável**: Se cair, investigar contra-narrativas ou fadiga de mensagem

### 5. Conversão (15%)
- **O que mede**: O movimento gera resultado de negócio?
- **Cálculo**: Leads, trials, demos originados do movimento
- **Fonte de dados**: CRM, attribution tracking
- **Acionável**: Se cair, revisar CTAs e funil de conversão

## Thresholds

| Faixa       | Score   | Interpretação                          | Ação                              |
|-------------|---------|----------------------------------------|-----------------------------------|
| Excelente   | 80-100  | Movimento saudável e crescendo         | Manter e escalar                  |
| Bom         | 65-79   | Funcionando com espaço para melhorar   | Otimizar componentes mais fracos  |
| Atenção     | 50-64   | Sinais de problema em alguns eixos     | Diagnóstico urgente               |
| Crítico     | 30-49   | Movimento perdendo força               | Revisão estratégica completa      |
| Emergência  | 0-29    | Risco de colapso                       | Parar tudo e reconstruir          |

## Cadência de Medição

- **Cálculo**: Semanal (toda segunda-feira)
- **Report**: Semanal no dashboard
- **Revisão profunda**: Mensal com o Chief of Movement
- **Histórico**: Mantido no `maturity-score-history.md`

## Responsável

O **Metrics Analyst** calcula semanalmente. O **Chief of Movement** revisa e
decide ações quando o score cai abaixo de 65.

## Limitações Conhecidas

- Sentimento é a métrica mais subjetiva — interpretar com cuidado
- Conversão pode ser afetada por fatores externos ao movimento
- Score composto pode mascarar problemas em componentes individuais
- Sempre analisar componentes individualmente além do score composto

## Evolução

Este score deve evoluir conforme o movimento amadurece. Revisar pesos e
componentes trimestralmente. Documentar mudanças no changelog.
