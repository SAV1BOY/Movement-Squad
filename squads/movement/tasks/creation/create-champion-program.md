---
id: create-champion-program
name: "Criar Programa de Champions"
squad: movement
type: task
category: creation
agents: [community-builder, arquiteto-movimento, estrategista-movimento]
frameworks: [champion-program-framework, ambassador-model]
checklists: [champion-program-checklist, champion-selection-checklist]
templates: [champion-program-template, champion-toolkit-template]
version: "1.0"
tags: [creation, champions, embaixadores, lideranca, comunidade]
---

# Criar Programa de Champions

## Objetivo

Projetar e implementar o programa de champions do movimento — um sistema estruturado para identificar, capacitar, empoderar e reconhecer os membros mais engajados e influentes, transformando-os em líderes comunitários que amplificam o movimento de dentro para fora.

## Contexto

Champions são o ativo mais valioso de um movimento. São membros que não foram contratados — escolheram defender a causa por convicção. Um programa de champions bem desenhado multiplica o impacto do squad por 10x sem multiplicar o custo. Mal desenhado, transforma verdadeiros crentes em "influenciadores pagos" e mata a autenticidade.

## Inputs Necessários

- Community Structure com camada de champions definida
- Identity System com códigos de reconhecimento
- Win Conditions relacionadas à comunidade
- Dados de engajamento dos membros atuais
- Benchmarks de programas de embaixadores referência
- Budget para benefícios e incentivos

## Processo

1. **Definir perfil do champion ideal** — Documentar: comportamentos que demonstram (cria conteúdo, responde outros, convida pessoas, defende o movimento), valores que encarna, nível de influência necessário, tempo de engajamento mínimo.

2. **Criar critérios de seleção** — Estabelecer critérios objetivos e subjetivos: (a) Métricas de engajamento (frequência, qualidade de contribuição), (b) Alinhamento com valores (avaliação qualitativa), (c) Influência no grupo (recomendações de pares), (d) Disponibilidade e vontade.

3. **Projetar jornada do champion** — Mapear: como é convidado, como é capacitado, como atua no dia a dia, como é reconhecido, como evolui (champion → senior champion → council), como pode sair com dignidade.

4. **Criar programa de capacitação** — Desenvolver: (a) Kit do champion (guidelines, assets exclusivos, acesso privilegiado), (b) Treinamento inicial (imersão de 1-2h no propósito, técnicas, ferramentas), (c) Treinamento contínuo (mensal, com novos skills e updates).

5. **Definir responsabilidades e autonomia** — Esclarecer: o que champions podem fazer por conta própria, o que precisam de aprovação, como reportam atividades, quanto tempo se espera que dediquem.

6. **Projetar sistema de reconhecimento** — Criar camadas de reconhecimento: (a) Público (destaque na comunidade, badge, menção), (b) Exclusivo (acesso a conteúdo/eventos VIP, early access a produto), (c) Material (merch exclusivo, compensação se aplicável).

7. **Criar ferramentas do champion** — Produzir: toolkit com templates, talking points, FAQs, conteúdo exclusivo para compartilhar, canal privado de comunicação com o squad, dashboard de impacto pessoal.

8. **Definir métricas de performance** — Estabelecer como medir impacto de cada champion: membros que trouxe, conteúdo que criou, interações facilitadas, satisfaction dos membros que acompanha.

9. **Planejar eventos exclusivos** — Criar momentos especiais para champions: meetups exclusivos, Q&A com liderança, co-criação de próximas fases do movimento, reconhecimento público em marcos.

10. **Projetar sustentabilidade** — Garantir que o programa não dependa de burnout: rotação de responsabilidades, pausas permitidas, sistema de backup entre champions, pesquisa de satisfação trimestral.

## Outputs Esperados

- **Champion Program Document** completo
- **Critérios de seleção** documentados
- **Programa de capacitação** com materiais
- **Champion Toolkit** pronto
- **Sistema de reconhecimento** definido
- **Métricas de performance** configuradas
- **Calendário de eventos exclusivos**

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Perfil de champion | Documentado com critérios claros |
| Programa de capacitação | >= 2h de conteúdo pronto |
| Toolkit produzido | Completo e distribuível |
| Reconhecimento | >= 3 camadas definidas |
| Métricas | Sistema de tracking configurado |
| Sustentabilidade | Mecanismos anti-burnout definidos |

## Decision Points

- **Champions desengajando** → Investigar causa (burnout, falta de reconhecimento, desalinhamento) antes de recrutar novos
- **Candidatos insuficientes** → A comunidade ainda não está madura — fortalecer base antes de criar programa
- **Champion virando "funcionário"** → Reequilibrar autonomia vs. direcionamento
- **Champion com comportamento misaligned** → Conversa privada, coaching, e se necessário, offboarding respeitoso

## Integração

| Tipo | Referência |
|------|-----------|
| **Frameworks** | `frameworks/identity-belonging-gradient.md`, `frameworks/community-flywheel.md` |
| **Checklists** | `checklists/comunidade/champion-program-quality.md`, `checklists/community-activation-quality.md` |
| **Templates** | `templates/outputs/champion-program-blueprint.md` |
| **Registries** | `data/registries/champion-registry.yaml` |
| **Workflows** | `workflows/02-artifact-foundry.md` |

### Regras de Fluxo
- **Rework:** Se quality gate reprovar → revisar com feedback específico do quality gate, iterar o artefato e resubmeter
- **Escalation:** Se bloqueio ou decisão fora de escopo → escalar para Movement Chief
- **Handoff:** Output vai para → tasks de Activation (launch-activation, activate-community)
