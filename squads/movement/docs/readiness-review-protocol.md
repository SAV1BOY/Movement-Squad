---
id: readiness-review-protocol
name: "Readiness Review Protocol"
squad: movement
type: doc
category: governance
tags:
  - readiness
  - review
  - governanca
  - lancamento
  - quality-gate
---

# Readiness Review Protocol — Protocolo de Revisão de Prontidão

## Objetivo

O Readiness Review é uma revisão estruturada que acontece antes de marcos
críticos do movimento: lançamento, escala e encerramento. Garante que o squad
tem tudo pronto antes de avançar, evitando lançamentos prematuros, escalas
sem sustentação e encerramentos sem captura de legado.

---

## Quando Aplicar

| Tipo | Momento | Exemplo |
|------|---------|---------|
| **Pre-Launch** | Antes de lançar o movimento publicamente | Tese validada, identidade definida, canais prontos |
| **Pre-Scaling** | Antes de escalar distribuição ou comunidade | Métricas saudáveis, processos estáveis, time preparado |
| **Pre-Sunset** | Antes de iniciar processo de encerramento | Critérios de sunset atingidos, legado mapeado |

---

## Quem Participa

| Papel | Responsabilidade na Review |
|-------|---------------------------|
| **Movement Chief** | Conduz a review, decide Go/No-Go |
| **Movement Architect** | Apresenta estado da arquitetura e sistemas |
| **Analista de Impacto** | Apresenta métricas e health score |
| **Stakeholders** | Validam alinhamento com objetivos de negócio |
| **Agentes do domínio** | Respondem perguntas sobre seus entregáveis |

---

## Formato da Review

### Agenda (60 minutos)

1. **Contexto e objetivo** (5 min) — Chief apresenta o marco e por que a review é necessária
2. **Estado atual** (15 min) — Architect apresenta visão geral, dependências, riscos
3. **Métricas** (10 min) — Analista apresenta dados quantitativos e health score
4. **Checklist de Readiness** (15 min) — Revisão item por item do checklist
5. **Riscos e mitigações** (10 min) — Discussão de riscos abertos
6. **Decisão** (5 min) — Chief declara Go / Go com condições / No-Go

### Regras

- Decisão é do Chief, mas deve considerar input de todos
- Se qualquer item crítico do checklist estiver vermelho, é No-Go automático
- Review deve ser registrada em `data/readiness-reviews/`

---

## Checklist de Readiness

### Pre-Launch

- [ ] Tese do movimento validada e documentada
- [ ] Identidade coletiva definida (enemy, dream, códigos)
- [ ] Manifesto ou artefato fundacional criado e aprovado
- [ ] Canais de distribuição definidos e configurados (mínimo 3)
- [ ] Rituais inaugurais desenhados e testados
- [ ] Métricas e dashboard configurados
- [ ] Plano de lançamento sequenciado (framework `launch-sequencing`)
- [ ] Ethics check aprovado (`governance/ethics-and-boundaries`)
- [ ] Risk log atualizado com mitigações definidas
- [ ] Stakeholders alinhados e informados

### Pre-Scaling

- [ ] Health Score acima do threshold mínimo por 4+ semanas
- [ ] Processos operacionais documentados e estáveis
- [ ] Champion program ativo com champions engajados
- [ ] Canais diversificados (nenhum com >60% de concentração)
- [ ] Earned media positivo e crescente
- [ ] Capacidade do time suficiente para volume maior
- [ ] Playbook de crise documentado e testado
- [ ] Experimentos de escala validados (ver experiment-log)
- [ ] Budget e recursos aprovados para escala
- [ ] Cross-squad handoffs funcionando sem atrito

### Pre-Sunset

- [ ] Critérios de sunset atingidos (conforme `movement-sunset-framework`)
- [ ] Comunicação planejada para comunidade e stakeholders
- [ ] Plano de captura de legado definido
- [ ] Destino de ativos reutilizáveis mapeado
- [ ] Champions e parceiros notificados
- [ ] Timeline de encerramento definida
- [ ] Debriefings agendados com time core
- [ ] Arquivo estruturado preparado
- [ ] Lessons learned em andamento
- [ ] Stakeholders aprovaram decisão de sunset

---

## Critérios de Decisão

| Decisão | Critério | Ação |
|---------|----------|------|
| **Go** | Todos os itens do checklist verdes ou amarelos com mitigação | Avançar para o próximo marco |
| **Go com condições** | Maioria verde, até 2 itens amarelos sem mitigação definida | Avançar, mas resolver condições em até 7 dias |
| **No-Go** | Qualquer item crítico vermelho, ou 3+ itens amarelos | Não avançar. Definir plano de ação e reagendar review |

---

## Registro

Cada review deve ser registrada em `data/readiness-reviews/` com o formato:

```yaml
# data/readiness-reviews/YYYY-MM-DD-[tipo]-review.yaml
review:
  data: "YYYY-MM-DD"
  tipo: "" # pre-launch | pre-scaling | pre-sunset
  movimento: ""
  participantes: []
  decisao: "" # go | go-com-condicoes | no-go
  condicoes: [] # se go-com-condições
  itens_vermelhos: [] # se no-go
  plano_de_acao: []
  proxima_review: "" # data, se aplicável
  registrado_por: ""
```

---

## Exemplo Preenchido

```yaml
review:
  data: "2026-03-15"
  tipo: "pre-scaling"
  movimento: "Sexta do Fracasso"
  participantes:
    - movement-chief
    - movement-architect
    - analista-de-impacto
    - stakeholder-marketing
  decisao: "go-com-condicoes"
  condicoes:
    - "Diversificar canais: Twitter está com 65% de concentração. Reduzir para <60% em 7 dias."
    - "Documentar playbook de crise até 2026-03-22."
  itens_vermelhos: []
  plano_de_acao:
    - acao: "Estrategista-de-ciclo cria plano de diversificação para LinkedIn e newsletter"
      responsavel: "estrategista-de-ciclo"
      prazo: "2026-03-22"
    - acao: "Chief documenta playbook de crise"
      responsavel: "movement-chief"
      prazo: "2026-03-22"
  proxima_review: "2026-03-29"
  registrado_por: "movement-architect"
```

---

## Referências

- `config.yaml` seção `quality_gates` — Gates obrigatórios
- `docs/quality-gate-cascade.md` — Cascata completa de quality gates
- `data/risk-log.yaml` — Registro de riscos
- `frameworks/movement-lifecycle-framework.md` — Ciclo de vida do movimento
- `frameworks/movement-sunset-framework.md` — Framework de encerramento
