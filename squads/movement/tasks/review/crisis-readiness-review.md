---
id: crisis-readiness-review
name: "Review de Prontidão para Crise"
squad: movement
type: task
category: review
agents: [estrategista-movimento, arquiteto-movimento]
frameworks: [crisis-readiness-framework, backlash-preparedness-model]
checklists: [crisis-readiness-checklist, response-protocol-checklist]
templates: [crisis-readiness-scorecard-template, scenario-update-template]
version: "1.0"
tags: [review, crise, prontidao, backlash, protocolo, risco]
---

# Review de Prontidão para Crise

## Objetivo

Avaliar periodicamente o nível de preparação do squad para lidar com crises, backlash e contra-narrativas — garantindo que protocolos estejam atualizados, porta-vozes treinados, cenários simulados e a equipe pronta para responder com velocidade e consistência.

## Contexto

Não é "se" uma crise vai acontecer — é "quando". Movimentos polarizados são especialmente vulneráveis: cada posição forte gera oposição proporcional. O review de prontidão garante que o squad não seja pego de surpresa, transformando uma crise potencial em oportunidade de demonstrar integridade e resiliência.

## Inputs Necessários

- Counter-Narrative Playbook atualizado
- Protocolos de escalação vigentes
- Lista de porta-vozes e seus treinamentos
- Cenários de backlash simulados anteriormente
- Histórico de crises/incidentes do período
- Signal Reports com sinais de risco emergentes

## Processo

1. **Auditar Counter-Narrative Playbook** — Revisar: todas as contra-narrativas ainda são relevantes? Surgiu alguma nova? As respostas preparadas ainda são adequadas? Os dados de suporte ainda são válidos?

2. **Revisar protocolos de escalação** — Verificar: os níveis de escalação fazem sentido? Os contatos estão atualizados? O fluxo de decisão está claro? Quem está de plantão esta semana?

3. **Avaliar prontidão dos porta-vozes** — Para cada porta-voz: quando foi o último treinamento? Está confortável com as key messages atuais? Sabe lidar com perguntas hostis? Precisa de reciclagem?

4. **Atualizar cenários de risco** — Com base nos sinais culturais recentes: quais novos cenários de crise são plausíveis? O que mudou no ambiente que cria novos riscos? Priorizar top 3 cenários novos.

5. **Simular cenário top 1** — Rodar tabletop exercise: apresentar cenário realista, cronometrar resposta do squad, avaliar qualidade da resposta, identificar gaps no protocolo.

6. **Revisar capacidade de monitoramento** — Verificar: ferramentas de social listening estão configuradas para alertas? Keywords de risco estão atualizadas? Alguém está monitorando fora de horário?

7. **Avaliar relacionamentos de crise** — Verificar: temos contato direto com jornalistas-chave para resposta rápida? Temos relação com plataformas para solicitar remoção se necessário? Temos suporte jurídico acessível?

8. **Revisar histórico de incidentes** — Analisar todos os incidentes (pequenos ou grandes) do período: como foram tratados? O protocolo funcionou? O que poderíamos ter feito melhor?

9. **Calcular Crisis Readiness Score** — Pontuar de 0-100 baseado em: playbook atualizado, porta-vozes prontos, protocolos funcionais, simulação realizada, monitoramento ativo.

10. **Definir ações de melhoria** — Para cada gap identificado, definir: ação corretiva, responsável, prazo. Priorizar itens que reduzem risco mais rapidamente.

## Outputs Esperados

- **Crisis Readiness Scorecard** atualizado
- **Counter-Narrative Playbook** revisado
- **Cenários de risco** atualizados (top 3-5)
- **Resultados da simulação** documentados
- **Ações de melhoria** priorizadas
- **Status de porta-vozes** atualizado

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Playbook revisado | 100% das contra-narrativas |
| Protocolos verificados | Todos os níveis de escalação |
| Porta-vozes avaliados | 100% dos designados |
| Simulação realizada | >= 1 por trimestre |
| Crisis Readiness Score | >= 70/100 |
| Monitoramento ativo | 24/7 (pelo menos alertas) |

## Decision Points

- **Score > 80** → Prontidão adequada, manter cadência de review
- **Score 60-80** → Atenção — priorizar treinamento e simulação
- **Score < 60** → Vulnerável — ações corretivas imediatas antes de qualquer ativação grande
- **Cenário de risco iminente** → Congelar ativações não-essenciais e preparar resposta

## Integração

| Tipo | Referência |
|------|-----------|
| **Frameworks** | `frameworks/crisis-to-movement-framework.md`, `frameworks/governance-layer.md` |
| **Checklists** | `checklists/crisis-and-backlash-quality.md`, `checklists/pr/backlash-mitigation.md` |
| **Templates** | `templates/plans/crisis-response-plan.md` |
| **Registries** | `data/registries/decision-log.yaml` |
| **Workflows** | `workflows/05-ralphloop-kaizen-weekly.md` |

### Regras de Fluxo
- **Rework:** Se quality gate reprovar → documentar gaps encontrados, definir ações corretivas e reagendar review em 1 semana
- **Escalation:** Se bloqueio ou decisão fora de escopo → escalar para Movement Architect
- **Handoff:** Output vai para → tasks de Strategy e Operations do próximo ciclo
