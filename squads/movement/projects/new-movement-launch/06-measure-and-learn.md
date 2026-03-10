---
id: nml-06
name: Medir e Aprender
squad: movement
type: project-phase
category: new-movement-launch
phase: 6-measure
tags:
  - métricas
  - aprendizado
  - análise
  - otimização
---

# 06 · Medir e Aprender

## Objetivo da Fase

Avaliar o desempenho do movimento contra as win conditions definidas na fase 00,
extrair aprendizados estruturados e definir otimizações. Medir não é só coletar
números — é interpretar sinais para tomar decisões melhores. Esta fase transforma
dados em inteligência acionável.

## Inputs

- Win conditions com métricas, targets e prazos (fase 00)
- Relatório de ativação com métricas por canal (fase 05)
- Dashboard de saúde da comunidade (fase 04)
- Banco de sinais e sentimento coletados durante ativação
- Feedback qualitativo da comunidade e parceiros
- Dados de cada plataforma e canal utilizado

## Processo

1. **Coleta e Consolidação de Dados** — Reunir dados de todas as fontes:
   analytics de plataformas, métricas de comunidade, dados de sentimento,
   feedback qualitativo. Centralizar em um único relatório.

2. **Avaliação contra Win Conditions** — Para cada win condition, comparar
   resultado vs. target. Classificar: superou / atingiu / quase / falhou.
   Para cada classificação, documentar hipóteses do porquê.

3. **Análise de Health Score** — Calcular health score do movimento usando
   `movement-health-score-calculator.md`. Avaliar dimensões: alcance,
   engajamento, sentimento, comunidade, viralidade orgânica.

4. **Análise de Cohort** — Usar `cohort-retention-calculator.md` para
   entender retenção por coorte. Quem entrou quando? Quem ficou? Quem
   saiu? Padrões de comportamento por coorte.

5. **Análise de Narrativa** — Usar `narrative-consistency-checker.md` para
   avaliar se a narrativa do movimento se manteve consistente durante a
   distribuição ou se sofreu distorção.

6. **Análise de Spread Memético** — Usar `memetic-spread-tracker.md` para
   mapear como a tese se espalhou. Quais variações surgiram? Quais
   elementos foram mais replicados?

7. **Sessão de Aprendizados** — Workshop de 3h com time completo para
   discutir resultados. Formato: o que funcionou, o que não funcionou,
   o que surpreendeu, o que faremos diferente.

8. **Relatório de Aprendizados** — Documentar findings em formato
   estruturado. Cada aprendizado deve ter: observação, hipótese,
   evidência e recomendação de ação.

9. **Plano de Otimização** — Listar 5-10 ações de otimização priorizadas
   por impacto e esforço. Cada ação com responsável e prazo.

## Outputs

- [ ] Relatório consolidado de métricas por canal e total
- [ ] Avaliação de cada win condition (superou/atingiu/quase/falhou)
- [ ] Health score do movimento calculado
- [ ] Análise de cohort e retenção
- [ ] Análise de consistência narrativa
- [ ] Mapa de spread memético
- [ ] Documento de aprendizados estruturados
- [ ] Plano de otimização priorizado

## Quality Gate

| Critério                          | Mínimo Aceitável                         |
|-----------------------------------|------------------------------------------|
| Win conditions avaliadas          | 100% das win conditions com status       |
| Dados consolidados                | Todas as fontes incluídas                |
| Aprendizados documentados         | Mínimo 10 aprendizados estruturados      |
| Plano de otimização               | Mínimo 5 ações priorizadas              |
| Sessão de aprendizados            | Time completo participou                 |
| Health score calculado            | Score geral + por dimensão               |

## Próxima Fase

→ `07-scale-or-pivot.md` — Com base nos resultados e aprendizados, tomar a
decisão estratégica: escalar o movimento, pivotar a abordagem ou descontinuar.

### Framework de Interpretação

- Métricas de vaidade (likes, views) ≠ métricas de movimento (ações, adesão)
- Crescimento lento mas saudável > crescimento rápido mas vazio
- Sentimento negativo estruturado é pior que baixo alcance
- Viralidade orgânica é o indicador mais forte de movimento real
- Retenção da comunidade é mais importante que aquisição

### Armadilhas de Medição

- Medir só o que é fácil de medir, ignorando o qualitativo
- Cherry-picking de dados para justificar narrativa pré-definida
- Comparar com benchmarks irrelevantes
- Não separar métricas de campanha de métricas de movimento
- Ignorar sinais fracos que contradizem a narrativa de sucesso
