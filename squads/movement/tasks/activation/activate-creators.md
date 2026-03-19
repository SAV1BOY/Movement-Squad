---
id: activate-creators
name: "Ativar Creators e Influenciadores"
squad: movement
type: task
category: activation
agents: [ativador-chefe, estrategista-movimento]
frameworks: [creator-activation-framework, influence-amplification-model]
checklists: [creator-activation-checklist, content-approval-checklist]
templates: [creator-outreach-template, creator-tracking-template]
version: "1.0"
tags: [activation, creators, influenciadores, parcerias, amplificacao]
---

# Ativar Creators e Influenciadores

## Objetivo

Executar a ativação de creators e influenciadores — desde o primeiro contato até a publicação e medição de resultados — garantindo que cada parceria amplifique autenticamente a mensagem do movimento e gere impacto mensurável.

## Contexto

Creators não são canais de distribuição — são co-contadores da história. A ativação ideal faz o creator sentir que o movimento é dele também, não apenas um job. Quando o creator publica sobre o movimento com a mesma paixão com que fala sobre seus temas favoritos, a audiência sente a diferença.

## Inputs Necessários

- Creator Briefs aprovados
- Creator Kit com assets
- Lista de creators selecionados com perfis analisados
- Budget aprovado por creator/tier
- Calendar de ativação com datas
- Métricas de sucesso definidas por parceria

## Processo

1. **Fazer outreach personalizado** — Contatar cada creator com mensagem individual: mencionar algo específico do trabalho dele que conecta com o movimento, explicar por que ele especificamente foi escolhido, convidar para conversa (não pitch).

2. **Conduzir conversa de alinhamento** — Call ou reunião com cada creator: apresentar o movimento (não o produto), ouvir a visão dele, discutir como poderia participar autenticamente, identificar interseções genuínas.

3. **Enviar brief e kit** — Após alinhamento, enviar: brief customizado, Creator Kit, timeline, detalhes comerciais. Dar prazo para dúvidas antes de começar a produzir.

4. **Acompanhar produção** — Estar disponível para dúvidas sem microgerenciar. Se o creator pedir liberdade criativa além do brief, considerar seriamente — ele conhece a audiência melhor.

5. **Revisar conteúdo** — Quando o creator enviar preview: verificar alinhamento com valores (não com estética pessoal), checar accuracy de informações, confirmar compliance legal. Máximo 1 rodada de ajustes.

6. **Coordenar publicação** — Alinhar data e horário com o calendar de ativação. Se múltiplos creators, orquestrar para que publicações se complementem sem parecer campanha coordenada.

7. **Amplificar publicação** — Quando o conteúdo for ao ar: repostar nos canais do movimento, compartilhar na comunidade, ativar paid amplification se planejado, engajar nos comentários do post do creator.

8. **Monitorar resultados** — Rastrear em tempo real: views, engajamento, sentimento dos comentários, cliques, entradas na comunidade, menções derivadas.

9. **Dar feedback ao creator** — Compartilhar resultados, agradecer publicamente, enviar dados de impacto, discutir o que funcionou, abrir porta para próxima colaboração.

10. **Compilar creator report** — Para cada creator: métricas de resultado, custo por resultado, qualidade do conteúdo, fit cultural, recomendação de continuidade (sim/não/modificar).

## Outputs Esperados

- **Creators ativados** com conteúdo publicado
- **Outreach logs** de todas as conversas
- **Conteúdo aprovado** e publicado no timing
- **Métricas por creator** compiladas
- **Creator Report** por parceria
- **Recomendações de continuidade**

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Taxa de aceite | >= 50% dos creators contatados |
| Conteúdo publicado | 100% dos creators ativados |
| Alinhamento com valores | 100% aprovado no review |
| Rodadas de revisão | <= 1 por creator |
| Engajamento rate | >= média do creator em conteúdo orgânico |
| Report completo | Para cada creator ativado |

## Decision Points

- **Creator produz conteúdo excepcional** → Propor parceria de longo prazo / embaixador
- **Conteúdo desalinhado no review** → Conversa aberta; se não resolver, cancelar com respeito
- **Audiência do creator rejeita** → Analisar se é problema de fit ou de execução
- **Creator quer se engajar mais profundamente** → Considerar para papel de champion ou co-creator

## Integração

| Tipo | Referência |
|------|-----------|
| **Frameworks** | `frameworks/creator-movement-framework.md`, `frameworks/cycle-momentum-mapping.md` |
| **Checklists** | `checklists/creator-influencer-brief-quality.md`, `checklists/distribuicao/paid-amplification-guardrails.md` |
| **Templates** | `templates/outputs/creator-brief-package.md` |
| **Registries** | `data/registries/creator-partners.yaml` |
| **Workflows** | `workflows/03-activation-sprint.md` |

### Regras de Fluxo
- **Rework:** Se quality gate reprovar → pausar canal/fase afetada, diagnosticar causa raiz e reexecutar com ajustes
- **Escalation:** Se bloqueio ou decisão fora de escopo → escalar para Movement Chief
- **Handoff:** Output vai para → tasks de Measurement (measure-movement-health, run-experiments)
