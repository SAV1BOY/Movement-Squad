---
id: impact-dashboard-quality
name: "Qualidade do Dashboard de Impacto"
squad: movement
type: checklist
category: quality-gate
version: "1.0"
tags: [dashboard, métricas, dados, impacto, monitoramento, tendências]
---

# Qualidade do Dashboard de Impacto

## Objetivo

Garantir que o dashboard de impacto do movimento exibe as métricas certas, com definições
claras, fontes confiáveis, visualizações acionáveis e tendências temporais que permitem
decisões rápidas. Um dashboard que mostra vaidade (impressões sem contexto) ou que ninguém
consulta é pior que não ter dashboard — cria falsa sensação de controle.

## Quando Usar

- Na configuração inicial do dashboard antes do lançamento do movimento
- Quando novas métricas forem adicionadas ou métricas existentes removidas
- Quando stakeholders reportarem que o dashboard não responde suas perguntas
- Em revisões mensais da qualidade dos dados e da utilidade do dashboard
- Quando a fonte de dados mudar (nova ferramenta, nova API)

## Agentes Responsáveis

- **Data & Analytics Agent** — Construtor e mantenedor do dashboard
- **Movement Strategist Agent** — Define quais perguntas o dashboard deve responder
- **Growth & Conversion Agent** — Fornece métricas de conversão e crescimento
- **Review & QA Agent** — Executa este checklist como quality gate

## Checklist

### 1. Métricas Corretas

- [ ] 1.1 O dashboard responde às 3-5 perguntas estratégicas mais importantes do movimento
- [ ] 1.2 As métricas incluem pelo menos 1 de cada tipo: awareness, engajamento, conversão, retenção
- [ ] 1.3 Métricas de vaidade (impressões brutas, seguidores totais) estão ausentes ou contextualizadas
- [ ] 1.4 Existe pelo menos 1 métrica de saúde da comunidade (NPS, sentimento, retenção 30d)
- [ ] 1.5 As métricas de negócio (receita, CAC, LTV) estão conectadas às métricas de movimento

### 2. Definições Claras

- [ ] 2.1 Cada métrica tem definição escrita acessível no dashboard (tooltip ou glossário)
- [ ] 2.2 O método de cálculo de cada métrica está documentado e reproduzível
- [ ] 2.3 Diferenças entre métricas similares estão explicadas (ex.: MAU vs. membros ativos)
- [ ] 2.4 Os benchmarks ou metas para cada métrica estão visíveis no dashboard
- [ ] 2.5 A periodicidade de atualização de cada métrica está indicada (real-time, diário, semanal)

### 3. Fontes de Dados

- [ ] 3.1 A fonte de dados de cada métrica está documentada (ferramenta, tabela, API)
- [ ] 3.2 As integrações de dados estão funcionando e foram testadas nas últimas 48h
- [ ] 3.3 Existe alerta automático para falha de ingestão de dados
- [ ] 3.4 Os dados não têm duplicação, gaps ou atrasos superiores a 24h
- [ ] 3.5 Existe processo de reconciliação de dados entre fontes diferentes

### 4. Visualização e Acionabilidade

- [ ] 4.1 Cada gráfico ou número tem título autoexplicativo (entende-se sem legenda)
- [ ] 4.2 Tendências temporais mostram pelo menos 4 semanas de histórico
- [ ] 4.3 Alertas visuais (cores, ícones) destacam métricas acima ou abaixo da meta
- [ ] 4.4 O dashboard carrega em menos de 5 segundos
- [ ] 4.5 Existe visão executiva resumida (1 tela) e visão detalhada por área

### 5. Uso e Governança

- [ ] 5.1 O dashboard é revisado em reunião recorrente (semanal ou quinzenal)
- [ ] 5.2 Pelo menos 3 decisões nos últimos 30 dias foram tomadas com base no dashboard
- [ ] 5.3 Existe responsável nomeado pela manutenção e qualidade dos dados
- [ ] 5.4 Feedback de usuários do dashboard é coletado e incorporado trimestralmente

## Critérios de Aprovação

- **Aprovado:** Todos os 24 itens completos com dashboard funcional e populado
- **Aprovado com ressalvas:** Até 3 itens pendentes, nenhum do grupo "Fontes de Dados"
- **Reprovado:** 4+ itens pendentes, ou fontes de dados não confiáveis ou desatualizadas

## Ação se Falhar

1. Priorizar correção de fontes de dados sobre adição de novas métricas
2. Se métricas estiverem erradas, suspender uso do dashboard até correção
3. Se ninguém usa o dashboard, realizar entrevistas para entender o que falta
4. Se visualização for confusa, simplificar para máximo 8 métricas na visão executiva
5. Documentar gaps e criar sprint dedicado para correção em até 2 semanas

## Cross-references

- `movement-brief-quality.md` — KPIs do brief devem estar no dashboard
- `experimentation-quality.md` — Resultados de experimentos alimentam o dashboard
- `movement-to-product-fit-quality.md` — Métricas de fit devem estar visíveis
- `distribution-plan-quality.md` — Métricas de distribuição por canal
- `movement-scaling-quality.md` — Métricas de escala e diluição devem ser monitoradas
- Framework: Impact Measurement Framework v1
- Template: Configuração de Dashboard (template-impact-dashboard.md)
