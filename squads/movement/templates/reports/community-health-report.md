---
id: tmpl-mov-rep-006
name: Relatório de Saúde da Comunidade
squad: movement
type: template
category: reports
tags: [comunidade, saúde, engajamento, retenção, moderação]
---

# Relatório de Saúde da Comunidade

## Instruções de Uso

Este relatório avalia a saúde da comunidade além de métricas de vaidade. Analisa qualidade
das interações, diversidade de vozes, carga de moderação e sentimento geral. Uma comunidade
pode crescer em números e morrer em alma — este relatório detecta isso.

**Quando usar:** Mensal, com check-in quinzenal.
**Quem preenche:** Community manager.
**Para quem:** Líder do movimento + squad.

---

## Template

### Relatório — {{mes_ano}}

**Comunidade:** {{nome_comunidade}}
**Plataforma:** {{plataforma}}
**Autor:** {{autor}}
**Status geral:** {{status}}

---

### 1. Números da Comunidade

| Métrica | Mês anterior | Este mês | Var. | Meta |
|---------|-------------|----------|------|------|
| Membros totais | {{total_ant}} | {{total_atual}} | {{var_total}} | {{meta_total}} |
| Novos membros | {{novos_ant}} | {{novos_atual}} | {{var_novos}} | {{meta_novos}} |
| Saídas/churn | {{saidas_ant}} | {{saidas_atual}} | {{var_saidas}} | — |
| Membros ativos | {{ativos_ant}} | {{ativos_atual}} | {{var_ativos}} | {{meta_ativos}} |

### 2. Engajamento

| Métrica | Valor | Benchmark | Avaliação |
|---------|-------|-----------|-----------|
| Mensagens/dia | {{msg_dia}} | {{bench_msg}} | {{aval_msg}} |
| Membros que postam (%) | {{pct_post}} | {{bench_post}} | {{aval_post}} |
| Reações/mensagem | {{reacoes}} | {{bench_reac}} | {{aval_reac}} |
| Threads com resposta (%) | {{threads}} | {{bench_threads}} | {{aval_threads}} |
| Tempo médio de permanência | {{tempo_perm}} | {{bench_perm}} | {{aval_perm}} |

### 3. Diversidade de Vozes

**Top 10% posters respondem por:** {{pct_top10}} das mensagens
**Concentração de voz:** {{concentracao — saudável/preocupante}}
**Novas vozes este mês:** {{novas_vozes}}
**Ações para diversificar:** {{acoes_diversidade}}

### 4. Retenção

| Cohort | Dia 1 | Dia 7 | Dia 30 | Dia 60 |
|--------|-------|-------|--------|--------|
| {{cohort_1}} | {{d1_c1}} | {{d7_c1}} | {{d30_c1}} | {{d60_c1}} |
| {{cohort_2}} | {{d1_c2}} | {{d7_c2}} | {{d30_c2}} | {{d60_c2}} |

### 5. Moderação

| Métrica | Valor | Var. | Observação |
|---------|-------|------|------------|
| Infrações reportadas | {{infracoes}} | {{var_infr}} | {{obs_infr}} |
| Ações de moderação | {{acoes_mod}} | {{var_mod}} | {{obs_mod}} |
| Bans | {{bans}} | {{var_bans}} | {{obs_bans}} |
| Tempo médio de resposta | {{tempo_mod}} | {{var_tempo}} | {{obs_tempo}} |

**Temas de moderação recorrentes:** {{temas_moderacao}}

### 6. Sentimento

**Sentimento geral:** {{sentimento_geral — positivo/neutro/negativo}}
**Temas positivos:** {{temas_positivos}}
**Temas negativos:** {{temas_negativos}}
**Feedback notável:** {{feedback_notavel}}

### 7. Rituais e Eventos

| Ritual/Evento | Participação | Var. | Feedback |
|---------------|-------------|------|----------|
| {{ritual_1}} | {{part_1}} | {{var_r1}} | {{feed_1}} |
| {{ritual_2}} | {{part_2}} | {{var_r2}} | {{feed_2}} |

### 8. Recomendações

1. {{rec_1}}
2. {{rec_2}}
3. {{rec_3}}

---

## Exemplo Preenchido

### Números
| Métrica | Anterior | Atual | Var. |
|---------|----------|-------|------|
| Membros | 3.200 | 4.800 | +50% |
| Ativos | 960 | 1.680 | +75% |
| Churn | 120 | 95 | -21% |

### Diversidade
**Top 10%:** 45% das mensagens (benchmark: 30-40%). Levemente concentrado.
**Novas vozes:** 89 membros postaram pela primeira vez.
**Ação:** Criar "destaque do novato" semanal para estimular novas vozes.

### Sentimento
**Geral:** Fortemente positivo. Membros expressam orgulho de pertencer.
**Negativo:** Frustração com velocidade de resposta dos mods (justificado pelo volume).

---

## Dicas

- **Diversidade de vozes é crítica.** Se poucos dominam, a comunidade vira clube.
- **Churn importa mais que crescimento.** Entenda POR QUE as pessoas saem.
- **Sentimento qualitativo > métricas quantitativas.** Leia as conversas, não só os números.
- **Moderação é termômetro.** Aumento de infrações pode indicar problema estrutural.
- **Retenção por cohort.** Uma média geral esconde variações importantes entre grupos.
