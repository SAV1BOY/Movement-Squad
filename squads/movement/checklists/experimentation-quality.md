---
id: experimentation-quality
name: "Qualidade do Experimento"
squad: movement
type: checklist
category: quality-gate
version: "1.0"
tags: [experimento, teste, hipótese, dados, decisão, aprendizado]
---

# Qualidade do Experimento

## Objetivo

Validar que cada experimento executado dentro do movimento segue rigor metodológico mínimo:
hipótese clara e falsificável, variável única isolada, critérios de leitura de resultado
pré-definidos e decisão vinculada ao resultado. Experimentos mal desenhados geram dados
que mentem e decisões que destroem momentum.

## Quando Usar

- Antes de iniciar qualquer teste A/B, piloto ou experimento no movimento
- Quando resultados de um experimento forem ambíguos ou contestados
- Na priorização de backlog de experimentos (decidir quais rodar)
- Em revisões semanais de aprendizados de experimentação
- Quando um stakeholder questionar uma decisão baseada em dados

## Agentes Responsáveis

- **Experimentation Agent** — Designer e executor dos experimentos
- **Data & Analytics Agent** — Valida setup estatístico e leitura de dados
- **Movement Strategist Agent** — Define prioridade estratégica dos experimentos
- **Review & QA Agent** — Executa este checklist como quality gate

## Checklist

### 1. Hipótese

- [ ] 1.1 A hipótese está escrita no formato "Se [ação], então [resultado], porque [razão]"
- [ ] 1.2 A hipótese é falsificável (é possível provar que está errada)
- [ ] 1.3 A hipótese está vinculada a uma decisão real (se confirmar, faremos X; se refutar, Y)
- [ ] 1.4 A hipótese é relevante para o momento atual do movimento (não é curiosidade acadêmica)
- [ ] 1.5 A hipótese foi priorizada usando critério de impacto x esforço documentado

### 2. Design do Experimento

- [ ] 2.1 A variável que está sendo testada é UMA única (isolamento de variável)
- [ ] 2.2 O grupo de controle está definido (contra o que estamos comparando)
- [ ] 2.3 O tamanho da amostra é suficiente para significância estatística (calculado, não chutado)
- [ ] 2.4 A duração do experimento está definida com data de início e fim
- [ ] 2.5 Fatores externos que podem contaminar o resultado estão listados e mitigados
- [ ] 2.6 O experimento não prejudica a experiência do usuário/membro durante o teste

### 3. Métricas e Leitura

- [ ] 3.1 A métrica primária de sucesso está definida antes do início do experimento
- [ ] 3.2 Métricas secundárias e guardrail metrics estão definidas (o que não pode piorar)
- [ ] 3.3 O threshold de sucesso está quantificado (ex.: aumento de 15% com p < 0.05)
- [ ] 3.4 A fonte de dados e o método de coleta estão configurados e testados
- [ ] 3.5 Existe plano para lidar com resultado inconclusivo (o que fazer se não der significância)

### 4. Execução

- [ ] 4.1 O setup técnico foi testado em ambiente de staging antes do lançamento
- [ ] 4.2 Um checkpoint intermediário está agendado (metade do prazo) para sanity check
- [ ] 4.3 O experimento pode ser interrompido rapidamente se causar dano inesperado
- [ ] 4.4 Todas as pessoas envolvidas na execução sabem seu papel e timeline

### 5. Decisão e Documentação

- [ ] 5.1 A decisão pós-resultado está pré-mapeada (confirma: escalar; refuta: pivotar; inconclusivo: re-testar)
- [ ] 5.2 O responsável por tomar a decisão final está nomeado
- [ ] 5.3 O formato de documentação do resultado está definido (template de learnings)
- [ ] 5.4 Os aprendizados serão compartilhados com a equipe em até 48h após conclusão
- [ ] 5.5 O repositório de experimentos será atualizado independente do resultado

## Critérios de Aprovação

- **Aprovado:** Todos os 25 itens completos com hipótese, design e métricas documentados
- **Aprovado com ressalvas:** Até 2 itens pendentes, nenhum dos grupos "Hipótese" ou "Métricas"
- **Reprovado:** 3+ itens pendentes, ou experimento sem hipótese falsificável

## Ação se Falhar

1. Devolver ao Experimentation Agent para redesenho do experimento
2. Se a hipótese for vaga, realizar sessão de refinamento com o strategist
3. Se o design for falho, consultar Data & Analytics Agent para ajuste estatístico
4. Nunca rodar experimento sem métrica de sucesso pré-definida (regra absoluta)
5. Experimentos que falharem no gate 2 vezes devem ser despriorizados

## Cross-references

- `impact-dashboard-quality.md` — Resultados de experimentos alimentam o dashboard
- `movement-thesis-quality.md` — Experimentos podem validar ou invalidar a tese
- `cultural-insight-quality.md` — Insights podem ser testados como experimentos
- `movement-to-product-fit-quality.md` — Fit pode ser otimizado via experimentação
- `distribution-plan-quality.md` — Canais e formatos são testáveis via experimentos
- Framework: Experimentation Playbook v1
- Template: Ficha de Experimento (template-experiment.md)
