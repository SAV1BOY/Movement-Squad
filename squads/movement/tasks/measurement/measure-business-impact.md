---
id: measure-business-impact
name: "Medir Impacto em Negócio"
squad: movement
type: task
category: measurement
agents: [analista-impacto, estrategista-movimento]
frameworks: [business-impact-framework, attribution-model]
checklists: [business-metrics-checklist, attribution-checklist]
templates: [business-impact-report-template, roi-calculation-template]
version: "1.0"
tags: [measurement, negocio, impacto, roi, conversao, atribuicao]
---

# Medir Impacto em Negócio

## Objetivo

Quantificar o impacto do movimento nas métricas de negócio da empresa — awareness, consideração, conversão, retenção e advocacy — demonstrando com dados que o investimento em movimento cultural gera retorno tangível além do valor cultural.

## Contexto

Movimentos culturais geram valor intangível (brand equity, cultural relevance) e tangível (leads, conversão, retention). Sem medir o tangível, o movimento vive sob ameaça constante de corte de budget. Este task constrói a ponte entre "fizemos algo incrível culturalmente" e "isso gerou resultado para o negócio".

## Inputs Necessários

- Win Conditions com metas de negócio
- Coupling Map movimento-produto
- Dados de CRM/vendas/conversão
- Dados de tráfego e atribuição
- Dados de NPS e customer satisfaction
- Baseline pré-movimento para comparação

## Processo

1. **Definir métricas de negócio rastreáveis** — Selecionar: (a) Awareness (search volume da marca, SOV), (b) Consideração (visitas ao site, trials, downloads), (c) Conversão (vendas, sign-ups, ativações), (d) Retenção (churn rate, LTV), (e) Advocacy (NPS, referrals, reviews positivos).

2. **Configurar modelo de atribuição** — Definir como atribuir resultados ao movimento: (a) UTMs em todos os links do movimento, (b) Landing pages específicas, (c) Códigos promocionais por canal, (d) Pesquisa "como nos conheceu", (e) Comparação temporal (antes vs. depois).

3. **Estabelecer baseline** — Documentar todas as métricas no dia 0 (antes do movimento ou no início do ciclo). Sem baseline, não há como provar impacto.

4. **Segmentar audience do movimento** — Criar segmento de "membros do movimento" no CRM/analytics para comparar: taxa de conversão de membros vs. não-membros, LTV de membros vs. não-membros, NPS de membros vs. não-membros.

5. **Rastrear funil do movimento** — Medir: alcance do movimento → engajamento → visita ao produto → trial/demo → conversão → retenção. Identificar onde o funil afunila mais.

6. **Calcular custo por resultado** — Comparar: custo do movement squad + ativações vs. resultados gerados. Calcular: CAC via movimento, custo por lead qualificado, custo por community member que converte.

7. **Medir impacto em brand equity** — Rastrear indicadores de percepção de marca: brand awareness (pesquisas), brand consideration, brand preference, atributos de marca associados ao movimento.

8. **Analisar correlações temporais** — Cruzar timeline de ações do movimento com picos/vales de métricas de negócio. Correlação não é causalidade, mas padrões consistentes são evidência forte.

9. **Produzir Business Impact Report** — Mensal: relatório com todas as métricas, comparação com baseline e metas, ROI estimado, insights sobre o que converte e o que não converte.

10. **Apresentar para stakeholders** — Preparar narrativa de impacto: não apenas números, mas a história de como o movimento gera valor. Usar mix de dados quantitativos e histórias qualitativas.

## Outputs Esperados

- **Dashboard de business impact** configurado
- **Modelo de atribuição** funcionando
- **Segmento de membros** criado no CRM/analytics
- **Business Impact Report** mensal
- **Cálculo de ROI** atualizado
- **Apresentação para stakeholders** trimestral

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Métricas rastreadas | >= 5 métricas de negócio |
| Atribuição | Modelo configurado e funcional |
| Baseline | Documentado para todas as métricas |
| Segmento de membros | Criado e populado |
| Report mensal | Entregue com comparação vs. baseline |
| ROI | Calculado (mesmo que estimado) |

## Decision Points

- **ROI positivo e crescente** → Argumentar por mais investimento no movimento
- **ROI negativo após 90 dias** → Revisar coupling map e funil de conversão
- **Membros convertem mais mas retêm igual** → Foco em deepening commitment pós-conversão
- **Impact não mensurável** → Investir em infraestrutura de medição antes de continuar

## Integração

| Tipo | Referência |
|------|-----------|
| **Frameworks** | `frameworks/impact-movement-attribution.md`, `frameworks/impact-metrics-model.md` |
| **Checklists** | `checklists/impacto/causal-attribution-sanity.md`, `checklists/chief/chief-alignment-with-business.md` |
| **Templates** | `templates/reports/movement-impact-report.md` |
| **Registries** | `data/metrics/business-impact.md` |
| **Workflows** | `workflows/04-measure-and-learn.md` |

### Regras de Fluxo
- **Rework:** Se quality gate reprovar → revisar metodologia, corrigir viés identificado e reexecutar análise
- **Escalation:** Se bloqueio ou decisão fora de escopo → escalar para Movement Chief
- **Handoff:** Output vai para → tasks de Review (impact-review) e próximo ciclo de Strategy
