---
id: map-counter-narratives
name: "Mapear Contra-Narrativas"
squad: movement
type: task
category: research
agents: [fenomenologo]
frameworks: [phenomenology-counter-narrative, narrative-graph-framework]
checklists: [fenomenologia/counter-signal-capture]
templates: [outputs/cultural-insight-report]
registry: [data/research/counter-narratives]
version: "1.0"
tags: [research, contra-narrativas, risco, narrativa, oposicao]
---

# Mapear Contra-Narrativas

## Objetivo

Identificar, catalogar e analisar as contra-narrativas — argumentos, críticas, ceticismos e oposições — que existem ou podem surgir contra o movimento, preparando o squad para responder com autenticidade e consistência.

## Contexto

Todo movimento gera oposição. Se ninguém discorda, o movimento não está dizendo nada forte o suficiente. Mas ser surpreendido por uma contra-narrativa poderosa pode destruir credibilidade em horas. Mapear as contra-narrativas proativamente permite construir respostas antes que sejam necessárias e, em alguns casos, fortalecer a thesis incorporando críticas legítimas.

## Inputs Necessários

- Thesis e manifesto atuais do movimento
- Posicionamentos públicos da marca/movimento
- Histórico de crises e backlash no setor
- Comentários críticos e negativos coletados
- Posicionamentos de concorrentes que contradizem o nosso

## Processo

1. **Identificar oposições explícitas** — Coletar críticas diretas ao movimento, à marca ou ao setor: reviews negativos, threads de hate, artigos críticos, comentários de detratores, posts de concorrentes.

2. **Identificar oposições implícitas** — Mapear ceticismos que não são vocalizados diretamente mas se manifestam como: abandono silencioso, baixo engajamento em certos temas, ironia/sarcasmo, memes depreciativos.

3. **Categorizar por natureza** — Classificar cada contra-narrativa: (a) Crítica legítima (tem fundamento real), (b) Mal-entendido (a mensagem não foi clara), (c) Oposição ideológica (discordância de valores), (d) Ataque oportunista (concorrente ou troll), (e) Ceticismo saudável (questiona mas está aberto).

4. **Avaliar potência** — Para cada contra-narrativa, medir: (a) Base factual (1-5), (b) Ressonância emocional (1-5), (c) Potencial viral (1-5), (d) Tamanho do grupo que sustenta (1-5), (e) Risco reputacional (1-5).

5. **Mapear porta-vozes da oposição** — Identificar quem articula as contra-narrativas: influenciadores, jornalistas, concorrentes, ex-membros, ativistas. Entender suas motivações e alcance.

6. **Analisar vulnerabilidades reais** — Para cada crítica legítima, avaliar honestamente: "Eles têm razão?" Se sim, documentar a vulnerabilidade e recomendar ação corretiva antes que se torne crise.

7. **Criar matriz de resposta** — Para cada contra-narrativa priorizada, desenvolver: (a) Resposta padrão (1-2 frases), (b) Resposta expandida (para contextos que exigem profundidade), (c) Ação corretiva (se aplicável), (d) Tom recomendado (empático, firme, educativo, silêncio estratégico).

8. **Definir protocolos de escalação** — Estabelecer quando uma contra-narrativa deve ser: ignorada, respondida por community manager, respondida por liderança, ou tratada como crise.

9. **Simular cenários de backlash** — Para as 3 contra-narrativas mais potentes, simular: como se espalhariam, quem amplificaria, qual seria o dano, como responderíamos passo a passo.

10. **Documentar e treinar** — Compilar tudo em um Counter-Narrative Playbook acessível a todo o squad e treinar porta-vozes nas respostas preparadas.

## Outputs Esperados

- **Counter-Narrative Cards** catalogados (mínimo 15)
- **Matriz de resposta** com respostas preparadas
- **Protocolos de escalação** definidos
- **Cenários de backlash** simulados (top 3)
- **Counter-Narrative Playbook** compilado
- **Lista de vulnerabilidades reais** com ações corretivas

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Contra-narrativas mapeadas | >= 15 |
| Categorias representadas | >= 3 das 5 categorias |
| Respostas preparadas | 100% das priorizadas |
| Cenários simulados | >= 3 |
| Vulnerabilidades reais documentadas | 100% |
| Protocolos de escalação | Definidos para todos os níveis |

## Decision Points

- **Crítica legítima identificada** → Parar e corrigir antes de continuar ativação
- **Contra-narrativa ganhando tração** → Ativar protocolo de resposta imediata
- **Porta-voz influente atacando** → Escalar para liderança e avaliar engagement direto
- **Vulnerabilidade sistêmica encontrada** → Reunião emergencial com stakeholders

## Integração

| Tipo | Referência |
|------|-----------|
| **Frameworks** | `frameworks/phenomenology-counter-narrative.md`, `frameworks/narrative-graph-framework.md` |
| **Checklists** | `checklists/fenomenologia/counter-signal-capture.md` |
| **Templates** | `templates/outputs/cultural-insight-report.md` |
| **Registries** | `data/research/counter-narratives/` |
| **Workflows** | `workflows/00-signal-radar-daily.md` |

### Regras de Fluxo
- **Rework:** Se quality gate reprovar → retornar à Fase 1 (varredura) com fontes ampliadas e reexecutar captura
- **Escalation:** Se bloqueio ou decisão fora de escopo → escalar para Movement Chief
- **Handoff:** Output vai para → tasks de Strategy (craft-movement-thesis, design-identity-system)
