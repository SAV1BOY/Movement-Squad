---
id: decision-logs
name: "Padrão de Log de Decisão"
squad: movement
type: utility
category: lib/utilities
version: 1.0.0
tags: [decisão, log, registro, governança, utilidade]
---

# Padrão de Log de Decisão

## Propósito

Template e processo para registrar decisões estratégicas do movimento, garantindo memória institucional, accountability e aprendizado.

## Template de Decisão

```yaml
---
id: decision-YYYY-MM-DD-titulo-curto
name: "Título da Decisão"
squad: movement
type: decision
category: archive/decisions
version: 1.0.0
tags: [decisão, contexto-relevante]
date: YYYY-MM-DD
status: proposta | aprovada | implementada | revertida
---
```

### Corpo da Decisão

```markdown
## Contexto
[O que estava acontecendo que exigiu essa decisão?]

## Problema
[Qual problema específico estávamos tentando resolver?]

## Opções Consideradas

### Opção A: [Nome]
- **Prós:** [lista]
- **Contras:** [lista]
- **Risco:** [baixo | médio | alto]

### Opção B: [Nome]
- **Prós:** [lista]
- **Contras:** [lista]
- **Risco:** [baixo | médio | alto]

### Opção C: [Nome]
- **Prós:** [lista]
- **Contras:** [lista]
- **Risco:** [baixo | médio | alto]

## Decisão
[Qual opção foi escolhida e por quê?]

## Consequências Esperadas
[O que esperamos que aconteça como resultado?]

## Responsável
[Quem é accountable pela implementação?]

## Prazo de Revisão
[Quando revisaremos se a decisão foi acertada?]

## Resultado (preenchido depois)
[O que realmente aconteceu?]
```

## Processo de Decisão

1. **Identificar** — Reconhecer que uma decisão é necessária
2. **Documentar contexto** — Escrever o contexto e problema
3. **Levantar opções** — Mínimo 2, ideal 3 opções
4. **Consultar stakeholders** — Quem é afetado deve ser ouvido
5. **Decidir** — Escolher e registrar a justificativa
6. **Comunicar** — Informar todos os afetados
7. **Implementar** — Executar a decisão
8. **Revisar** — No prazo definido, avaliar o resultado

## Classificação de Decisões

| Tipo | Reversibilidade | Quem Decide | Exemplo |
|------|----------------|-------------|---------|
| Tipo 1 | Irreversível | Liderança + comunidade | Mudar a tese central |
| Tipo 2 | Reversível | Liderança | Mudar canal principal |
| Tipo 3 | Facilmente reversível | Qualquer contribuidor | Ajustar frequência de ritual |

## Regras

1. **Toda decisão Tipo 1 deve ser documentada** — sem exceção
2. **Decisões Tipo 2 devem ser documentadas** se afetam mais de 10 pessoas
3. **O registro deve ser feito antes da implementação**
4. **Revisão é obrigatória** no prazo definido
5. **Decisões revertidas devem explicar o porquê**

## Arquivo

- Decisões vivem em `archive/decisions/`
- Nomeadas como `decision-YYYY-MM-DD-titulo-curto.md`
- Indexadas por data e status
- Decisões revertidas mantidas para aprendizado

## Anti-padrões

- **Decisão sem registro**: se não foi escrito, não foi decidido
- **Decisão sem opções**: se só considerou uma opção, não decidiu
- **Decisão sem prazo de revisão**: decisão sem feedback loop é permanente por acidente
- **Decisão retroativa**: registrar depois de implementar perde o valor
