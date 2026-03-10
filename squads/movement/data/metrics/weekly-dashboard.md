# Weekly Dashboard — Snapshot Semanal do Movimento

## Visão Geral

Template para o snapshot semanal de saúde do movimento. Preenchido toda
segunda-feira pelo Metrics Analyst e revisado pelo Chief of Movement.

## Template do Dashboard Semanal

```
═══════════════════════════════════════════════════════════
MOVEMENT DASHBOARD — Semana de [DD/MM/YYYY] a [DD/MM/YYYY]
═══════════════════════════════════════════════════════════

HEALTH SCORE: [XX]/100  (semana anterior: [XX])  [↑/↓/→] [+/-X]

─── COMPONENTES ───────────────────────────────────────────
Engajamento:   [XX]/100  [↑/↓/→]
Retenção:      [XX]/100  [↑/↓/→]
Propagação:    [XX]/100  [↑/↓/→]
Sentimento:    [XX]/100  [↑/↓/→]
Conversão:     [XX]/100  [↑/↓/→]

─── NÚMEROS DA SEMANA ─────────────────────────────────────
Membros ativos:          [XXX]  (anterior: [XXX])
Novos membros:           [XX]   (meta: [XX])
Participação rituais:    [XX%]  (anterior: [XX%])
Conteúdos publicados:    [XX]   (meta: [XX])
Compartilhamentos org.:  [XX]   (anterior: [XX])
Comentários substant.:   [XX]   (anterior: [XX])
Menções orgânicas:       [XX]   (anterior: [XX])
Leads gerados:           [XX]   (meta: [XX])

─── EXPERIMENTOS ATIVOS ───────────────────────────────────
[EXP-XXX] [Título] — Semana [X/Y] — Status: [no caminho/risco/bloqueado]
[EXP-XXX] [Título] — Semana [X/Y] — Status: [no caminho/risco/bloqueado]

─── DESTAQUES DA SEMANA ───────────────────────────────────
✓ [Algo que funcionou bem]
✓ [Outro destaque positivo]
✗ [Algo que não funcionou]
✗ [Outro ponto de atenção]

─── SINAIS RELEVANTES CAPTURADOS ──────────────────────────
1. [Descrição curta do sinal]
2. [Descrição curta do sinal]
3. [Descrição curta do sinal]

─── DECISÕES TOMADAS ──────────────────────────────────────
[DEC-XXX] [Decisão tomada e justificativa curta]

─── PRIORIDADES PRÓXIMA SEMANA ────────────────────────────
1. [Prioridade #1]
2. [Prioridade #2]
3. [Prioridade #3]

─── ALERTAS ───────────────────────────────────────────────
[Nenhum / Descrição do alerta e ação recomendada]

═══════════════════════════════════════════════════════════
```

## Como Preencher

1. **Calcule o Health Score** usando a fórmula do `movement-health-score.md`
2. **Colete números** das plataformas e comunidade
3. **Liste experimentos** ativos com status atualizado
4. **Destaque** máximo 3 positivos e 3 negativos da semana
5. **Registre sinais** — os 3 mais relevantes da semana
6. **Liste decisões** tomadas na semana (referência ao decision-log)
7. **Defina prioridades** para a próxima semana (máximo 3)
8. **Alertas** apenas se houver algo que precisa de atenção urgente

## Onde Armazenar

Dashboards preenchidos ficam neste diretório com nome:
`YYYY-WXX-weekly-dashboard.md` (ex: `2026-W10-weekly-dashboard.md`)

## Cadência

- **Preenchimento**: Segunda-feira até 12h
- **Revisão**: Segunda-feira 14h com Chief of Movement
- **Distribuição**: Segunda-feira 15h para todo o squad

## Responsável

**Metrics Analyst** preenche. **Chief of Movement** revisa e aprova.

## Regras

- Nunca pule uma semana — consistência é fundamental
- Se um número não estiver disponível, marque como "N/D" e explique
- Seja honesto — dashboards otimistas são métricas de vaidade
- Compare sempre com semana anterior para identificar tendências
