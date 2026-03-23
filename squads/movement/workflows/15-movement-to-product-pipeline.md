---
id: movement-to-product-pipeline
name: "Pipeline: Engajamento → Trial → Conversão"
squad: movement
type: workflow
agents: [estrategista-de-ciclo, analista-de-impacto, movement-architect]
cadence: monthly
version: "1.0"
tags: [workflow, produto, conversao, pipeline, engajamento, trial]
---

# Pipeline: Engajamento → Trial → Conversão

## Objetivo

Gerenciar o pipeline de conversão do movimento para o produto — otimizando os caminhos orgânicos pelos quais membros engajados com a causa se tornam clientes — sem comprometer a autenticidade do movimento.

## Diagrama de Fases

```
[ENGAJAMENTO]     [CONSIDERAÇÃO]    [TRIAL]           [CONVERSÃO]       [ADVOCACY]
Membro ativo  →   Interesse no  →   Experimenta   →   Torna-se      →   Recomenda
no movimento      produto           o produto         cliente           a outros
   |                 |                  |                  |                  |
   v                 v                  v                  v                  v
Participa de     Descobre          Free trial,       Ativa/compra,    Referral,
rituais,         funcionalidade    demo, desconto    usa produto      review,
cria conteúdo    via movimento     de membro                          case study
```

## Fases Detalhadas

### Fase 1: Engajamento no Movimento (Contínuo)

**Agentes:** movement-architect

**Inputs:**
- Membros ativos na comunidade
- Dados de engajamento por membro
- Coupling Map definido

**Ações:**
1. Manter membros engajados com conteúdo e rituais de valor puro (sem push de produto)
2. Rastrear nível de engajamento e comprometimento com a causa
3. Identificar membros com alto engajamento que ainda não são clientes
4. Criar valor genuíno independente do produto

**Outputs:**
- Base de membros engajados
- Segmento de "engajados não-clientes" identificado

**Decision Gate:**
- Base de engajados sólida → alimentar naturalmente a consideração
- Engajamento baixo → focar em comunidade antes de pensar em conversão

### Fase 2: Consideração Natural (Contínuo)

**Agentes:** estrategista-de-ciclo, manifestador

**Inputs:**
- Coupling Map com momentos de transição
- Conteúdo-ponte produzido
- Regras de menção ao produto

**Ações:**
1. Publicar conteúdo-ponte nos momentos corretos: tutoriais, cases da comunidade, demos contextualizados
2. Incorporar produto organicamente em rituais (quando faz sentido)
3. Champions recomendam autenticamente em contextos relevantes
4. Responder perguntas sobre produto quando surgem organicamente
5. NÃO empurrar produto — criar condições para descoberta natural

**Outputs:**
- Conteúdo-ponte publicado
- Menções orgânicas rastreadas
- Perguntas sobre produto respondidas

**Decision Gate:**
- Interesse orgânico surgindo → facilitar trial
- Zero interesse → verificar coupling (produto não conecta com movimento?)

### Fase 3: Trial e Experiência (Mensal)

**Agentes:** estrategista-de-ciclo, movement-architect

**Inputs:**
- Membros que demonstraram interesse
- Benefícios exclusivos para membros
- Landing pages de conversão

**Ações:**
1. Oferecer trial/demo exclusivo para membros do movimento
2. Criar experiência de onboarding de produto conectada com a causa
3. Acompanhar jornada de trial: ativação, uso, pontos de atrito
4. Coletar feedback durante trial
5. Oferecer suporte personalizado via comunidade

**Outputs:**
- Trials ativados por membros
- Jornada de trial rastreada
- Feedback coletado

**Decision Gate:**
- Trial → Ativação alta → caminho para conversão
- Trial → Ativação baixa → investigar friction no produto

### Fase 4: Conversão e Ativação (Contínuo)

**Agentes:** analista-de-impacto

**Inputs:**
- Dados de trial e ativação
- Ofertas exclusivas para membros
- Dados de conversão

**Ações:**
1. Rastrear conversão de trial para cliente pago
2. Oferecer condições exclusivas para membros do movimento
3. Comparar taxa de conversão membros vs. não-membros
4. Calcular CAC via movimento vs. outros canais
5. Acompanhar LTV de clientes vindos do movimento

**Outputs:**
- Dados de conversão rastreados
- CAC e LTV calculados
- Comparação membros vs. não-membros

**Decision Gate:**
- Conversão alta + LTV alto → movimento gera clientes de qualidade
- Conversão alta + LTV baixo → produto não entrega promessa do movimento
- Conversão baixa → revisar coupling e trial experience

### Fase 5: Advocacy e Referral (Contínuo)

**Agentes:** movement-architect, analista-de-impacto

**Inputs:**
- Clientes vindos do movimento
- Programa de referral
- NPS data

**Ações:**
1. Medir NPS de clientes-membros vs. clientes regulares
2. Ativar programa de referral entre membros
3. Convidar para case studies e testimonials
4. Nutrir ciclo: cliente satisfeito → champion → traz mais membros → mais clientes

**Outputs:**
- NPS comparativo
- Referrals rastreados
- Cases produzidos

**Decision Gate:**
- NPS alto + referrals ativos → ciclo virtuoso funcionando
- NPS baixo → problema de produto, não de movimento

## Cadência

- **Engajamento e consideração:** Contínuo
- **Trial management:** Mensal
- **Conversão tracking:** Semanal
- **Pipeline review:** Mensal
- **ROI analysis:** Trimestral

## Artefatos Produzidos

- Pipeline dashboard
- Conversion pathway report
- CAC/LTV comparativo
- Referral program report
- Cases de clientes-membros

## Métricas de Sucesso

| Métrica | Meta |
|---------|------|
| Trial rate (membro → trial) | >= 10% |
| Conversão (trial → cliente) | >= 20% |
| CAC via movimento vs. outros | >= 30% menor |
| LTV membro vs. não-membro | >= 20% maior |
| NPS membro-cliente | >= 70 |
| Referral rate | >= 15% dos membros-clientes |

## Integração

| Tipo | Referência |
|------|-----------|
| **Tasks** | `tasks/strategy/plan-movement-to-product-coupling.md`, `tasks/measurement/measure-business-impact.md`, `tasks/measurement/analyze-cohort-retention.md` |
| **Frameworks** | `frameworks/movement-to-product-coupling.md`, `frameworks/product-led-movement-framework.md`, `frameworks/impact-movement-attribution.md`, `frameworks/impact-metrics-model.md` |
| **Checklists** | `checklists/movement-to-product-fit-quality.md`, `checklists/chief/chief-alignment-with-business.md`, `checklists/impacto/causal-attribution-sanity.md` |
| **Registries** | `data/registries/decision-log.yaml`, `data/metrics/business-impact.md` |

### Níveis de Quality Gate Aplicáveis
- **Nível 2 (Task Gate):** Checklists de product-fit e atribuição causal aplicados em cada fase
- **Nível 4 (Chief Gate):** Movement Chief valida coupling map e decisões de conversão
- **Nível 6 (HRM Gate):** Stakeholder humano aprova estratégia de monetização do movimento

### Regras de Fluxo
- **Quality Gate entre fases:** Engajamento→Trial: touchpoints gerando consideração; Trial→Conversão: ativação alta; Conversão→Advocacy: NPS alto + referrals ativos
- **Rework:** Se conversão baixa → revisar coupling e trial experience
- **Escalation:** Se LTV baixo apesar de conversão alta → problema de produto, escalar para stakeholders
- **Handoff:** CAC/LTV e pipeline data alimentam → `workflows/16-quarterly-movement-review.md` e relatórios para stakeholders
