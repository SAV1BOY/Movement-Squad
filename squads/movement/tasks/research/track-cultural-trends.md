---
id: track-cultural-trends
name: "Rastrear Tendências Culturais"
squad: movement
type: task
category: research
agents: [fenomenologo]
frameworks: [phenomenology-signal-clustering, cycle-cultural-wave-surfing]
checklists: [ciclo/trend-vs-fad-filter, fenomenologia/signal-source-diversity]
templates: [outputs/cultural-insight-report]
registry: [data/research/trend-briefs]
version: "1.0"
tags: [research, tendencias, cultura, macro, ciclos]
---

# Rastrear Tendências Culturais

## Objetivo

Monitorar e analisar tendências culturais em diferentes estágios de maturidade — de micro-sinais emergentes a macro-tendências consolidadas — avaliando seu impacto potencial no movimento e identificando janelas de oportunidade para ação.

## Contexto

Sinais viram tendências que viram mainstream que viram clichê. O timing de quando um movimento se conecta a uma tendência é tudo: cedo demais parece alienado, tarde demais parece oportunista. Este task mantém um radar vivo do ciclo de vida das tendências relevantes para calibrar o timing de cada ação do movimento.

## Inputs Necessários

- Signal Reports dos últimos 3 ciclos
- Relatórios de tendências de fontes de referência (WGSN, Trend Hunter, etc.)
- Dados de busca e volume de conversas sobre temas monitorados
- Mapa de tensões culturais atualizado
- Histórico do Trend Radar anterior

## Processo

1. **Definir camadas de monitoramento** — Organizar o radar em 4 camadas: (a) Micro-sinais (0-6 meses de vida), (b) Tendências emergentes (6-18 meses), (c) Tendências aceleradas (18-36 meses), (d) Macro-tendências consolidadas (3+ anos).

2. **Atualizar inventário de tendências** — Revisar o Trend Radar existente. Para cada tendência monitorada: verificar se subiu de camada, estagnou ou declinou. Adicionar novas tendências capturadas desde o último ciclo.

3. **Pesquisar fontes especializadas** — Consultar relatórios de tendências, futurismo e coolhunting. Cruzar com publicações acadêmicas, relatórios de comportamento do consumidor e forecasts de plataformas.

4. **Analisar dados de velocidade** — Para cada tendência, medir: crescimento de volume de busca, taxa de adoção por early adopters, velocidade de migração entre plataformas, entrada de marcas mainstream como sinal de pico.

5. **Mapear ciclo de vida** — Posicionar cada tendência no modelo de ciclo: Emergência → Adoção por nicho → Aceleração → Mainstream → Saturação → Declínio. Estimar em qual fase está e quanto tempo resta até a próxima.

6. **Avaliar relevância para o movimento** — Para cada tendência, pontuar: (a) Conexão com a thesis (1-5), (b) Conexão com o público (1-5), (c) Janela de oportunidade restante (1-5), (d) Risco de parecer oportunista (1-5, invertido).

7. **Identificar convergências** — Buscar pontos onde 2+ tendências convergem, criando oportunidades amplificadas. Convergências são mais poderosas que tendências isoladas.

8. **Formular trend briefs** — Para as 5-7 tendências mais relevantes, criar briefs detalhados: descrição, evidências, fase do ciclo, janela de oportunidade, recomendação de ação, riscos.

9. **Projetar cenários** — Para as top 3 tendências, criar cenários: "Se a tendência acelera, nosso movimento deveria...", "Se a tendência estagna, nosso movimento deveria...", "Se a tendência reverte, nosso movimento deveria...".

10. **Atualizar Trend Radar** — Publicar versão atualizada do radar visual com todas as tendências posicionadas por camada e relevância. Distribuir para o squad.

## Outputs Esperados

- **Trend Radar** visual atualizado
- **Trend Briefs** detalhados (5-7 por ciclo)
- **Análise de convergências** documentada
- **Cenários projetados** para top 3 tendências
- **Recomendações de timing** para ações do movimento

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Tendências monitoradas | >= 20 no radar ativo |
| Fontes consultadas | >= 10 fontes distintas |
| Trend briefs produzidos | >= 5 por ciclo |
| Convergências identificadas | >= 2 |
| Cenários por tendência top | >= 2 cenários cada |
| Ciclo de vida mapeado | 100% das tendências priorizadas |

## Decision Points

- **Tendência em aceleração + alta relevância** → Iniciar sprint de criação de conteúdo alinhado
- **Tendência chegando ao mainstream** → Avaliar se ainda vale surfar ou se é hora de se diferenciar
- **Tendência em declínio que adotamos** → Planejar transição narrativa suave
- **Convergência de tendências detectada** → Convocar sessão estratégica para avaliar oportunidade amplificada

## Integração

| Tipo | Referência |
|------|-----------|
| **Frameworks** | `frameworks/phenomenology-signal-clustering.md`, `frameworks/cycle-cultural-wave-surfing.md` |
| **Checklists** | `checklists/ciclo/trend-vs-fad-filter.md`, `checklists/fenomenologia/signal-source-diversity.md` |
| **Templates** | `templates/outputs/cultural-insight-report.md` |
| **Registries** | `data/research/trend-briefs/` |
| **Workflows** | `workflows/00-signal-radar-daily.md` |

### Regras de Fluxo
- **Rework:** Se quality gate reprovar → retornar à Fase 1 (varredura) com fontes ampliadas e reexecutar captura
- **Escalation:** Se bloqueio ou decisão fora de escopo → escalar para Movement Chief
- **Handoff:** Output vai para → tasks de Strategy (craft-movement-thesis, design-identity-system)
