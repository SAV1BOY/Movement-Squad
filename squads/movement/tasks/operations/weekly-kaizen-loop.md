---
id: weekly-kaizen-loop
name: "Loop Semanal de Aprendizado (Kaizen)"
squad: movement
type: task
category: operations
agents: [arquiteto-movimento, estrategista-movimento, analista-impacto]
frameworks: [kaizen-loop-framework, retrospective-model]
checklists: [kaizen-checklist]
templates: [kaizen-template, learning-log-template]
version: "1.0"
tags: [operations, semanal, kaizen, aprendizado, melhoria-continua]
---

# Loop Semanal de Aprendizado (Kaizen)

## Objetivo

Conduzir sessão semanal de aprendizado e melhoria contínua — revisando o que fizemos na semana, o que aprendemos, o que funcionou e o que ajustar — mantendo o squad em ciclo constante de evolução e impedindo que erros se repitam.

## Contexto

Kaizen é melhoria contínua incremental. Não esperar o review mensal para ajustar — a cada semana, o squad aprende algo e melhora algo. Sessões curtas (30-45min) mas consistentes são mais poderosas que reviews longos esporádicos. O acúmulo de pequenas melhorias gera resultados exponenciais.

## Inputs Necessários

- Métricas da semana (health score, community, content)
- Weekly Signal Digest
- Feedback recebido de membros e stakeholders
- Resultados de ações/experimentos da semana
- Issues e bloqueios encontrados
- Learnings informais do squad

## Processo

1. **Check-in rápido** (5min) — Cada membro do squad em 1 frase: como se sentiu sobre o trabalho da semana? Energia alta, média ou baixa?

2. **Revisar métricas-chave** (5min) — Dashboard rápido: Health Score da semana, métricas que subiram, métricas que caíram, alertas. Só números, sem discussão profunda ainda.

3. **O que funcionou** (10min) — Cada membro compartilha 1 coisa que funcionou bem na semana. Pode ser: conteúdo que performou, interação com membro, processo que fluiu, insight que teve. Documentar os "wins".

4. **O que não funcionou** (10min) — Cada membro compartilha 1 coisa que não funcionou ou poderia melhorar. Sem julgamento — foco em aprendizado. Documentar os "learnings".

5. **Identificar causa raiz** (5min) — Para os 2-3 "não funcionou" mais impactantes: qual é a causa raiz? É processo, é ferramenta, é comunicação, é prioridade, é recurso?

6. **Definir 1-3 ajustes** (5min) — Selecionar no máximo 3 ajustes concretos para a próxima semana. Cada ajuste com: o que muda, quem é responsável, como sabemos que melhorou.

7. **Revisar ajustes da semana anterior** (5min) — Os ajustes definidos na semana passada foram implementados? Funcionaram? Se não, por que não?

8. **Olhar para frente** (5min) — Preview da próxima semana: prioridades, datas importantes, riscos, dependências. Alinhar expectativas.

9. **Documentar no Learning Log** — Registrar: wins da semana, learnings, causa raiz, ajustes definidos, status de ajustes anteriores. Manter log acessível e pesquisável.

10. **Encerrar com energia** — Terminar com: reconhecimento de algo/alguém da semana, frase motivacional conectada com a thesis, ou momento leve para fechar bem.

## Outputs Esperados

- **Kaizen Session** realizada semanalmente
- **Learning Log** atualizado
- **1-3 ajustes** definidos para a semana
- **Status de ajustes anteriores** revisado
- **Preview da próxima semana** alinhado

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Sessão realizada | Toda semana sem exceção |
| Duração | 30-45 minutos máximo |
| Participação | >= 80% do squad |
| Ajustes definidos | 1-3 por semana |
| Learning Log | Atualizado em até 2h pós-sessão |
| Ajustes anteriores revisados | 100% verificados |

## Decision Points

- **Mesmo problema aparecendo 3+ semanas** → Escalar para mudança estrutural, não incremental
- **Energia do squad baixa consistentemente** → Avaliar workload e priorizar redução de escopo
- **Muitos ajustes não implementados** → Reduzir para 1 ajuste/semana e focar em execução
- **Squad sem learnings** → Falta de experimentação — provocar mais testes

## Integração

- **Alimenta:** `impact-review`, `monthly-movement-review`, todas as tasks de melhoria
- **Recebe de:** `weekly-signal-radar`, métricas diárias, feedback da comunidade
- **Workflow relacionado:** `05-ralphloop-kaizen-weekly`
- **Cadência:** Semanal (sessão fixa, mesmo dia/horário)
- **Handoff:** Learning Log acessível a todo o squad e usado em reviews mensais
