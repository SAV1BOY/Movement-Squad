---
id: cb-05
name: Saúde e Crescimento
squad: movement
type: project-phase
category: community-build
phase: 5-health
tags:
  - saúde
  - crescimento
  - métricas
  - sustentabilidade
---

# 05 · Saúde e Crescimento

## Objetivo da Fase

Implementar sistema contínuo de monitoramento de saúde e crescimento da comunidade.
Comunidades saudáveis crescem organicamente; comunidades doentes precisam de
investimento constante para sobreviver. Esta fase garante que temos os sinais
certos para agir antes que problemas se tornem crises.

## Inputs

- Métricas de onboarding e retenção acumuladas (fases anteriores)
- Dados de participação em rituais
- Impacto do programa de champions (fase 04)
- Feedback qualitativo acumulado
- Benchmarks de comunidades similares
- Ferramentas de analytics configuradas

## Processo

1. **Dashboard de Saúde** — Construir dashboard com métricas-chave atualizadas
   automaticamente. Métricas essenciais:
   - Membros ativos (DAU/WAU/MAU e ratios)
   - Retenção por coorte (dia 1, 7, 30, 90)
   - Taxa de criação de conteúdo (% que cria vs. consome)
   - Sentimento geral (via análise de sentimento)
   - Diversidade de participação (concentração vs. distribuição)
   - Crescimento orgânico (novos membros por indicação)

2. **Auditoria Mensal** — Executar `community-health-audit.md` mensalmente.
   Documentar evolução de cada indicador. Identificar tendências antes
   que virem problemas.

3. **Sistema de Alertas** — Definir thresholds que disparam ação:
   - Retenção < 40%: investigar causa imediatamente
   - Atividade cai 30%+ em 2 semanas: intervenção
   - Sentimento negativo > 20%: diagnóstico urgente
   - Concentração > 80% em 10% dos membros: diversificar

4. **Estratégia de Crescimento Orgânico** — Criar flywheel de crescimento:
   membro engajado → cria conteúdo → conteúdo atrai novos → onboarding
   converte → membro engajado. Identificar gargalos no flywheel.

5. **Programa de Indicação** — Desenhar mecanismo de indicação que facilita
   e incentiva membros a trazerem outros. Deve ser natural, não forçado.
   Cada membro deveria conseguir explicar e convidar facilmente.

6. **Análise de Churn** — Investigar por que membros saem. Entrevistas
   de saída (quando possível), análise de padrões de abandono, identificação
   de momentos críticos na jornada.

7. **Ciclo de Melhoria** — Priorizar 3-5 ações de melhoria por mês baseadas
   em dados. Implementar, medir impacto, iterar. Documentar cada ciclo
   para referência futura.

8. **Relatório Trimestral** — Usar `quarterly-review-builder.md` para
   produzir relatório completo de saúde e crescimento. Compartilhar
   com stakeholders e com a própria comunidade (versão resumida).

## Outputs

- [ ] Dashboard de saúde configurado e atualizado
- [ ] Processo de auditoria mensal implementado
- [ ] Sistema de alertas com thresholds definidos
- [ ] Flywheel de crescimento mapeado com gargalos
- [ ] Programa de indicação desenhado e ativo
- [ ] Análise de churn com findings acionáveis
- [ ] 3-5 ações de melhoria priorizadas por mês
- [ ] Relatório trimestral produzido

## Quality Gate

| Critério                          | Mínimo Aceitável                         |
|-----------------------------------|------------------------------------------|
| Dashboard funcional               | Métricas atualizadas semanalmente        |
| Auditoria mensal                  | Executada sem falhas por 3+ meses        |
| Alertas funcionando               | Thresholds configurados e monitorados    |
| Crescimento orgânico              | Tendência positiva mês a mês             |
| Churn investigado                 | Causas principais identificadas          |
| Ações de melhoria                 | Implementadas com impacto medido         |

## Próxima Fase

→ Fase contínua. Saúde e crescimento é um processo permanente. Se métricas
indicarem necessidade de escala, encaminhar para `movement-scaling/`.
Se indicarem crise, encaminhar para `crisis-response/`.

### Métricas que Importam vs. Métricas de Vaidade

**Importam:**
- % de membros que criam conteúdo (creator ratio)
- Retenção por coorte ao longo do tempo
- Tempo até primeira contribuição significativa
- NPS da comunidade
- Crescimento via indicação orgânica

**Vaidade:** Total cadastrados sem considerar ativos, mensagens sem
qualidade, seguidores em redes, eventos sem participação.
