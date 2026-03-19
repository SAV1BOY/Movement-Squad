---
id: research-platform-dynamics
name: "Pesquisar Dinâmicas de Plataformas"
squad: movement
type: task
category: research
agents: [fenomenologo]
frameworks: [cycle-cultural-wave-surfing, distribution-trident]
checklists: [fenomenologia/signal-source-diversity]
templates: [outputs/cultural-insight-report]
registry: [data/research/platform-dynamics]
version: "1.0"
tags: [research, plataformas, algoritmo, distribuicao, formato]
---

# Pesquisar Dinâmicas de Plataformas

## Objetivo

Analisar as dinâmicas específicas de cada plataforma relevante para o movimento — algoritmos, formatos nativos, comportamentos de usuário, cultura local e oportunidades de distribuição — para garantir que o conteúdo e as ativações do movimento sejam otimizados por contexto.

## Contexto

Cada plataforma é uma cultura com regras próprias. O que viraliza no TikTok morre no LinkedIn. O que engaja no Discord não funciona no Instagram. Movimentos culturais eficazes são platform-native: respeitam a gramática de cada espaço sem perder a essência da mensagem. Ignorar dinâmicas de plataforma é o erro mais comum de movimentos que ficam só no planejamento.

## Inputs Necessários

- Lista de plataformas prioritárias do movimento
- Dados de presença atual em cada plataforma
- Análise de performance dos últimos 90 dias por plataforma
- Benchmarks de concorrentes e movimentos similares por plataforma
- Atualizações recentes de algoritmo e funcionalidades

## Processo

1. **Definir universo de plataformas** — Categorizar em: (a) Plataformas core (presença obrigatória), (b) Plataformas de oportunidade (alto potencial, baixa presença), (c) Plataformas de nicho (pequeno alcance, alta relevância), (d) Plataformas emergentes (monitorar).

2. **Auditar algoritmo atual** — Para cada plataforma core, documentar: fatores de ranqueamento conhecidos, formatos privilegiados pelo algoritmo, métricas que o algoritmo prioriza, mudanças recentes e tendências de evolução.

3. **Mapear formatos nativos** — Para cada plataforma, listar: formatos que performam melhor, durações ideais, estilos visuais dominantes, hooks que funcionam, CTAs que convertem, horários de pico.

4. **Analisar cultura da plataforma** — Descrever para cada uma: tom de voz dominante, tipo de humor que funciona, temas tabu, estética prevalente, tipo de autenticidade valorizado, o que é considerado "cringe".

5. **Estudar cases de movimento na plataforma** — Identificar 3-5 exemplos de movimentos (culturais, sociais, de marca) que se espalharam com sucesso em cada plataforma. Analisar: o que fizeram diferente, qual formato usaram, como o algoritmo os favoreceu.

6. **Mapear comunidades relevantes** — Identificar em cada plataforma: grupos, hashtags, subcomunidades e espaços onde o público-alvo do movimento já se reúne organicamente.

7. **Avaliar oportunidades de formato** — Cruzar a essência do movimento com os formatos que cada plataforma favorece. Identificar 3-5 formatos de conteúdo ideais por plataforma que preservem autenticidade e maximizem distribuição.

8. **Testar hipóteses de formato** — Planejar 2-3 testes rápidos de formato por plataforma prioritária para validar as hipóteses antes de comprometer produção em escala.

9. **Criar platform briefs** — Para cada plataforma prioritária, produzir brief com: regras do jogo, formatos recomendados, ton de voz adaptado, frequência ideal, métricas de sucesso, do's e don'ts.

10. **Montar matriz de distribuição** — Criar matriz cruzando: tipo de conteúdo do movimento x plataforma ideal x formato recomendado x cadência sugerida.

## Outputs Esperados

- **Platform Briefs** para cada plataforma prioritária
- **Matriz de distribuição** conteúdo x plataforma x formato
- **Mapa de comunidades relevantes** por plataforma
- **Cases analisados** com aprendizados
- **Plano de testes de formato** por plataforma

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Plataformas analisadas | >= 5 |
| Platform briefs criados | 100% das plataformas core |
| Cases analisados | >= 3 por plataforma core |
| Comunidades mapeadas | >= 5 por plataforma core |
| Formatos recomendados | >= 3 por plataforma |
| Testes planejados | >= 2 por plataforma prioritária |

## Decision Points

- **Plataforma emergente com fit alto** → Iniciar presença experimental com 30 dias de teste
- **Plataforma em declínio para nosso público** → Reduzir investimento gradualmente
- **Mudança de algoritmo impactante** → Atualizar brief e comunicar squad imediatamente
- **Formato viral descoberto** → Priorizar produção e escalar rapidamente

## Integração

| Tipo | Referência |
|------|-----------|
| **Frameworks** | `frameworks/cycle-cultural-wave-surfing.md`, `frameworks/distribution-trident.md` |
| **Checklists** | `checklists/fenomenologia/signal-source-diversity.md` |
| **Templates** | `templates/outputs/cultural-insight-report.md` |
| **Registries** | `data/research/platform-dynamics/` |
| **Workflows** | `workflows/00-signal-radar-daily.md` |

### Regras de Fluxo
- **Rework:** Se quality gate reprovar → retornar à Fase 1 (varredura) com fontes ampliadas e reexecutar captura
- **Escalation:** Se bloqueio ou decisão fora de escopo → escalar para Movement Chief
- **Handoff:** Output vai para → tasks de Strategy (craft-movement-thesis, design-identity-system)
