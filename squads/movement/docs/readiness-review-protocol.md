---
id: readiness-review-protocol
name: "Protocolo de Readiness Review (Go/No-Go)"
squad: movement
type: doc
category: docs
version: 1.0.0
tags: [readiness, go-no-go, protocolo, lançamento, revisão]
---

# Protocolo de Readiness Review (Go/No-Go)

## Visão Geral

O protocolo de Readiness Review é o processo formal de go/no-go antes de lançamentos
e transições de fase. Ele garante que ninguém avance para uma fase de alto investimento
sem que as condições mínimas estejam atendidas. Uma review bem conduzida evita
lançamentos prematuros e retrabalho caro.

## Quando Aplicar

| Momento | Tipo de Review | Criticidade |
|---------|---------------|-------------|
| Antes de lançar movimento novo | Full review | Alta — sem review, sem lançamento |
| Transição seed → growth | Review focada | Alta — escalar sem base é perigoso |
| Antes de escala significativa | Full review + capacidade | Alta — escala amplifica problemas |
| Pós-pivot, antes de reativar | Review de revalidação | Média — pivot muda premissas |
| Antes de parceria estratégica | Review focada (reputação) | Média — parceiro herda riscos |

## Checklist de Readiness (10 Itens)

Antes da review, o time deve preparar evidências para cada item.

### Bloco 1: Fundação

- [ ] **1. Tese articulada e validada** — Existe documento de tese com inimigo, sonho
  e mecanismo? Foi validada com público real (mínimo 10 pessoas)?

- [ ] **2. Identidade pronta para uso** — Nome, linguagem, símbolos e manifesto estão
  finalizados e testados? Early adopters já usam a linguagem?

- [ ] **3. Win conditions definidas** — Existem 3-7 win conditions mensuráveis com
  baseline, target e prazo?

### Bloco 2: Execução

- [ ] **4. Artefatos prontos para 2 semanas** — Existe conteúdo suficiente para manter
  cadência por 14 dias pós-lançamento sem produção emergencial?

- [ ] **5. Calendário de distribuição definido** — Canais, formatos, frequência e
  responsáveis estão definidos para as primeiras 4 semanas?

- [ ] **6. Comunidade seed ativada** — Mínimo 10 membros engajados, com champions
  identificados e pelo menos 1 ritual testado?

### Bloco 3: Infraestrutura

- [ ] **7. Métricas instrumentadas** — Dashboard configurado, tracking ativo, baseline
  medido para todos os KPIs?

- [ ] **8. Processos operacionais definidos** — Cadência do loop, responsabilidades,
  quality gates e handoffs documentados?

### Bloco 4: Proteção

- [ ] **9. Riscos mapeados** — Risk log atualizado com mitigações para riscos de
  severidade alta e crítica?

- [ ] **10. Compliance verificado** — Revisão jurídica (se aplicável), permissões de
  UGC, direitos de imagem, regulações setoriais verificados?

## Quem Participa

| Papel | Responsabilidade na Review |
|-------|--------------------------|
| Chief of Movement | Lidera a sessão, toma decisão final, documenta |
| Strategist / Lead | Apresenta evidências de tese e estratégia |
| Creator Lead | Apresenta status de artefatos e calendário |
| Community Lead | Apresenta status da comunidade seed |
| Analyst | Apresenta métricas, baseline e instrumentação |
| Stakeholder (opcional) | Fornece perspectiva externa, valida alinhamento |

**Tamanho ideal:** 4-6 pessoas. Menos que 4 falta perspectiva. Mais que 6 vira plenário.

## Formato da Review

### Preparação (48h antes)

1. Organizador distribui checklist com 10 itens para autoavaliação
2. Cada lead preenche os itens de seu domínio com evidências
3. Organizador consolida em documento único e distribui para todos

### Sessão (90 minutos)

```
00-10 min  → Contexto e objetivo da review (Chief)
10-25 min  → Bloco 1: Fundação (Strategist apresenta, todos avaliam)
25-40 min  → Bloco 2: Execução (Creator + Community apresentam)
40-55 min  → Bloco 3: Infraestrutura (Analyst apresenta)
55-65 min  → Bloco 4: Proteção (Chief + Legal apresentam)
65-80 min  → Discussão aberta: gaps, riscos, condições
80-90 min  → Decisão formal: GO / GO condicional / NO-GO
```

### Regras da Sessão

- Cada bloco: apresentação de 5 min + discussão de 10 min
- Avaliadores pontuam independentemente usando a `readiness-review-rubric`
- Divergências > 5 pontos em uma dimensão devem ser discutidas
- Decisão final é do Chief, mas dissidências são registradas
- Nenhum item pode ser "não sei" — se não há evidência, a resposta é "não"

## Critérios de Decisão

### GO (Pontuação 100-125)

- Todas as dimensões da rubric acima de 15 pontos
- Nenhum item do checklist como "não"
- Riscos mapeados com mitigação definida
- **Ação:** Lançar conforme planejado

### GO Condicional (Pontuação 75-99)

- Nenhuma dimensão abaixo de 11 pontos
- Máximo 2 itens do checklist como "não" (não críticos)
- **Ação:** Lançar com plano de mitigação para dimensões fracas
- **Condição:** Items pendentes resolvidos em até 7 dias pós-lançamento
- **Monitoramento:** Daily check nas primeiras 2 semanas

### NO-GO (Pontuação 0-74)

- Qualquer dimensão abaixo de 11 pontos
- 3+ itens do checklist como "não"
- **Ação:** Não lançar. Definir plano de ação para resolver gaps
- **Reavaliação:** Agendar nova review em 7-14 dias
- **Comunicação:** Informar stakeholders sobre novo prazo

### Critérios de Veto Automático (NO-GO independente da pontuação)

1. Tese não foi testada com nenhuma pessoa real
2. Nenhuma métrica está instrumentada
3. Não existe comunidade seed (zero membros engajados)
4. Risco de severidade crítica sem mitigação
5. Stakeholder principal não deu sign-off

## Registro

### Documento de Registro

```yaml
readiness_review:
  id: "RR-XXX"
  data: YYYY-MM-DD
  movimento: ""
  fase: ""
  participantes: []
  checklist:
    tese_validada: true/false
    identidade_pronta: true/false
    win_conditions: true/false
    artefatos_prontos: true/false
    calendário_distribuição: true/false
    comunidade_seed: true/false
    métricas_instrumentadas: true/false
    processos_definidos: true/false
    riscos_mapeados: true/false
    compliance_verificado: true/false
  rubric_scores:
    tese_validada: 0
    identidade_pronta: 0
    artefatos_prontos: 0
    comunidade_seed: 0
    métricas_baseline: 0
    total: 0
  decisão: "" # GO | GO-CONDICIONAL | NO-GO
  condições: []
  gaps: []
  plano_de_ação: []
  próxima_review: "" # data, se NO-GO
  dissidências: []
```

### Onde Armazenar

- Registro em `data/readiness-reviews/RR-XXX-[nome]-[data].yaml`
- Referência no decision log do squad

## Exemplos

### Exemplo: GO Condicional

**Contexto:** Movimento de design acessível, review pré-lançamento.

**Scores:** Tese: 22, Identidade: 18, Artefatos: 14, Comunidade: 16, Métricas: 12. Total: 82.

**Checklist:** 8/10 ✓. Pendentes: artefatos para YouTube (em produção) e compliance de acessibilidade do site (em revisão).

**Decisão:** GO Condicional. Lançar em redes sociais conforme planejado. YouTube ativado em 5 dias quando artefatos estiverem prontos. Site revisado em 7 dias.

### Exemplo: NO-GO

**Contexto:** Movimento de produtividade consciente, review pré-escala.

**Scores:** Tese: 20, Identidade: 8, Artefatos: 11, Comunidade: 19, Métricas: 15. Total: 73.

**Diagnóstico:** Identidade fraca — membros não usam a linguagem do movimento. Artefatos no mínimo.

**Decisão:** NO-GO. Investir 2 semanas em fortalecimento de identidade (workshop com comunidade, teste de linguagem, iteração de símbolos). Nova review em 14 dias.

## Integração

- Rubrica detalhada em `lib/utilities/readiness-review-rubric`
- Registros armazenados em `data/readiness-reviews/`
- Decisão segue `movement-governance-framework` (Camada 3)
- Métricas conectadas ao `movement-health-score-framework`
- Riscos classificados pela `risk-taxonomy`
