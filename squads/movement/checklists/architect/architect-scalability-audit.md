---
id: architect-scalability-audit
name: "Auditoria de Escalabilidade"
squad: movement
type: checklist
category: architect
agent: architect-of-movement
version: "1.0"
tags: [escala, crescimento, gargalos, automação, sustentabilidade]
---

# Auditoria de Escalabilidade

## Objetivo

Avaliar se o sistema do movimento consegue crescer 10x sem quebrar: processos,
ferramentas, equipe e cultura. Movimento que cresce mais rápido que sua infraestrutura
colapsa sob o próprio peso.

## Checklist

### Escalabilidade de Processos

- [ ] Processos-chave estão documentados em SOPs replicáveis (não dependem de conhecimento tácito)
- [ ] Tempo de produção de conteúdo não aumenta proporcionalmente com volume
- [ ] Processo de aprovação funciona com 5x o volume atual sem gargalo
- [ ] Onboarding de novo membro da equipe leva < 1 semana até produtividade mínima
- [ ] Existe automação para tarefas repetitivas (agendamento, reports, respostas padrão)

### Escalabilidade de Ferramentas

- [ ] Ferramentas atuais suportam 10x usuários/dados sem upgrade de plano
- [ ] APIs e integrações entre ferramentas estão funcionando sem intervenção manual
- [ ] Dados não estão fragmentados em planilhas pessoais (fonte única de verdade existe)
- [ ] Backup de dados críticos é automático e testado
- [ ] Existe plano B para cada ferramenta crítica (se cair, o que usar?)

### Escalabilidade de Equipe

- [ ] Modelo de equipe para 2x e 5x crescimento está desenhado (quais roles)
- [ ] Existe programa de formação de líderes dentro da comunidade (escala sem contratar)
- [ ] Conhecimento crítico está documentado (nenhuma pessoa é single point of failure)
- [ ] Modelo de governança funciona com equipe distribuída (não depende de presença física)
- [ ] Carga de trabalho atual permite absorver 30% mais demanda sem burnout

### Escalabilidade Cultural

- [ ] A identidade do movimento se mantém forte mesmo com 10x mais membros
- [ ] Existem mecanismos de preservação cultural (rituais, histórias fundadoras, valores explícitos)
- [ ] Novos membros são socializados nos valores antes de ganhar voz ativa
- [ ] Sub-comunidades regionais/temáticas mantêm coerência com o todo
- [ ] Existe protocolo para lidar com "efeito Eternal September" (diluição por crescimento rápido)

## Critérios de Aprovação

- Pelo menos 4 de 5 itens em cada seção devem estar completos
- Nenhuma seção pode ter menos de 3 itens completos
- Itens marcados como incompletos devem ter plano de ação com prazo
- Auditoria deve ser refeita a cada 90 dias ou após crescimento > 50%

## Ação se Falhar

1. Identificar os 3 maiores gargalos de escalabilidade com a equipe
2. Priorizar automação das tarefas mais repetitivas (quick wins primeiro)
3. Documentar os 5 processos mais críticos que só existem na cabeça de alguém
4. Testar ferramentas sob carga simulada antes de precisar na prática
5. Criar roadmap de escalabilidade com marcos trimestrais e owners definidos
