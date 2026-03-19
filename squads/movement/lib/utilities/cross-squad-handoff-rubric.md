---
id: cross-squad-handoff-rubric
name: "Rubrica de Handoff entre Squads"
squad: movement
type: utility
category: lib/utilities
version: 1.0.0
tags: [rubrica, handoff, cross-squad, qualidade, avaliação]
---

# Rubrica de Handoff entre Squads

## Propósito

Ferramenta padronizada para avaliar a qualidade de handoffs entre squads. Cada transição de responsabilidade é um momento de risco: informações se perdem, contexto evapora, prazos deslizam. Esta rubrica garante que todo handoff seja avaliável, rastreável e melhorável.

## Dimensões de Avaliação

### 1. Completude (0-25 pontos)

| Pontuação | Critério |
|-----------|----------|
| 0-5 | Entrega incompleta — faltam artefatos essenciais ou partes do escopo |
| 6-10 | Entrega parcial — artefatos principais presentes mas faltam dependências |
| 11-15 | Entrega substancial — todos os artefatos principais presentes, pequenas lacunas |
| 16-20 | Entrega completa — todos os artefatos presentes conforme acordado |
| 21-25 | Entrega exemplar — tudo presente, com materiais de apoio adicionais |

**O que verificar:**
- Todos os artefatos listados no acordo de handoff foram entregues?
- Formatos estão conforme o esperado pelo squad receptor?
- Dependências externas foram resolvidas antes da entrega?
- Nenhum item "pendente" ficou sem dono definido?
- Assets auxiliares (dados brutos, fontes, referências) estão incluídos?

### 2. Clareza (0-25 pontos)

| Pontuação | Critério |
|-----------|----------|
| 0-5 | Documentação confusa — receptor não entende o que recebeu |
| 6-10 | Documentação básica — entendível após múltiplas perguntas |
| 11-15 | Documentação clara — entendível com poucas perguntas de esclarecimento |
| 16-20 | Documentação excelente — autoexplicativa, receptor entende sem reunião |
| 21-25 | Documentação referência — serve como modelo para futuros handoffs |

**O que verificar:**
- O contexto estratégico está documentado (por que, não só o quê)?
- Decisões tomadas durante o processo estão registradas com racional?
- Limitações e ressalvas estão explícitas?
- Nomenclatura e terminologia são consistentes com o glossário do squad receptor?
- Existe um resumo executivo de 5 linhas no topo?

### 3. Evidências (0-25 pontos)

| Pontuação | Critério |
|-----------|----------|
| 0-5 | Sem evidências — entrega baseada apenas em opinião |
| 6-10 | Evidências anedóticas — exemplos isolados sem dados |
| 11-15 | Evidências parciais — dados presentes mas incompletos ou desatualizados |
| 16-20 | Evidências sólidas — dados quantitativos e qualitativos presentes |
| 21-25 | Evidências robustas — dados, narrativas, contra-argumentos e fontes verificáveis |

**O que verificar:**
- Dados quantitativos têm fonte, data e método de coleta?
- Dados qualitativos incluem verbatims ou exemplos concretos?
- Contra-argumentos e riscos estão documentados?
- Evidências são recentes (menos de 30 dias para dados voláteis)?
- Existe distinção clara entre fato, interpretação e hipótese?

### 4. Rastreabilidade (0-25 pontos)

| Pontuação | Critério |
|-----------|----------|
| 0-5 | Sem rastreabilidade — impossível saber quem fez o quê e quando |
| 6-10 | Rastreabilidade mínima — datas e autores de alguns artefatos |
| 11-15 | Rastreabilidade parcial — histórico de decisões principais documentado |
| 16-20 | Rastreabilidade completa — log de atividades, decisões e mudanças |
| 21-25 | Rastreabilidade exemplar — audit trail completo com links para registros |

**O que verificar:**
- Cada artefato tem autor e data de criação/atualização?
- Mudanças de escopo ou direção estão registradas com data e motivo?
- Experimentos realizados têm log no experiment-log?
- Referências cruzadas com outros artefatos do squad estão funcionando?
- O handoff em si está registrado com data, participantes e decisões?

### 5. Timing (0-25 pontos)

| Pontuação | Critério |
|-----------|----------|
| 0-5 | Atrasado criticamente — impactou entregas do squad receptor |
| 6-10 | Atrasado — fora do prazo mas sem impacto crítico |
| 11-15 | No prazo — entregue conforme combinado |
| 16-20 | Antecipado — entregue antes do prazo com qualidade mantida |
| 21-25 | Proativo — entregue antecipadamente com pre-brief ao squad receptor |

**O que verificar:**
- O prazo combinado foi cumprido?
- O squad receptor teve tempo adequado para absorver o material?
- Houve comunicação proativa sobre progresso antes da data de entrega?
- Riscos de atraso foram sinalizados com antecedência?
- A janela de handoff permitiu perguntas e ajustes?

## Classificação Geral

| Pontuação Total | Classificação | Ação Recomendada |
|----------------|---------------|------------------|
| 100-125 | GOLD | Registrar como referência, reconhecer o squad |
| 75-99 | GOOD | Aceitar e documentar pontos de melhoria |
| 50-74 | REVIEW | Aceitar condicionalmente, exigir correções em 48h |
| 0-49 | REJECT | Devolver ao squad emissor com lista de gaps |

## Como Usar

1. **Antes do handoff** — compartilhe esta rubrica com o squad emissor para alinhar expectativas
2. **No momento do handoff** — squad receptor avalia cada dimensão com 2+ avaliadores
3. **Registre a pontuação** — documente no registro de handoffs com data e avaliadores
4. **Comunique o resultado** — compartilhe com squad emissor para feedback construtivo
5. **Acompanhe tendências** — monitore médias por squad para identificar padrões

## Template de Avaliação

```yaml
avaliação_handoff:
  data: YYYY-MM-DD
  de_squad: ""
  para_squad: ""
  avaliadores: []
  asset_avaliado: ""
  pontuações:
    completude: 0
    clareza: 0
    evidências: 0
    rastreabilidade: 0
    timing: 0
  total: 0
  classificação: ""  # GOLD | GOOD | REVIEW | REJECT
  gaps_identificados: []
  ações_corretivas: []
  prazo_correção: ""
```

## Integração

- Usado no protocolo `cross-squad-handoff-protocol` como gate de qualidade
- Resultados alimentam o `handoff-component` para melhoria contínua
- Pontuações históricas rastreadas no `data/registries/` para tendências
- Complementa o `movement-scoring-rubric` com foco em transições
