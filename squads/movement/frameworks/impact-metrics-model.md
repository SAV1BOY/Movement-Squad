---
id: impact-metrics-model
name: "Metrics Model"
squad: movement
type: framework
category: agent-specific
agent: impact
version: "1.0"
tags: [métricas, modelo, north-star, guardrails, impact]
---

# Metrics Model

## Overview

Sem métricas, movimentos viram atos de fé. Com métricas demais, viram planilhas sem alma. Este framework define o modelo de métricas ideal para um movimento: uma North Star Metric que resume a saúde geral, 3-5 métricas de input que a alimentam, e 2-3 guardrails que não podem ser violados. O agente de Impact usa este modelo para dar visibilidade sem criar paralisia por análise.

## Princípios

1. **Uma North Star, não dez** — Se tudo é prioridade, nada é prioridade. O movimento inteiro se orienta por uma métrica. Uma.

2. **Inputs são alavancas** — As métricas de input são o que a squad pode influenciar diretamente. A North Star é consequência.

3. **Guardrails protegem** — Métricas que não podem cair abaixo de um piso. Se um guardrail é violado, tudo para até resolver.

4. **Cadência de leitura definida** — Cada métrica tem um ritmo de leitura: diária, semanal, mensal. Ler na cadência errada gera ansiedade ou cegueira.

5. **Dados imperfeitos são melhores que nenhum dado** — Não espere o tracking perfeito para começar a medir. Métricas proxy funcionam no início.

6. **Métricas mudam conforme a fase** — A North Star de um movimento de 30 dias é diferente da de um movimento de 6 meses. Revise trimestralmente.

## Protocolo

### Passo 1: Definir a North Star Metric

1. A North Star Metric deve:
   - Resumir a saúde do movimento em um único número.
   - Ser influenciável pela squad (não puramente externa).
   - Ser compreensível por qualquer pessoa em 5 segundos.
   - Ser mensurável com as ferramentas disponíveis.

2. Exemplos por fase do movimento:

| Fase | North Star | Razão |
|------|-----------|-------|
| 0-30 dias | Engajamento qualificado por artefato | Ressonância da tese |
| 30-60 dias | UGC semanal | Engajamento orgânico |
| 60-90 dias | Champions ativos | Sustentabilidade do movimento |
| 90+ dias | Conversão atribuída ao movimento | Conexão com negócio |

3. Validar com o Chief: "Se pudéssemos olhar apenas um número para saber se o movimento está saudável, qual seria?"

### Passo 2: Definir Métricas de Input

4. Inputs são as alavancas que a squad move diretamente para influenciar a North Star.
5. Selecionar 3-5 inputs. Cada input deve ter relação causal clara com a North Star.

**Modelo exemplo (North Star: UGC semanal):**
- Input 1: Artefatos publicados por semana (mais artefatos → mais inspiração → mais UGC).
- Input 2: Champions ativos (mais champions → mais UGC direto + indireto).
- Input 3: Alcance orgânico semanal (mais alcance → mais pessoas expostas → mais UGC).
- Input 4: Taxa de participação em rituais (mais participação → mais conteúdo gerado).

6. Para cada input, definir:
   - Como medir (fonte de dados, ferramenta).
   - Meta (número alvo por período).
   - Cadência de leitura (diária, semanal).
   - Responsável por monitorar.

### Passo 3: Definir Guardrails

7. Guardrails são métricas que não podem cair abaixo de um piso. São proteções contra efeitos colaterais.

**Guardrails comuns:**
- **Sentiment score**: proporção positivo/negativo nos comentários. Piso: 70% positivo.
- **Churn de champions**: % de champions que ficam inativos por 30+ dias. Teto: 20%.
- **Brand safety score**: incidentes de marca relacionados ao movimento. Teto: 0 por mês.
- **Diversidade de fontes**: % do engajamento que vem de um único canal. Teto: 70%.

8. Se um guardrail é violado:
   - Alerta imediato ao Chief.
   - Investigação de causa raiz.
   - Ação corretiva antes de retomar produção.
   - Documentar incidente e aprendizado.

### Passo 4: Construir o Dashboard

9. Dashboard deve caber em uma tela, com:
   - North Star em destaque (número atual + tendência de 4 semanas).
   - Inputs abaixo com barras de progresso vs. meta.
   - Guardrails com indicador verde/amarelo/vermelho.

10. Ferramentas possíveis: Google Sheets, Notion, Looker, qualquer ferramenta simples que a squad use.

11. Atualização: inputs atualizados semanalmente. North Star e guardrails atualizados conforme cadência definida.

### Passo 5: Ritual de Leitura

12. Definir rituais de leitura:
    - **Diária (5 min)**: olhar rápido nos inputs do dia anterior. Sem reunião.
    - **Semanal (30 min)**: reunião com squad. North Star + inputs + guardrails. Decisões de ajuste.
    - **Mensal (60 min)**: análise profunda. Tendências, correlações, anomalias. Revisão de metas.
    - **Trimestral (120 min)**: revisão do modelo. A North Star ainda é a certa? Inputs mudaram?

### Passo 6: Evoluir o Modelo

13. O modelo de métricas não é estático. Revisar trimestralmente:
    - A North Star reflete o que importa na fase atual?
    - Os inputs ainda têm relação causal com a North Star?
    - Os guardrails são os corretos para os riscos atuais?
    - As metas são desafiadoras mas realistas?

14. Documentar mudanças no modelo com data e racional.

## Quando Usar

- No início de um movimento para definir como medir sucesso.
- Quando há dados mas falta foco ("medimos tudo mas não sabemos nada").
- Em reuniões semanais e mensais como estrutura de análise.
- Para comunicar progresso a stakeholders.

## Quando Não Usar

- Para análise de experimentos — use o framework de Experiment Design.
- Para análise de cohorts — use o framework de Cohort Analysis.
- Se não há dados nenhum — primeiro implemente tracking mínimo.

## Integração

- **Chief** valida a North Star e usa o dashboard para decisões de portfólio.
- **Architect** conecta métricas aos componentes do sistema.
- **Manifestor** ajusta produção baseado em performance dos inputs.
- **Cycle** alinha cadência de leitura com o calendário.
- **Phenomenology** investiga causas qualitativas quando métricas mudam.
- **Identity** garante que métricas de sentiment refletem saúde da narrativa.

## Exemplo Aplicado

**Contexto:** Modelo de métricas para movimento #ExijaClareza, fase 60-90 dias.

**North Star:** Champions ativos por semana.
- Meta: 20 champions publicando pelo menos 1 vez por semana.
- Atual: 15. Tendência: crescente (+2/semana).

**Inputs:**

| Input | Meta | Atual | Cadência |
|-------|------|-------|----------|
| Artefatos publicados/semana | 8 | 10 | Semanal |
| Novos membros/semana | 50 | 62 | Semanal |
| Participação em rituais | 40 | 35 | Semanal |
| Alcance orgânico | 50.000 | 48.000 | Semanal |

**Guardrails:**

| Guardrail | Piso/Teto | Atual | Status |
|-----------|-----------|-------|--------|
| Sentiment | >70% positivo | 82% | Verde |
| Churn champions | <20%/mês | 12% | Verde |
| Concentração em 1 canal | <70% | 65% | Amarelo |

**Ação baseada na leitura:** Participação em rituais abaixo da meta (35 vs 40). Investigar: o ritual está ficando repetitivo? Concentração em 1 canal no amarelo — iniciar esforço para diversificar.
