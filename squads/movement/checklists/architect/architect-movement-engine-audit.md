---
id: architect-movement-engine-audit
name: "Auditoria do Motor do Movimento"
squad: movement
type: checklist
category: architect
agent: architect-of-movement
version: "1.0"
tags: [sistema, loops, motor, auditoria, engrenagens]
---

# Auditoria do Motor do Movimento

## Objetivo

Auditar os loops sistêmicos que mantêm o movimento funcionando: loops de aquisição,
engajamento, retenção e amplificação. O motor do movimento precisa ser auto-reforçante
— se parar de pedalar, não pode parar de andar.

## Checklist

### Loop de Aquisição

- [ ] Canal primário de descoberta está identificado e mensurado (como pessoas encontram o movimento)
- [ ] Taxa de conversão de visitante→membro está acima de 5%
- [ ] Existe pelo menos 1 mecanismo de viralidade ativo (referral, share, UGC)
- [ ] O custo de aquisição por membro está calculado e dentro do aceitável
- [ ] Existe diversificação de canais (não depender de 1 único canal > 70%)

### Loop de Engajamento

- [ ] Primeira ação significativa do novo membro acontece em menos de 48 horas
- [ ] Existe sequência de onboarding com pelo menos 3 touchpoints
- [ ] Métricas de engajamento diário/semanal estão definidas e trackadas
- [ ] Existem pelo menos 3 tipos de interação disponíveis (consumir, reagir, criar)
- [ ] Feedback loop entre ação do membro e resposta do sistema é < 24h

### Loop de Retenção

- [ ] Cohort de retenção D7, D30, D90 está sendo medida
- [ ] Existem pelo menos 2 mecanismos de hábito (ritual, notificação, conteúdo recorrente)
- [ ] Membros inativos > 14 dias recebem reativação personalizada
- [ ] Motivos de churn dos últimos 30 dias estão documentados
- [ ] Existe escada de comprometimento (membro→colaborador→líder→embaixador)

### Loop de Amplificação

- [ ] Membros ativos têm ferramenta fácil para compartilhar o movimento
- [ ] Conteúdo gerado pelo membro (UGC) tem fluxo de curadoria e redistribuição
- [ ] Existe incentivo (não necessariamente financeiro) para indicar novos membros
- [ ] Histórias de transformação são coletadas e amplificadas sistematicamente
- [ ] O movimento aparece em buscas orgânicas (SEO do ecossistema de conteúdo)

## Critérios de Aprovação

- Pelo menos 4 de 5 itens em cada loop devem estar funcionando
- Nenhum loop pode ter menos de 3 itens completos (falha estrutural)
- Dados de cada loop devem ter menos de 7 dias de defasagem
- Pelo menos 1 loop deve mostrar crescimento positivo mês-sobre-mês

## Ação se Falhar

1. Identificar o loop com maior gap e priorizar correção em sprint de 2 semanas
2. Mapear visualmente o sistema completo em diagrama de loops causais
3. Testar cada loop isoladamente para identificar ponto de quebra
4. Implementar instrumentação de dados nos loops sem medição
5. Revisitar auditoria em 30 dias com dados atualizados
