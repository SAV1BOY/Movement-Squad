---
id: movement-governance-framework
name: "Movement Governance Framework"
squad: movement
type: framework
category: core
version: "1.0"
tags: [governança, decisão, aprovação, escalação, compliance, operacional]
---

# Movement Governance Framework

## Overview

O Movement Governance Framework define como decisões são tomadas, aprovadas, escaladas e revertidas dentro do HRM (Human Resource for Movements). Movimentos sem governança clara acabam em dois extremos: paralisia por consenso ou caos por falta de accountability. Este framework encontra o equilíbrio — velocidade com responsabilidade.

A tese central: governança não é burocracia. Governança é a estrutura que permite ao time tomar decisões rápidas e corretas com confiança. Sem ela, cada decisão vira uma negociação ad hoc. Com ela, o time sabe exatamente quem decide o quê, quando escalar e como reverter.

---

## Princípios de Governança

### 1. Decisão no nível mais baixo possível
Cada decisão deve ser tomada pelo nível mais próximo da execução que tenha contexto suficiente. Escalar desnecessariamente é tão danoso quanto não escalar quando necessário.

### 2. Velocidade com reversibilidade
Decisões reversíveis devem ser tomadas rápidas. Decisões irreversíveis merecem mais deliberação. A maioria das decisões operacionais é reversível — trate-as assim.

### 3. Accountability explícita
Para cada decisão, uma pessoa é accountable. Isso não significa que decide sozinha, mas que é responsável pelo resultado. Accountability compartilhada é accountability de ninguém.

### 4. Transparência de racional
Toda decisão significativa deve ter o racional documentado. Não basta saber O QUE foi decidido — é essencial saber POR QUÊ.

### 5. Dissidência registrada
Quem discordou deve ter sua posição registrada. Isso protege a diversidade de pensamento e permite revisitar decisões com contexto completo.

### 6. Revisão periódica
Nenhuma decisão é permanente. Decisões estratégicas são revisadas a cada 90 dias. Decisões operacionais são revisadas no ciclo Kaizen semanal.

---

## Camadas de Decisão

### Camada 1: Agent (Decisão Individual)

| Aspecto | Definição |
|---------|-----------|
| Quem | Qualquer agent do squad no exercício de seu papel |
| Escopo | Decisões táticas dentro do domínio de responsabilidade |
| Exemplos | Escolha de formato de conteúdo, priorização de tarefas do dia, tom de resposta em comunidade |
| Tempo de decisão | Imediato (minutos) |
| Aprovação necessária | Nenhuma |
| Documentação | Registro no task log |
| Reversão | Autoautorizada |

### Camada 2: Team (Decisão Coletiva Operacional)

| Aspecto | Definição |
|---------|-----------|
| Quem | 2+ agents do squad, incluindo o lead do domínio |
| Escopo | Decisões que afetam múltiplos domínios ou a cadência do sprint |
| Exemplos | Calendário editorial da semana, priorização de experimentos, ajuste de ritual |
| Tempo de decisão | Até 24h |
| Aprovação necessária | Consenso dos envolvidos ou decisão do lead |
| Documentação | Decision log com racional |
| Reversão | Autorizada pelo lead do domínio |

### Camada 3: Chief (Decisão Estratégica)

| Aspecto | Definição |
|---------|-----------|
| Quem | Chief of Movement com input dos leads |
| Escopo | Decisões que afetam direção do movimento, budget ou posicionamento público |
| Exemplos | Pivot de tese, alocação de budget, parceria estratégica, decisão de escala ou sunset |
| Tempo de decisão | Até 72h |
| Aprovação necessária | Chief com input documentado dos leads |
| Documentação | Decision log formal com racional, alternativas e dissidências |
| Reversão | Requer nova sessão de decisão |

### Camada 4: Stakeholder (Decisão de Alto Impacto)

| Aspecto | Definição |
|---------|-----------|
| Quem | Stakeholders externos + Chief |
| Escopo | Decisões que impactam marca corporativa, budget significativo ou exposição pública |
| Exemplos | Lançamento de movimento novo, sunset definitivo, comunicação de crise, investimento > threshold |
| Tempo de decisão | Até 1 semana (exceto crise) |
| Aprovação necessária | Sign-off formal de stakeholders |
| Documentação | Ata formal com sign-off documentado |
| Reversão | Requer novo ciclo de aprovação |

---

## Protocolo de Aprovação

### Fluxo Padrão

```
Agent identifica necessidade de decisão
  ↓
Classifica a camada (1-4)
  ↓
Se Camada 1 → decide e registra
Se Camada 2 → convoca envolvidos, decide em até 24h
Se Camada 3 → prepara brief para Chief, sessão em até 72h
Se Camada 4 → Chief prepara brief para stakeholders, sessão em até 1 semana
  ↓
Decisão documentada com racional
  ↓
Comunicada aos afetados
```

### Critérios de Classificação

| Pergunta | Se Sim | Se Não |
|----------|--------|--------|
| Afeta só meu domínio? | Camada 1 | Camada 2+ |
| Afeta múltiplos domínios? | Camada 2 | Verificar próxima |
| Envolve budget, posicionamento público ou direção? | Camada 3 | Camada 2 |
| Impacta marca corporativa ou requer sign-off externo? | Camada 4 | Camada 3 |

---

## Protocolo de Escalação

### Quando Escalar

- Decisão ultrapassa o escopo da camada atual
- Há divergência irresolúvel entre agents/leads
- Risco identificado com severidade alta ou crítica
- Prazo de decisão da camada atual está estourando
- Informação insuficiente para decidir no nível atual

### Como Escalar

```yaml
escalação:
  de: "" # quem está escalando
  para: "" # para quem está escalando
  motivo: "" # por que está escalando
  contexto: "" # resumo da situação em 5 linhas
  opções: [] # opções já consideradas com prós e contras
  recomendação: "" # o que o escalante recomenda
  prazo: "" # até quando a decisão é necessária
  impacto_de_atraso: "" # o que acontece se demorar
```

### Regras de Escalação

1. Nunca escale sem recomendação — traga o problema E a sugestão de solução
2. Nunca escale mais de uma camada de vez — respeite a hierarquia
3. Escale cedo, não tarde — escalar na véspera do prazo não é escalar, é transferir culpa
4. Documente a escalação — registro protege todos os envolvidos

---

## Protocolo de Kill/Pivot

### Quando Acionar

- Métricas abaixo do threshold por 4+ semanas consecutivas
- Tese invalidada por experimento formal
- Contexto cultural mudou fundamentalmente
- Custo supera 2x o orçamento sem perspectiva de retorno

### Processo de Kill

```
Analyst identifica padrão de declínio
  ↓
Prepara brief com evidências (Camada 3)
  ↓
Chief convoca sessão de decisão
  ↓
Opções: Kill | Pivot | Continuar com ajustes
  ↓
Se Kill → encaminhar para movement-sunset/
Se Pivot → encaminhar para movement-pivot/
Se Continuar → definir condições e prazo de reavaliação
```

### Critérios para Kill vs. Pivot

| Indicador | Kill | Pivot |
|-----------|------|-------|
| Tese | Não ressoa com ninguém | Ressoa mas execução falha |
| Comunidade | Sem engajamento orgânico | Engajada mas não cresce |
| Custo | Insustentável em qualquer cenário | Sustentável com mudança de canal/formato |
| Contexto | Mudou permanentemente | Mudou mas há adaptação possível |

---

## Protocolo de Rework

### Quando Acionar

- Artefato rejeitado em quality gate
- Handoff classificado como REVIEW ou REJECT
- Experimento inconclusivo que precisa de redesign
- Feedback negativo consistente da comunidade sobre um output

### Processo de Rework

```
Rejeição identificada com feedback específico
  ↓
Owner original recebe feedback documentado
  ↓
Owner analisa e propõe plano de rework (24h)
  ↓
Lead aprova plano de rework
  ↓
Execução do rework com prazo definido
  ↓
Resubmissão para quality gate
  ↓
Se aprovado → prosseguir
Se rejeitado novamente → escalar para Camada 3
```

### Regras de Rework

1. Máximo 2 ciclos de rework — se não passar na terceira, escalar
2. Feedback deve ser específico e acionável — "melhorar" não é feedback
3. Prazo de rework não pode exceder o prazo original — rework com prazo infinito é retrabalho disfarçado
4. Rework não muda o escopo — se o problema é o escopo, é decisão de Camada 2+

---

## Auditoria e Compliance

### Cadência de Auditoria

| Tipo | Frequência | Escopo | Responsável |
|------|-----------|--------|-------------|
| Auditoria de decisões | Mensal | Revisar decision logs, verificar accountability | Chief |
| Auditoria de quality gates | Quinzenal | Verificar se gates estão sendo aplicados | Leads |
| Auditoria de riscos | Quinzenal | Revisar risk log, atualizar status | Analyst |
| Auditoria de compliance | Trimestral | Verificar aderência a protocolos e ética | Chief + Stakeholders |

### Registro de Auditoria

```yaml
auditoria:
  data: YYYY-MM-DD
  tipo: "" # decisões | quality-gates | riscos | compliance
  auditor: ""
  período_auditado: "" # ex: 2026-02-01 a 2026-02-28
  achados:
    - achado: ""
      severidade: "" # alta | média | baixa
      ação_recomendada: ""
  status_geral: "" # conforme | com-ressalvas | não-conforme
  próxima_auditoria: ""
```

---

## Exemplo Detalhado

**Contexto:** O time detecta que o ritual "Sexta do Fracasso" está gerando alguns
relatos de que empresas estão usando as confissões contra os autores. É um risco
reputacional para o movimento.

**Camada 1 (Agent):** Community architect percebe 3 relatos em 1 semana. Registra
no risk log como RSK-004 com severidade "alto" (prob. média × impacto alto).

**Escalação para Camada 2 (Team):** Community architect escala para o time com
contexto, 3 opções (pausar ritual, adicionar disclaimer, criar modo anônimo) e
recomendação (modo anônimo). Time se reúne em 12h.

**Decisão Camada 2:** Time decide implementar modo anônimo como teste de 2 semanas
(decisão reversível). Narrative architect cria template anônimo. Decision log
atualizado.

**Monitoramento:** Após 2 semanas, 60% dos participantes usam modo anônimo. Relatos
de uso negativo caem a zero. Team decide manter modo anônimo como opção permanente.

**Se tivesse escalado:** Se o risco envolvesse exposição em mídia (impacto em marca
corporativa), escalaria para Camada 3 (Chief) ou Camada 4 (Stakeholders) com
recomendação de pausa imediata do ritual até resolução.

---

## Cross-references

- [[movement-engine-5-loop]] — Gates de decisão em cada etapa do loop seguem este framework
- [[ralphloop-kaizen]] — Decisões de melhoria no ciclo semanal classificadas por camada
- [[chief-risk-appetite-framework]] — Define o apetite de risco que informa decisões
- [[risk-taxonomy]] — Classificação de riscos usada no protocolo de escalação
- [[cross-squad-handoff-rubric]] — Quality gate de handoff gera rework via este framework
- [[readiness-review-rubric]] — Decisão de go/no-go segue protocolo de Camada 3
