---
id: design-channel-architecture
name: "Projetar Arquitetura de Canais"
squad: movement
type: task
category: strategy
agents: [movement-architect, estrategista-de-ciclo]
frameworks: [architect-channel-architecture, distribution-trident]
checklists: [architect/architect-channel-role-clarity, distribuicao/channel-mix-quality]
templates: [outputs/distribution-plan]
registry: [data/registries/distribution-plans]
version: "1.0"
tags: [strategy, canais, distribuicao, arquitetura, plataformas]
---

# Projetar Arquitetura de Canais

## Objetivo

Definir a arquitetura completa de canais do movimento — quais plataformas e espaços usar, com qual função cada um, como se conectam entre si e qual fluxo o membro percorre desde o primeiro contato até se tornar champion.

## Contexto

Canal não é só "onde postar". A arquitetura de canais define a jornada do membro através de espaços com funções distintas: descoberta, engajamento, pertencimento, ação. Sem arquitetura clara, o movimento publica conteúdo em todo lugar sem estratégia, diluindo impacto e confundindo quem tenta participar.

## Inputs Necessários

- Platform Briefs de pesquisa de dinâmicas
- Personas e segmentos do público-alvo
- Identity System do movimento
- Win Conditions 30/60/90
- Budget de mídia e ferramentas disponíveis
- Presença digital atual da marca

## Processo

1. **Definir funções de canal** — Categorizar cada canal potencial por função: (a) Descoberta (atrair novos), (b) Engajamento (aprofundar), (c) Comunidade (pertencer), (d) Ação (mobilizar), (e) Conversão (conectar ao produto).

2. **Mapear jornada do membro** — Desenhar o fluxo ideal: como alguém descobre o movimento → onde tem o primeiro engajamento → para onde migra para aprofundar → onde se sente parte → como é ativado para ação.

3. **Selecionar canais por função** — Para cada função, escolher 1-2 canais primários e 1 secundário. Princípio: é melhor dominar poucos canais do que estar mediocremente em muitos.

4. **Definir papel de cada canal** — Para cada canal selecionado, especificar: tipo de conteúdo, tom de voz adaptado, frequência de publicação, KPIs específicos, responsável, formato principal.

5. **Projetar conexões entre canais** — Definir como os canais se alimentam: CTAs de canal para canal, sequência de nurturing, pontos de transição, deep links, cross-posting strategy.

6. **Definir owned vs. rented** — Distinguir: canais owned (site, newsletter, comunidade própria) vs. rented (redes sociais). Garantir que o core do movimento vive em espaço owned para não depender de algoritmos.

7. **Criar Channel Map visual** — Montar mapa visual mostrando: todos os canais, suas funções, conexões entre eles, fluxo do membro, pontos de conversão.

8. **Definir cadência por canal** — Estabelecer calendário de publicação por canal com: frequência mínima, momentos de pico, temas recorrentes, espaço para conteúdo reativo.

9. **Preparar infraestrutura** — Garantir que cada canal tem: conta configurada, branding aplicado, bios otimizadas, links funcionando, tracking implementado, equipe treinada.

10. **Criar Channel Briefs** — Para cada canal ativo, produzir brief com: função, público, tom, formatos, cadência, KPIs, do's e don'ts, exemplos de referência.

## Outputs Esperados

- **Channel Architecture Document** com mapa completo
- **Channel Map** visual
- **Channel Briefs** por canal (1 cada)
- **Jornada do membro** mapeada
- **Calendário de cadência** por canal
- **Infraestrutura configurada** e validada

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Funções cobertas | Todas as 5 funções com canal designado |
| Jornada do membro | Completa do descobrimento ao champion |
| Canal owned | >= 1 canal owned como core |
| Channel briefs | 100% dos canais ativos |
| Conexões definidas | Todos os canais conectados no fluxo |
| Infraestrutura | 100% configurada antes do lançamento |

## Decision Points

- **Canal sem tração após 30 dias** → Avaliar se é problema de conteúdo ou de fit, ajustar ou descontinuar
- **Canal owned com baixa adoção** → Intensificar CTA de redes sociais para owned
- **Novo canal emergente relevante** → Testar por 30 dias antes de incorporar na arquitetura
- **Sobrecarga de canais** → Priorizar e consolidar antes de adicionar novos

## Integração

| Tipo | Referência |
|------|-----------|
| **Frameworks** | `frameworks/architect-channel-architecture.md`, `frameworks/distribution-trident.md` |
| **Checklists** | `checklists/architect/architect-channel-role-clarity.md`, `checklists/distribuicao/channel-mix-quality.md` |
| **Templates** | `templates/outputs/distribution-plan.md` |
| **Registries** | `data/registries/distribution-plans/` |
| **Workflows** | `workflows/01-thesis-forge.md` |

### Regras de Fluxo
- **Rework:** Se quality gate reprovar → retornar ao passo que falhou, incorporar feedback e resubmeter para aprovação do Movement Chief
- **Escalation:** Se bloqueio ou decisão fora de escopo → escalar para Movement Chief
- **Handoff:** Output vai para → tasks de Creation (write-manifesto, create-memetic-assets)
