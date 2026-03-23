# Changelog — Log de Mudanças do Movement Squad

## Visão Geral

Este documento registra todas as mudanças significativas na estrutura,
documentação, frameworks, templates e processos do Movement Squad. Serve
como memória organizacional e referência histórica.

## Formato

Cada entrada segue o formato:
```
### [Data] — [Categoria] — [Descrição curta]
- O que mudou
- Por que mudou
- Quem contribuiu
- Impacto esperado
```

## Categorias

- **ESTRUTURA**: Mudanças na organização de diretórios e arquivos
- **DOCS**: Novos documentos ou atualizações significativas
- **FRAMEWORK**: Novos frameworks ou alterações em existentes
- **TEMPLATE**: Novos templates ou alterações em existentes
- **WORKFLOW**: Novos workflows ou alterações em existentes
- **CHECKLIST**: Novas checklists ou alterações em existentes
- **METRICA**: Novas métricas ou alterações em definições
- **REGISTRO**: Mudanças em registries (estrutura, não dados)
- **PROCESSO**: Mudanças em cadências, reuniões ou decisões
- **AGENTE**: Mudanças em definições de papéis dos agentes

---

## Registro de Mudanças

### 2026-03-10 — ESTRUTURA — Criação completa do diretório data/ e docs/

- **O que mudou**: Criação de toda a estrutura de diretórios e arquivos para
  data/research, data/registries, data/metrics e docs/
- **Por que mudou**: Estabelecer a infraestrutura base para operação do squad
- **Quem contribuiu**: Chief of Movement
- **Impacto esperado**: Squad tem agora toda a estrutura necessária para
  começar a operar com documentação, métricas e registros padronizados

**Arquivos criados**:
- 8 READMEs em data/research/ (signals, ethnography-notes, interviews,
  trend-briefs, competitor-movements, platform-dynamics, counter-narratives,
  cultural-context)
- 10 registries YAML em data/registries/ (movement-theses, identity-codes,
  community-roles, creator-partners, experiment-log, decision-log,
  slogan-bank, signal-archive, champion-registry, lessons-learned-registry)
- 11 definições de métricas em data/metrics/
- 18 documentos em docs/
- 13 arquivos .gitkeep para diretórios vazios

---

### Template para Novas Entradas

```
### YYYY-MM-DD — [CATEGORIA] — [Descrição curta]

- **O que mudou**: [Descrição detalhada]
- **Por que mudou**: [Justificativa]
- **Quem contribuiu**: [Nome ou papel]
- **Impacto esperado**: [O que muda na prática]
```

---

## Notas

- Registre TODAS as mudanças significativas, mesmo pequenas
- Mudanças em dados (novos sinais, novas entrevistas) NÃO precisam ir aqui
  — são registradas em seus respectivos diretórios
- Mudanças em ESTRUTURA (como os dados são organizados) devem ser registradas
- Se uma mudança quebra compatibilidade com processos existentes, destaque
  claramente e notifique o squad
- Mantenha este arquivo em ordem cronológica reversa (mais recente primeiro)
