---
id: experiment-readout
name: "Qualidade do Readout de Experimentos"
squad: movement
type: checklist
category: impacto
agent: impact-agent
version: "1.0"
tags: [experimento, readout, resultado, aprendizado, decisão]
---

# Qualidade do Readout de Experimentos

## Objetivo

Garantir que cada experimento do movimento produz readout estruturado com dados
confiáveis, conclusões honestas e próximos passos claros. Experimento sem readout
de qualidade é desperdício de tempo e recurso.

## Checklist

### Design do Experimento

- [ ] Hipótese está documentada antes do início (o que esperamos que aconteça e por quê)
- [ ] Métrica de sucesso está definida antes do início (não escolhida depois com viés)
- [ ] Tamanho de amostra mínimo está calculado para resultado estatisticamente relevante
- [ ] Grupo de controle está definido (o que acontece se não fizermos nada)
- [ ] Duração do experimento está pré-definida (não encerrado quando resultado "fica bom")

### Coleta de Dados

- [ ] Instrumentação de dados foi verificada antes do início (tracking funcionando)
- [ ] Dados estão sendo coletados automaticamente (não depende de coleta manual subjetiva)
- [ ] Fatores externos que podem influenciar o resultado estão documentados
- [ ] Não houve mudança de variáveis durante o experimento (contamination)
- [ ] Dados brutos estão armazenados e auditáveis

### Análise e Conclusão

- [ ] Resultado é comparado com hipótese original (confirmou, refutou, inconclusivo)
- [ ] Significância estatística é reportada quando aplicável (não apenas "pareceu melhor")
- [ ] Resultados são apresentados com intervalo de confiança (não número absoluto isolado)
- [ ] Explicações alternativas para o resultado são consideradas (não pular para causalidade)
- [ ] Conclusão é honesta sobre limitações do experimento

### Ação Pós-Readout

- [ ] Decisão clara está documentada: escalar, iterar, pivotar ou encerrar
- [ ] Se escalar: plano de rollout com timeline e recursos está definido
- [ ] Se iterar: próxima versão do experimento está desenhada com ajustes específicos
- [ ] Se encerrar: motivo está documentado e investimento perdido é aceito
- [ ] Aprendizado é adicionado ao banco de conhecimento do movimento

## Critérios de Aprovação

- Todos os itens de "Design do Experimento" devem estar completos
- Todos os itens de "Coleta de Dados" devem estar completos
- Todos os itens de "Análise e Conclusão" devem estar completos
- Todos os itens de "Ação Pós-Readout" devem estar completos

## Ação se Falhar

1. Criar template obrigatório de design de experimento (preencher ANTES de iniciar)
2. Verificar instrumentação de dados antes de cada experimento (não depois)
3. Treinar equipe em conceitos básicos de estatística e significância
4. Implementar review de readout com pessoa não envolvida na execução (olhar fresco)
5. Criar repositório de experimentos com busca por tema e resultado
