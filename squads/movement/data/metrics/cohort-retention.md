# Cohort Retention — Retenção por Coorte

## Visão Geral

Mede a retenção de membros do movimento agrupados pela semana/mês em que
entraram. Retenção por coorte é a métrica mais honesta de saúde de uma
comunidade — revela se as pessoas ficam, não apenas se chegam.

## Por que Medir por Coorte

Métricas agregadas de retenção escondem problemas. Se você cresce rápido,
novos membros mascaram a perda dos antigos. Análise por coorte mostra
a verdade nua e crua de cada grupo que entrou.

## Definição de "Retido"

Um membro é considerado retido em uma semana se realizou pelo menos UMA
das seguintes ações:
- Comentou em post ou thread na comunidade
- Participou de ritual semanal
- Compartilhou conteúdo do movimento
- Interagiu com outro membro publicamente
- Criou conteúdo original relacionado ao movimento

**Nota**: Apenas "visualizar" não conta como retenção. Queremos participação
ativa, não audiência passiva.

## Template de Tabela de Coorte

```
Coorte      | Sem 0 | Sem 1 | Sem 2 | Sem 4 | Sem 8 | Sem 12
────────────|───────|───────|───────|───────|───────|───────
Jan Sem 1   | 100%  |  72%  |  58%  |  45%  |  38%  |  32%
Jan Sem 2   | 100%  |  68%  |  55%  |  42%  |  35%  |  --
Jan Sem 3   | 100%  |  75%  |  62%  |  48%  |  --   |  --
Fev Sem 1   | 100%  |  70%  |  56%  |  43%  |  --   |  --
(...)
```

## Thresholds de Referência

| Período    | Meta Mínima | Bom       | Excelente |
|------------|-------------|-----------|-----------|
| Semana 1   | 60%         | 70%       | 80%+      |
| Semana 2   | 45%         | 55%       | 65%+      |
| Semana 4   | 30%         | 40%       | 50%+      |
| Semana 8   | 20%         | 30%       | 40%+      |
| Semana 12  | 15%         | 25%       | 35%+      |

## Análises Derivadas

### Curva de Estabilização
O ponto onde a retenção para de cair significativamente. Membros que passam
desse ponto tendem a ficar para sempre. Meta: estabilização até Semana 8.

### Comparação entre Coortes
Coortes com retenção significativamente diferente indicam que algo mudou —
investigue o que aconteceu naquela semana (novo ritual, conteúdo viral,
mudança de tom).

### Retenção por Canal de Origem
Membros vindos de diferentes fontes retêm de forma diferente. Isso informa
onde investir em aquisição.

## Cadência de Análise

- **Atualização**: Semanal (toda segunda com o dashboard)
- **Análise profunda**: Mensal (identificar tendências entre coortes)
- **Revisão de thresholds**: Trimestral

## Ações por Faixa

- **Abaixo da meta mínima**: Alerta imediato, investigar causa-raiz
- **Na meta mínima**: Aceitável, buscar otimizações
- **Bom**: Movimento saudável, focar em escalar
- **Excelente**: Estudar o que está funcionando para replicar

## Responsável

**Metrics Analyst** atualiza semanalmente. **Community Architect** investiga
quedas. **Chief of Movement** decide ações corretivas.

## Armadilhas Comuns

- Não comparar coortes de tamanhos muito diferentes (10 vs 100 membros)
- Sazonalidade afeta retenção — considerar no contexto
- Membros inativos que voltam devem ser contados na semana que voltaram
- Coortes recentes terão dados incompletos — paciência antes de concluir
