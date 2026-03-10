---
id: run-experiments
name: "Executar Experimentos e Readout"
squad: movement
type: task
category: measurement
agents: [analista-impacto, estrategista-movimento]
frameworks: [experiment-sprint-framework, hypothesis-test-learn-model]
checklists: [experiment-design-checklist, readout-checklist]
templates: [experiment-card-template, readout-template]
version: "1.0"
tags: [measurement, experimentos, testes, hipoteses, aprendizado]
---

# Executar Experimentos e Readout

## Objetivo

Projetar, executar e analisar experimentos rápidos que testem hipóteses sobre o movimento — mensagens, formatos, canais, rituais, ofertas — gerando aprendizado acionável que reduz incerteza e guia as próximas decisões com dados reais.

## Contexto

Movimentos culturais são complexos demais para planejar tudo a priori. Experimentos são a forma de aprender rápido o que funciona e o que não funciona sem apostar o farm. Cada experimento é uma pergunta feita ao mundo real — e a resposta vale mais que qualquer opinião interna.

## Inputs Necessários

- Hipóteses derivadas de Signal Reports, reviews e brainstorms
- Baseline de métricas atuais
- Budget alocado para testes
- Assets e conteúdo existentes para variações
- Calendar com janelas disponíveis para testes
- Win Conditions como referência de sucesso

## Processo

1. **Coletar hipóteses** — Reunir hipóteses de múltiplas fontes: signal reports, community feedback, brainstorms do squad, intuições de creators, dados de performance. Formular cada uma como: "Se fizermos X, esperamos Y porque Z."

2. **Priorizar por impacto e custo** — Classificar cada hipótese por: (a) Impacto potencial se confirmada (1-5), (b) Custo/esforço para testar (1-5 invertido), (c) Urgência (1-5). Selecionar top 3-5 para o ciclo.

3. **Projetar experimento** — Para cada hipótese: definir variável independente (o que mudamos), variável dependente (o que medimos), grupo teste vs. controle, tamanho de amostra necessário, duração do teste, critério de sucesso.

4. **Preparar assets de teste** — Produzir variações necessárias: A/B de headlines, formatos diferentes, canais alternativos, abordagens de ritual distintas. Minimizar variáveis mudadas simultaneamente.

5. **Executar com disciplina** — Rodar o experimento conforme planejado: não mudar variáveis durante o teste, não parar antes do prazo (exceto se detectar problema grave), registrar qualquer anomalia.

6. **Coletar dados** — Ao final do período: consolidar métricas quantitativas (engajamento, conversão, retenção) e qualitativas (comentários, feedback, observações comportamentais).

7. **Analisar resultados** — Determinar: a hipótese foi confirmada, refutada ou inconclusiva? O resultado tem significância estatística? Há nuances que os números não capturam?

8. **Produzir readout** — Criar documento conciso: hipótese testada, como testamos, o que encontramos, o que significa para o movimento, ação recomendada. Formato: 1 página, visual, decisão clara.

9. **Socializar learnings** — Apresentar readout ao squad: compartilhar em reunião semanal, adicionar ao banco de aprendizados, atualizar playbooks relevantes com base no resultado.

10. **Alimentar próximo ciclo** — Os resultados geram novas hipóteses? Algum experimento precisa de segunda rodada com mais profundidade? Inserir no backlog de hipóteses para priorização.

## Outputs Esperados

- **Experiment Cards** preenchidos (3-5 por ciclo)
- **Readouts** com resultados e recomendações
- **Banco de aprendizados** atualizado
- **Novas hipóteses** derivadas dos resultados
- **Playbooks atualizados** quando aplicável

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Experimentos executados | >= 3 por ciclo |
| Hipóteses formuladas corretamente | 100% com formato "Se X, então Y porque Z" |
| Readouts produzidos | 100% dos experimentos |
| Tempo de ciclo | <= 2 semanas por experimento |
| Ações derivadas | >= 1 ação por readout |
| Banco de aprendizados | Atualizado em até 48h pós-readout |

## Decision Points

- **Hipótese confirmada com força** → Implementar imediatamente e comunicar squad
- **Hipótese refutada** → Documentar aprendizado e considerar hipótese inversa
- **Resultado inconclusivo** → Avaliar se vale testar com mais amostra ou pivotar hipótese
- **Resultado surpreendente** → Explorar com mais profundidade antes de generalizar

## Integração

- **Alimenta:** `measure-movement-health`, `measure-business-impact`, todas as tasks de criação e ativação
- **Recebe de:** `detect-cultural-signals`, `measure-community-health`, `weekly-kaizen-loop`
- **Workflow relacionado:** `18-experiment-sprint`, `04-measure-and-learn`
- **Cadência:** Quinzenal (ciclo de experimento) ou conforme sprint definido
- **Handoff:** Readouts vão para todo o squad e alimentam decisões estratégicas
