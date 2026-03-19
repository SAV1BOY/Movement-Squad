---
id: experiment-sprint
name: "Sprint de Experimento: Hipótese → Teste → Readout → Decisão"
squad: movement
type: workflow
agents: [analista-impacto, estrategista-movimento, manifestador-criativo]
cadence: weekly
version: "1.0"
tags: [workflow, experimento, sprint, hipotese, teste, aprendizado]
---

# Sprint de Experimento: Hipótese → Teste → Readout → Decisão

## Objetivo

Operar sprints de experimentação rápidos e disciplinados que testem hipóteses sobre o movimento em ciclos curtos (1-2 semanas), gerando aprendizado acionável que reduz incerteza e guia decisões com dados reais.

## Diagrama de Fases

```
[HIPÓTESE]        [DESIGN]          [EXECUÇÃO]        [READOUT]         [DECISÃO]
Formular      →   Projetar      →   Executar      →   Analisar      →   Decidir
Hipótese          Experimento       Teste             Resultados        e Agir
   |                 |                  |                  |                  |
   v                 v                  v                  v                  v
"Se X, então Y   Variáveis,        Teste rodando,   Readout de        Implementar,
porque Z"        amostra,          dados coletados  1 página,         pivotar ou
                 duração, métrica                    insight claro     descartar
```

## Fases Detalhadas

### Fase 1: Formulação de Hipótese (Dia 1)

**Agentes:** estrategista-movimento, analista-impacto

**Inputs:**
- Backlog de hipóteses (de reviews, sinais, feedbacks)
- Métricas em alerta que precisam de investigação
- Ideias do squad e da comunidade

**Ações:**
1. Revisar backlog de hipóteses e priorizar por: impacto potencial x custo de teste
2. Formular hipótese no formato: "Se fizermos X, esperamos Y porque Z"
3. Definir: o que estamos tentando aprender? Qual decisão este teste informa?
4. Verificar se a hipótese é testável em 1-2 semanas com os recursos disponíveis
5. Selecionar 1-2 hipóteses para o sprint atual

**Outputs:**
- Hipótese(s) formulada(s) e priorizada(s)
- Justificativa de seleção

**Decision Gate:**
- Hipótese clara e testável → avançar para design
- Hipótese vaga → refinar antes de prosseguir

### Fase 2: Design do Experimento (Dia 2)

**Agentes:** analista-impacto

**Inputs:**
- Hipótese selecionada
- Recursos e ferramentas disponíveis
- Dados baseline

**Ações:**
1. Definir variável independente (o que mudamos)
2. Definir variável dependente (o que medimos)
3. Definir grupo teste vs. controle (quando aplicável)
4. Calcular tamanho de amostra necessário para resultado significativo
5. Definir duração do teste e critério de sucesso (qual resultado confirma/refuta)
6. Preparar assets ou variações necessárias para o teste
7. Configurar tracking e instrumentação

**Outputs:**
- Experiment Card completo
- Assets de teste prontos
- Tracking configurado

**Decision Gate:**
- Design robusto → executar
- Design fraco (amostra insuficiente, variáveis confusas) → redesenhar

### Fase 3: Execução do Teste (Dia 3-10)

**Agentes:** manifestador-criativo, ativador-chefe

**Inputs:**
- Experiment Card
- Assets de teste
- Tracking ativo

**Ações:**
1. Lançar teste conforme planejado
2. NÃO mudar variáveis durante a execução (disciplina)
3. Monitorar: dados sendo coletados corretamente? Anomalias?
4. Registrar observações qualitativas durante o teste
5. Se detectar problema grave (ex: bug, ofensa), pausar e ajustar

**Outputs:**
- Teste executado conforme planejado
- Dados brutos coletados
- Observações qualitativas registradas

**Decision Gate:**
- Teste completou período planejado → avançar para readout
- Teste interrompido por problema → documentar e decidir: recomeçar ou cancelar

### Fase 4: Readout e Análise (Dia 11-12)

**Agentes:** analista-impacto

**Inputs:**
- Dados brutos do teste
- Observações qualitativas
- Baseline para comparação

**Ações:**
1. Consolidar dados quantitativos: métrica de sucesso, diferença entre teste e controle
2. Avaliar significância: o resultado é estatisticamente relevante ou pode ser acaso?
3. Incorporar insights qualitativos: o que os números não contam?
4. Determinar veredicto: hipótese confirmada, refutada ou inconclusiva
5. Produzir readout de 1 página: hipótese, como testamos, o que encontramos, o que significa, ação recomendada

**Outputs:**
- Readout de 1 página
- Dados completos arquivados
- Veredicto claro

**Decision Gate:**
- Resultado claro → avançar para decisão
- Resultado inconclusivo → decidir: testar com mais rigor ou aceitar incerteza

### Fase 5: Decisão e Ação (Dia 12-14)

**Agentes:** estrategista-movimento, arquiteto-movimento

**Inputs:**
- Readout do experimento
- Contexto estratégico

**Ações:**
1. Apresentar readout no kaizen semanal ou reunião dedicada
2. Decidir: implementar (se confirmada), pivotar (se refutada), aprofundar (se inconclusiva)
3. Se implementar: definir quem executa, quando, como escalar
4. Atualizar banco de aprendizados e playbooks relevantes
5. Gerar novas hipóteses derivadas do resultado
6. Alimentar backlog para próximo sprint

**Outputs:**
- Decisão documentada
- Ação de implementação (se aplicável)
- Banco de aprendizados atualizado
- Novas hipóteses para backlog

**Decision Gate:**
- Decisão tomada e comunicada → sprint completo
- Nova hipótese gerada → enfileirar para próximo sprint

## Cadência

- **Sprint completo:** 10-14 dias
- **Capacidade:** 2-3 sprints simultâneos (se recursos permitem)
- **Backlog review:** Semanal (no kaizen)
- **Meta:** >= 2 experimentos concluídos por mês

## Artefatos Produzidos

- Experiment Cards
- Readouts de 1 página
- Banco de aprendizados atualizado
- Decisões documentadas

## Métricas de Sucesso

| Métrica | Meta |
|---------|------|
| Experimentos/mês | >= 2 |
| Tempo de ciclo (hipótese → readout) | <= 14 dias |
| Readouts produzidos | 100% dos experimentos |
| Decisões implementadas | >= 80% das confirmadas |
| Hipóteses geradas por readout | >= 1 nova |
| Aprendizados documentados | 100% |

## Integração

| Tipo | Referência |
|------|-----------|
| **Tasks** | `tasks/measurement/run-experiments.md`, `tasks/measurement/measure-movement-health.md`, `tasks/measurement/analyze-content-to-conversation.md` |
| **Frameworks** | `frameworks/impact-experiment-design.md`, `frameworks/impact-learning-loop.md`, `frameworks/ralphloop-kaizen.md` |
| **Checklists** | `checklists/experimentation-quality.md`, `checklists/impacto/experiment-readout.md`, `checklists/impacto/vanity-metric-filter.md` |
| **Registries** | `data/registries/experiment-log.yaml`, `data/registries/lessons-learned-registry.yaml` |

### Regras de Fluxo
- **Quality Gate entre fases:** Hipótese→Design: hipótese formatada (Se X, então Y porque Z); Design→Execução: experimento projetado com variáveis claras; Execução→Readout: teste completou período; Readout→Decisão: veredicto claro
- **Rework:** Se resultado inconclusivo → redesenhar teste com mais rigor ou mais amostra
- **Escalation:** Se experimento revela risco reputacional → pausar e escalar para Movement Chief
- **Handoff:** Readouts e decisões alimentam → `workflows/05-ralphloop-kaizen-weekly.md` e banco de aprendizados
