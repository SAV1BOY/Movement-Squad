---
id: ma-00
name: Escopo da Auditoria
squad: movement
type: project-phase
category: movement-audit
phase: 0-scope
tags:
  - auditoria
  - escopo
  - planejamento
  - diagnóstico
---

# 00 · Escopo da Auditoria

## Objetivo da Fase

Definir o escopo, metodologia e critérios da auditoria do movimento. Auditoria
sem escopo definido se perde em detalhes irrelevantes. Esta fase garante que
saberemos exatamente o que avaliar, como avaliar e que padrão usar para julgar.

## Inputs

- Briefing de quem solicitou a auditoria (interno ou externo)
- Documentação existente do movimento (tese, identidade, métricas)
- Acesso a plataformas e dados do movimento
- Timeline e budget para a auditoria
- Auditorias anteriores (se existirem)
- Contexto: por que esta auditoria agora?

## Processo

1. **Entendimento do Contexto** — Por que a auditoria está sendo feita?
   Possíveis gatilhos: revisão periódica, sinais de problema, mudança
   de liderança, preparação para escala, due diligence, curiosidade
   estratégica. O gatilho influencia o foco.

2. **Definição de Dimensões** — Selecionar quais dimensões serão avaliadas:
   - Saúde geral do movimento (health score)
   - Consistência narrativa
   - Saúde da comunidade
   - Impacto cultural e de negócio
   - Eficiência operacional
   Nem toda auditoria precisa cobrir tudo.

3. **Critérios de Avaliação** — Para cada dimensão, definir escala e
   critérios. Exemplo: 1-10 com descritores para cada nota. Usar
   benchmarks quando disponíveis.

4. **Fontes de Dados** — Mapear todas as fontes de dados disponíveis:
   analytics de plataformas, dados de comunidade, pesquisas, entrevistas,
   conteúdo publicado, documentos internos, feedback coletado.

5. **Metodologia** — Definir mix de análise quantitativa e qualitativa:
   - Quanti: métricas de plataformas, health score, cohort analysis
   - Quali: entrevistas, análise de conteúdo, observação participante
   Usar scripts existentes como ferramentas.

6. **Stakeholders da Auditoria** — Quem participa? Quem é entrevistado?
   Quem recebe o relatório? Definir RACI da auditoria.

7. **Timeline da Auditoria** — Cronograma fase a fase: escopo (1 semana),
   coleta de dados (1-2 semanas), análise (1 semana), relatório (1 semana),
   apresentação (1 dia). Total típico: 4-6 semanas.

8. **Documento de Escopo** — Consolidar tudo em documento que funciona
   como contrato: o que será avaliado, como, por quem, quando e para
   quem. Sign-off antes de iniciar.

## Outputs

- [ ] Contexto e gatilho da auditoria documentados
- [ ] Dimensões selecionadas com justificativa
- [ ] Critérios de avaliação por dimensão
- [ ] Mapa de fontes de dados disponíveis
- [ ] Metodologia definida (quanti + quali)
- [ ] RACI da auditoria
- [ ] Timeline com milestones
- [ ] Documento de escopo com sign-off

## Quality Gate

| Critério                          | Mínimo Aceitável                         |
|-----------------------------------|------------------------------------------|
| Escopo claro                      | Dimensões e critérios definidos          |
| Fontes de dados mapeadas          | Todas as fontes com acesso confirmado    |
| Metodologia adequada              | Mix quanti + quali                       |
| Timeline realista                 | Validada com quem executa                |
| Sign-off obtido                   | Stakeholders concordam com escopo        |
| Ferramentas preparadas            | Scripts e templates prontos para uso     |

## Próxima Fase

→ `01-health-assessment.md` — Iniciar avaliação de saúde geral do
movimento usando métricas quantitativas e health score.

### Tipos de Auditoria

**Auditoria Completa:** Todas as dimensões, profundidade máxima.
Para: decisões estratégicas importantes, pivot, escala.

**Auditoria de Saúde:** Foco em health score e métricas-chave.
Para: check-ups regulares, monitoramento contínuo.

**Auditoria Temática:** Uma dimensão em profundidade.
Para: investigar problema específico, preparar mudança pontual.

**Auditoria Rápida:** Overview de alto nível em 1-2 semanas.
Para: onboarding de novo time, visão geral para stakeholders.

### Scripts Utilizados na Auditoria

- `movement-health-score-calculator.md` — Score geral
- `community-health-audit.md` — Saúde da comunidade
- `narrative-consistency-checker.md` — Consistência narrativa
- `sentiment-analysis-skeleton.md` — Sentimento
- `cohort-retention-calculator.md` — Retenção por coorte
- `champion-impact-tracker.md` — Impacto de champions
