# Operating System — Cadência, Reuniões e Decisões

## Visão Geral

O sistema operacional do Movement Squad define como o time opera no dia a
dia: cadências, reuniões, rituais internos e processo de tomada de decisão.
Consistência operacional é o que transforma estratégia em execução.

## Cadências

### Diária
- **Captura de sinais**: Anthropologist registra mínimo 3 sinais por dia útil
- **Monitoramento de comunidade**: Community Architect verifica saúde
- **Publicação**: Memetic Engineer publica conforme calendário
- **Distribuição**: Distribution Hacker otimiza posts publicados

### Semanal
- **Segunda**: Dashboard semanal preenchido e revisado
- **Terça-Quinta**: Execução de workflows e experimentos
- **Sexta**: Ritual da comunidade (Sexta do Fracasso)
- **Sexta**: Retrospectiva rápida do squad (15 min)

### Quinzenal
- **Score de maturidade**: Chief calcula e registra
- **Análise de sentimento**: Metrics Analyst + Anthropologist
- **Revisão de experimentos**: Status de todos os experimentos ativos

### Mensal
- **Revisão estratégica**: Chief + todos os agentes (1h)
- **Atualização de teses**: Validar/invalidar com novas evidências
- **Review de champions**: Community Architect + Chief
- **Pesquisa de sentimento**: Enviar pesquisa para comunidade
- **Report de impacto**: Metrics Analyst consolida business impact

### Trimestral
- **Recalibração de metas**: Ajustar targets de métricas
- **Revisão de frameworks**: Avaliar quais frameworks estão funcionando
- **Planejamento do próximo trimestre**: Prioridades e experimentos
- **Pesquisa profunda de alinhamento**: Survey completo com comunidade

## Reuniões

### Standup Semanal (15 min — Segunda)
- **Quem**: Todos os agentes
- **Formato**: Cada agente em 2 min: o que fez, o que vai fazer, bloqueios
- **Output**: Alinhamento da semana

### Review de Dashboard (30 min — Segunda)
- **Quem**: Chief + Metrics Analyst (demais opcionais)
- **Formato**: Análise do dashboard semanal
- **Output**: Ações da semana definidas

### Revisão Estratégica Mensal (60 min — Primeira segunda do mês)
- **Quem**: Todos os agentes
- **Formato**: Retrospectiva + planejamento
- **Output**: Decisões documentadas no decision-log

### Revisão de Experimentos (30 min — Quinzenal)
- **Quem**: Chief + responsáveis dos experimentos ativos
- **Formato**: Status de cada experimento, decisões sobre concluídos
- **Output**: Atualização do experiment-log

## Processo de Decisão

### Decisões Operacionais (Dia a dia)
- **Quem decide**: Cada agente dentro de seu escopo
- **Documentação**: Não obrigatória, mas recomendada
- **Exemplo**: Escolha de formato de conteúdo, timing de post

### Decisões Táticas (Semana)
- **Quem decide**: Agente responsável com input do Chief
- **Documentação**: Registrar se afetar mais de 1 agente
- **Exemplo**: Mudança de ritual, novo canal de distribuição

### Decisões Estratégicas (Mês/Trimestre)
- **Quem decide**: Chief of Movement após ouvir agentes
- **Documentação**: Obrigatória no decision-log
- **Exemplo**: Nova tese, mudança de enemy, expansão de plataforma

### Decisões Emergenciais
- **Quem decide**: Chief of Movement imediatamente
- **Documentação**: Obrigatória dentro de 24h
- **Exemplo**: Crise de reputação, contra-narrativa viral

## Princípios de Decisão

1. **Dados > Opinião**: Sempre que possível, basear em evidências
2. **Reversibilidade**: Decisões reversíveis podem ser rápidas; irreversíveis
   precisam de mais deliberação
3. **Transparência**: Documentar o porquê, não apenas o quê
4. **Discordar e comprometer**: Quem discorda pode registrar, mas executa
5. **Velocidade**: 80% de certeza é suficiente para decidir

## Ferramentas e Rituais

- **Decision log**: `data/registries/decision-log.yaml`
- **Experiment log**: `data/registries/experiment-log.yaml`
- **Dashboard**: `data/metrics/weekly-dashboard.md`
- **Retrospectiva**: Formato Start/Stop/Continue (15 min na sexta)

## Evolução do Sistema

Este sistema operacional é vivo. Revisar trimestralmente e ajustar o que
não estiver funcionando. Documentar mudanças no `changelog.md`.
