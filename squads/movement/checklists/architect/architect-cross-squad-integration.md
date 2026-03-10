---
id: architect-cross-squad-integration
name: "Integração Cross-Squad"
squad: movement
type: checklist
category: architect
agent: architect-of-movement
version: "1.0"
tags: [integração, squads, colaboração, dependências, sincronia]
---

# Integração Cross-Squad

## Objetivo

Verificar que o squad de movimento está integrado com outros squads da organização,
compartilhando dados, alinhando mensagens e evitando trabalho duplicado. Movimento
isolado é movimento que eventualmente conflita com o resto da empresa.

## Checklist

### Mapeamento de Dependências

- [ ] Lista de squads com interface direta com o movimento está documentada
- [ ] Cada dependência tem tipo definido (dados, conteúdo, aprovação, recurso compartilhado)
- [ ] SLAs de resposta entre squads estão acordados por escrito
- [ ] Ponto de contato em cada squad parceiro está nomeado e acessível
- [ ] Riscos de dependência crítica estão identificados (o que trava se squad X não entregar)

### Fluxo de Informação

- [ ] Dashboard de métricas do movimento é acessível a squads parceiros
- [ ] Insights de fenomenologia são compartilhados com squad de produto mensalmente
- [ ] Calendário do movimento é visível para squads de marketing e vendas
- [ ] Feedback de comunidade relevante para produto é repassado em até 48h
- [ ] Aprendizados de experimentos são publicados em canal acessível a todos

### Alinhamento de Mensagem

- [ ] Tom de voz do movimento não contradiz comunicação de outros squads
- [ ] Lançamentos de produto e ações de movimento são coordenados no calendário
- [ ] Não existe promessa do movimento que o produto não pode cumprir
- [ ] Brand guidelines são respeitados mesmo quando o movimento "puxa" limites
- [ ] Existe aprovação cruzada para ações que mencionam diretamente o produto

### Rituais de Integração

- [ ] Existe sync quinzenal entre movimento e pelo menos 2 squads-chave
- [ ] Retrospectiva trimestral inclui representante de squad parceiro
- [ ] Existe canal compartilhado (Slack/Teams) para comunicação rápida entre squads
- [ ] Conflitos entre squads têm processo de escalação definido
- [ ] Vitórias compartilhadas são celebradas conjuntamente (crédito distribuído)

## Critérios de Aprovação

- Todos os itens de "Mapeamento de Dependências" devem estar completos
- Pelo menos 4 de 5 itens de "Fluxo de Informação" devem estar completos
- Todos os itens de "Alinhamento de Mensagem" devem estar completos
- Pelo menos 4 de 5 itens de "Rituais de Integração" devem estar completos

## Ação se Falhar

1. Agendar "integration kickoff" com squads parceiros em até 1 semana
2. Criar documento compartilhado de interfaces com responsáveis e SLAs
3. Implementar canal de comunicação cross-squad se não existir
4. Resolver conflitos de mensagem pendentes antes de próxima ação pública
5. Propor modelo de governança cross-squad ao chief para formalização
