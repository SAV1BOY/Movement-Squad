---
id: causal-attribution-sanity
name: "Sanidade da Atribuição Causal"
squad: movement
type: checklist
category: impacto
agent: impact-agent
version: "1.0"
tags: [atribuição, causalidade, correlação, honestidade, rigor]
---

# Sanidade da Atribuição Causal

## Objetivo

Garantir que o movimento não está reivindicando crédito por resultados que não causou
ou confundindo correlação com causalidade. Atribuição causal rigorosa é a base da
credibilidade da mensuração de impacto.

## Checklist

### Rigor na Atribuição

- [ ] Para cada resultado reportado, o mecanismo causal está articulado (como A levou a B)
- [ ] Fatores externos que podem ter influenciado o resultado estão documentados
- [ ] Resultados não são atribuídos ao movimento sem evidência de contribuição direta
- [ ] Correlação temporal (aconteceu depois) não é usada como prova de causalidade
- [ ] Claims de impacto usam linguagem calibrada ("contribuiu para" vs "causou")

### Metodologia de Atribuição

- [ ] Modelo de atribuição está definido e documentado (first touch, last touch, multi-touch)
- [ ] O modelo escolhido é adequado ao tipo de jornada do público
- [ ] Limitações do modelo são conhecidas e comunicadas junto com resultados
- [ ] Existe pelo menos 1 método de validação cruzada (survey pós-conversão, controle)
- [ ] Quando possível, holdout groups são usados para estimar incrementalidade

### Armadilhas Comuns

- [ ] Viés de sobrevivência está mitigado (não olhar só para quem ficou/converteu)
- [ ] Regressão à média é considerada ao interpretar resultados de experimentos
- [ ] Base rate do mercado é usada como comparação (crescimento seria orgânico de qualquer forma?)
- [ ] Self-selection bias é reconhecido em pesquisas com membros da comunidade
- [ ] Hawthorne effect é considerado em experimentos com comunidade (se comportam diferente quando observados)

### Comunicação de Resultados

- [ ] Reports incluem seção de "limitações e caveats" junto com resultados
- [ ] Intervalos de confiança ou ranges são apresentados em vez de números pontuais
- [ ] Linguagem de resultados diferencia "provável", "possível" e "confirmado"
- [ ] Stakeholders são educados sobre limitações de atribuição (expectativas calibradas)
- [ ] Resultados contra-intuitivos ou negativos são reportados com igual rigor

## Critérios de Aprovação

- Todos os itens de "Rigor na Atribuição" devem estar completos
- Pelo menos 4 de 5 itens de "Metodologia" devem estar completos
- Pelo menos 4 de 5 itens de "Armadilhas" devem estar mitigados
- Todos os itens de "Comunicação de Resultados" devem estar completos

## Ação se Falhar

1. Revisar últimos 5 reports de impacto com lens de atribuição causal rigorosa
2. Retreinar equipe em conceitos de causalidade vs correlação com exemplos reais
3. Implementar template de report com seção obrigatória de limitações
4. Definir modelo de atribuição padrão e documentar para toda a equipe
5. Convidar analista externo para auditoria de metodologia de atribuição
