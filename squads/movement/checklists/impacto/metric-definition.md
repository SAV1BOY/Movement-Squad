---
id: metric-definition
name: "Qualidade da Definição de Métricas"
squad: movement
type: checklist
category: impacto
agent: impact-agent
version: "1.0"
tags: [métricas, definição, kpi, mensuração, clareza]
---

# Qualidade da Definição de Métricas

## Objetivo

Garantir que cada métrica do movimento está definida com precisão suficiente para
ser mensurada, interpretada e acionada de forma consistente por qualquer membro
da equipe. Métrica ambígua gera discussão sobre números em vez de ação sobre resultados.

## Checklist

### Definição Técnica

- [ ] Cada métrica tem nome único e padronizado (sem sinônimos confusos)
- [ ] Fórmula de cálculo está documentada e não deixa margem para interpretação
- [ ] Fonte de dados está definida (de onde vem o número exatamente)
- [ ] Granularidade temporal está definida (diária, semanal, mensal)
- [ ] Unidade de medida está explícita (%, absoluto, taxa, R$)

### Relevância Estratégica

- [ ] Cada métrica está conectada a pelo menos 1 objetivo de negócio
- [ ] Não existem métricas medidas "por hábito" sem utilidade atual
- [ ] Existem no máximo 5 métricas primárias (north star + 4 de suporte)
- [ ] Métricas secundárias (operacionais) estão separadas das primárias
- [ ] Cada métrica responde a uma pergunta específica de negócio

### Metas e Thresholds

- [ ] Cada métrica primária tem meta numérica para o período atual
- [ ] Metas foram baseadas em benchmark, histórico ou estimativa fundamentada
- [ ] Threshold de "verde" (on track), "amarelo" (atenção) e "vermelho" (risco) está definido
- [ ] Metas são desafiadoras mas realistas (não são número mágico)
- [ ] Metas são revisadas trimestralmente com base em aprendizado acumulado

### Operacionalização

- [ ] Dashboard com métricas primárias está acessível e atualizado automaticamente
- [ ] Responsável por atualizar cada métrica está nomeado
- [ ] Frequência de revisão de métricas com equipe está definida (semanal para primárias)
- [ ] Anomalias em métricas disparam investigação em até 48h
- [ ] Histórico de métricas é armazenado para análise de tendência

## Critérios de Aprovação

- Todos os itens de "Definição Técnica" devem estar completos
- Todos os itens de "Relevância Estratégica" devem estar completos
- Todos os itens de "Metas e Thresholds" devem estar completos
- Pelo menos 4 de 5 itens de "Operacionalização" devem estar completos

## Ação se Falhar

1. Realizar workshop de métricas com equipe para alinhar definições
2. Criar dicionário de métricas com ficha para cada indicador
3. Eliminar métricas que não geram ação (reduzir ruído)
4. Implementar dashboard mínimo viável com as 5 métricas primárias
5. Revisar métricas com stakeholders para validar relevância estratégica
