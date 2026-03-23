---
id: architect-dependency-mapping
name: "Mapeamento de Dependências do Sistema"
squad: movement
type: checklist
category: architect
agent: architect-of-movement
version: "1.0"
tags: [dependências, mapeamento, riscos, componentes, sistema]
---

# Mapeamento de Dependências do Sistema

## Objetivo

Mapear todas as dependências entre componentes do sistema do movimento para
identificar fragilidades, caminhos críticos e pontos de falha em cascata.
Dependência não mapeada é bomba-relógio esperando o pior momento para explodir.

## Checklist

### Dependências Internas

- [ ] Diagrama de dependências entre agentes do squad está atualizado
- [ ] Cada dependência tem classificação: hard (bloqueia) ou soft (degrada)
- [ ] Caminho crítico do fluxo principal está identificado (da captura à distribuição)
- [ ] Dependências circulares estão identificadas e tratadas (A depende de B que depende de A)
- [ ] Cada componente tem SLA de entrega acordado com componentes dependentes

### Dependências Externas

- [ ] Plataformas de distribuição (Instagram, TikTok, YouTube) têm risk assessment
- [ ] Dependência de APIs externas está catalogada com plano de contingência
- [ ] Fornecedores críticos (design, vídeo, ferramentas) têm alternativas mapeadas
- [ ] Mudanças de algoritmo de plataformas são monitoradas semanalmente
- [ ] Contratos com fornecedores têm cláusula de continuidade ou transição

### Dependências de Pessoas

- [ ] Nenhum processo crítico depende de uma única pessoa sem backup documentado
- [ ] Conhecimento tácito dos top 5 contribuidores está sendo documentado
- [ ] Férias e ausências planejadas têm cobertura definida com antecedência
- [ ] Skills únicos na equipe estão identificados com plano de redundância
- [ ] Freelancers e temporários têm handoff documentado ao final do contrato

### Monitoramento de Dependências

- [ ] Existe alerting automático quando dependência crítica falha
- [ ] Review trimestral de dependências está agendado
- [ ] Novas dependências adicionadas passam por avaliação de risco
- [ ] Histórico de falhas de dependência está documentado com root cause
- [ ] Plano de disaster recovery cobre as 3 dependências mais críticas

## Critérios de Aprovação

- Todos os itens de "Dependências Internas" devem estar completos
- Pelo menos 4 de 5 itens de "Dependências Externas" devem estar completos
- Todos os itens de "Dependências de Pessoas" devem estar completos
- Pelo menos 3 de 4 itens de "Monitoramento" devem estar completos

## Ação se Falhar

1. Realizar sessão de mapeamento de dependências com toda a equipe (2 horas)
2. Criar diagrama visual de dependências usando ferramenta compartilhada
3. Classificar cada dependência por probabilidade de falha x impacto
4. Implementar plano de mitigação para as 5 dependências de maior risco
5. Agendar review mensal de dependências até estabilização do sistema
