---
id: plan-movement-scaling
name: "Planejar Escala do Movimento"
squad: movement
type: task
category: strategy
agents: [movement-chief, movement-architect]
frameworks: [movement-lifecycle-framework, scaling-layer]
checklists: [movement-scaling-quality, architect/architect-scalability-audit]
templates: [plans/movement-scaling-plan]
registry: [data/registries/decision-log]
version: "1.0"
tags: [strategy, escala, crescimento, expansao, rede]
---

# Planejar Escala do Movimento

## Objetivo

Projetar o plano de escalabilidade do movimento — como crescer de nicho para mainstream sem perder autenticidade, definindo fases de expansão, gatilhos de escala, riscos de diluição e mecanismos para preservar a essência.

## Contexto

O maior assassino de movimentos culturais é o sucesso mal gerenciado. Crescer rápido demais dilui a comunidade. Crescer devagar demais perde momentum. O plano de scaling define o equilíbrio: como expandir o alcance preservando a profundidade que torna o movimento especial.

## Inputs Necessários

- Win Conditions 30/60/90 com métricas de comunidade
- Community Structure definida
- Identity System com governança
- Dados de performance das primeiras fases
- Benchmarks de movimentos que escalaram (e os que falharam ao escalar)

## Processo

1. **Diagnosticar estágio atual** — Posicionar o movimento no modelo de estágio: Semente (0-500), Tribo (500-5K), Comunidade (5K-50K), Movimento (50K-500K), Cultura (500K+). Cada estágio tem regras diferentes.

2. **Mapear efeitos de rede** — Identificar quais dinâmicas de rede o movimento pode ativar: conteúdo gerado por membros, referral loops, rituais compartilháveis, identidade visível, status social de pertencimento.

3. **Definir fases de expansão** — Estabelecer: (a) Aprofundar antes de expandir (fortalecer core), (b) Expandir por adjacência (públicos similares), (c) Expandir por geografia (novas regiões), (d) Expandir por vertical (novos segmentos).

4. **Estabelecer gatilhos de escala** — Definir métricas que autorizam a expansão para a próxima fase. Ex: "Só expandir para novo segmento quando NPS da comunidade atual > 70 e taxa de contribuição espontânea > 15%".

5. **Identificar riscos de diluição** — Listar: (a) Entrada de membros sem fit cultural, (b) Perda de intimidade na comunidade, (c) Cooptação por mainstream, (d) Mensagem simplificada demais, (e) Burnout de champions originais.

6. **Projetar mecanismos de preservação** — Para cada risco, definir contramedida: (a) Onboarding rigoroso, (b) Sub-comunidades por interesse/região, (c) Rituais que escalam, (d) Governança descentralizada, (e) Programa de reconhecimento de OGs.

7. **Planejar infraestrutura de escala** — Definir: ferramentas que suportam crescimento, processos que automatizam sem desumanizar, equipe necessária por estágio, budget projetado.

8. **Criar playbook de expansão regional** — Se aplicável, definir como adaptar o movimento para novas regiões/culturas: o que é universal, o que é adaptável, o que nunca muda, quem lidera localmente.

9. **Definir métricas de saúde por estágio** — Para cada estágio, especificar: métricas que indicam que o movimento está saudável e pronto para próxima fase vs. métricas que indicam crescimento insustentável.

10. **Documentar e alinhar** — Compilar o Scaling Plan e alinhar com stakeholders sobre expectativas de timeline e investimento por fase.

## Outputs Esperados

- **Scaling Plan Document** com fases e gatilhos
- **Mapa de efeitos de rede** ativáveis
- **Riscos de diluição** e contramedidas
- **Playbook de expansão regional** (se aplicável)
- **Métricas de saúde por estágio**
- **Projeção de infraestrutura e budget**

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Fases definidas | >= 3 fases com gatilhos claros |
| Riscos identificados | >= 5 riscos com contramedidas |
| Efeitos de rede | >= 3 mecanismos projetados |
| Métricas por estágio | 100% dos estágios cobertos |
| Stakeholders alinhados | Aprovação formal |

## Decision Points

- **Comunidade core forte + demanda externa** → Iniciar primeira expansão controlada
- **Crescimento acima do planejado** → Avaliar se qualidade acompanha e ajustar velocidade
- **Sinais de diluição** → Pausar expansão e fortalecer core antes de continuar
- **Efeitos de rede não ativando** → Revisar mecanismos e testar novas abordagens

## Integração

| Tipo | Referência |
|------|-----------|
| **Frameworks** | `frameworks/movement-lifecycle-framework.md`, `frameworks/scaling-layer.md` |
| **Checklists** | `checklists/movement-scaling-quality.md`, `checklists/architect/architect-scalability-audit.md` |
| **Templates** | `templates/plans/movement-scaling-plan.md` |
| **Registries** | `data/registries/decision-log.yaml` |
| **Workflows** | `workflows/01-thesis-forge.md` |

### Regras de Fluxo
- **Rework:** Se quality gate reprovar → retornar ao passo que falhou, incorporar feedback e resubmeter para aprovação do Movement Chief
- **Escalation:** Se bloqueio ou decisão fora de escopo → escalar para Movement Architect
- **Handoff:** Output vai para → tasks de Creation (write-manifesto, create-memetic-assets)
