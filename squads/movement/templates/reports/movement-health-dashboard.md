---
id: tmpl-mov-rep-004
name: Dashboard de Saúde do Movimento
squad: movement
type: template
category: reports
tags: [dashboard, saúde, métricas, monitoramento, indicadores]
---

# Dashboard de Saúde do Movimento

## Instruções de Uso

O Dashboard de Saúde é o painel de controle que mostra, em uma página, se o movimento
está saudável. Não substitui relatórios detalhados — é o check rápido que responde
"precisamos nos preocupar com algo?" Atualize semanalmente.

**Quando usar:** Referência contínua, atualizada toda segunda-feira.
**Quem mantém:** Analista do movimento.
**Para quem:** Toda a equipe (visível e acessível).

---

## Template

### Dashboard — Semana {{semana}} / {{ano}}

**Movimento:** {{nome_movimento}}
**Atualizado em:** {{data_atualizacao}}
**Responsável:** {{responsavel}}

---

### 1. Status Geral

| Indicador | Status | Score | Tendência |
|-----------|--------|-------|-----------|
| Saúde geral | {{status_geral}} | {{score_geral}}/10 | {{tend_geral}} |

### 2. Indicadores Vitais

| Indicador | Valor atual | Meta | Status | Tendência (4 sem) |
|-----------|------------|------|--------|-------------------|
| Membros totais | {{membros}} | {{meta_membros}} | {{st_membros}} | {{tend_membros}} |
| Membros ativos (MAU) | {{mau}} | {{meta_mau}} | {{st_mau}} | {{tend_mau}} |
| Taxa de retenção 30d | {{retencao}} | {{meta_retencao}} | {{st_retencao}} | {{tend_retencao}} |
| NPS/Sentimento | {{nps}} | {{meta_nps}} | {{st_nps}} | {{tend_nps}} |
| UGC/semana | {{ugc}} | {{meta_ugc}} | {{st_ugc}} | {{tend_ugc}} |
| Taxa de referral | {{referral}} | {{meta_referral}} | {{st_referral}} | {{tend_referral}} |

### 3. Engajamento

| Canal | Alcance | Engajamento | Var. semanal |
|-------|---------|-------------|-------------|
| {{canal_1}} | {{alc_1}} | {{eng_1}} | {{var_1}} |
| {{canal_2}} | {{alc_2}} | {{eng_2}} | {{var_2}} |
| {{canal_3}} | {{alc_3}} | {{eng_3}} | {{var_3}} |

### 4. Comunidade

| Métrica | Valor | Benchmark | Status |
|---------|-------|-----------|--------|
| Mensagens/dia | {{msg_dia}} | {{bench_msg}} | {{st_msg}} |
| Membros que postam (%) | {{pct_postam}} | {{bench_post}} | {{st_post}} |
| Tempo médio de resposta | {{tempo_resp}} | {{bench_resp}} | {{st_resp}} |
| Novos membros/semana | {{novos_sem}} | {{bench_novos}} | {{st_novos}} |

### 5. Narrativa e Sentimento

**Sentimento predominante:** {{sentimento}}
**Temas emergentes:** {{temas}}
**Sinais de alerta:** {{alertas}}

### 6. Alertas

| Alerta | Nível | Descrição | Ação necessária |
|--------|-------|-----------|----------------|
| {{alerta_1}} | {{nivel_1}} | {{desc_1}} | {{acao_1}} |
| {{alerta_2}} | {{nivel_2}} | {{desc_2}} | {{acao_2}} |

### 7. Histórico (Últimas 8 Semanas)

| Semana | Score geral | Membros | MAU | NPS |
|--------|------------|---------|-----|-----|
| S{{s1}} | {{sc_1}} | {{m_1}} | {{mau_1}} | {{nps_1}} |
| S{{s2}} | {{sc_2}} | {{m_2}} | {{mau_2}} | {{nps_2}} |
| S{{s3}} | {{sc_3}} | {{m_3}} | {{mau_3}} | {{nps_3}} |
| S{{s4}} | {{sc_4}} | {{m_4}} | {{mau_4}} | {{nps_4}} |

---

## Exemplo Preenchido

### Status Geral
| Indicador | Status | Score | Tendência |
|-----------|--------|-------|-----------|
| Saúde geral | 🟢 Saudável | 8/10 | Subindo |

### Vitais
| Indicador | Atual | Meta | Status | Tendência |
|-----------|-------|------|--------|-----------|
| Membros | 4.800 | 5.000 | 🟡 | Subindo |
| MAU | 2.100 | 2.000 | 🟢 | Subindo |
| Retenção 30d | 68% | 60% | 🟢 | Estável |
| NPS | 72 | 70 | 🟢 | Subindo |
| UGC/semana | 450 | 300 | 🟢 | Subindo |

### Alertas
| Alerta | Nível | Descrição | Ação |
|--------|-------|-----------|------|
| Moderação | 🟡 Atenção | Volume 2x acima da capacidade | Recrutar mods |

---

## Dicas

- **Uma página, sempre.** Se não cabe em uma página, tem informação demais.
- **Cores e ícones claros.** Verde/amarelo/vermelho são universais. Use-os.
- **Tendência > Valor absoluto.** A direção importa mais que o número.
- **Atualize religiosamente.** Dashboard desatualizado é pior que não ter dashboard.
- **Defina thresholds antes.** O que faz um indicador ficar amarelo ou vermelho?
