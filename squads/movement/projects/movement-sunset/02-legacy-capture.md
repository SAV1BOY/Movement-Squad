---
id: ms-02
name: Captura de Legado
squad: movement
type: project-phase
category: movement-sunset
phase: 2-legacy
tags:
  - sunset
  - legado
  - aprendizado
  - knowledge-transfer
  - arquivo
---

# 02 · Captura de Legado

## Objetivo da Fase

Capturar todo o conhecimento, aprendizado e ativos reutilizáveis gerados pelo
movimento antes do encerramento. O investimento feito no movimento não deve morrer
com ele — cada insight, template, pesquisa e relação deve ser preservada e
transferida para beneficiar iniciativas futuras.

## Inputs

- Todo o acervo do movimento (artefatos, pesquisas, dados, templates)
- Experiment log completo com resultados
- Feedback e depoimentos da comunidade
- Registros de decisões e pivots
- Métricas históricas e Health Score
- Relacionamentos com champions e parceiros

## Processo

1. **Knowledge Transfer** — Documentar todo conhecimento tácito que existe apenas
   na cabeça dos membros do time. Realizar sessões de debriefing individual com
   cada pessoa que trabalhou no movimento.

2. **Inventário de Registros** — Catalogar todos os registros do movimento:
   experiment logs, decision logs, meeting notes, retrospectivas.
   Organizar em formato pesquisável.

3. **Extração de Lessons Learned** — Sistematizar os aprendizados em formato
   estruturado que outros times possam consumir. Separar por categoria:
   estratégia, execução, comunidade, distribuição, métricas.

4. **Identificação de Ativos Reutilizáveis** — Separar ativos que podem ser
   reaproveitados em outros movimentos ou projetos: templates testados, pesquisas
   de mercado, dados de audiência, relacionamentos com influenciadores.

5. **Arquivo do Movimento** — Criar pacote de arquivo completo com estrutura
   padronizada que permita consulta futura.

6. **Entrevistas de Legado** — Entrevistar 3-5 membros mais ativos da comunidade
   para capturar a perspectiva de quem viveu o movimento de dentro.

7. **Documentação de Anti-Patterns** — Documentar o que NÃO fazer, com base nas
   falhas e erros do movimento. Tão valioso quanto os sucessos.

## Knowledge Transfer

### Sessão de Debriefing (por pessoa)

```yaml
debriefing:
  participante: ""
  papel: ""
  duração: "60 min"
  perguntas:
    - "Qual foi a decisão mais importante que você tomou neste movimento?"
    - "O que você faria diferente se começasse de novo?"
    - "Qual insight sobre o público-alvo ninguém documentou?"
    - "Qual processo funcionou melhor e qual funcionou pior?"
    - "Que relacionamento construído aqui tem valor para futuras iniciativas?"
  insights_capturados: []
  artefatos_mencionados: []
  recomendações: []
```

## Registro de Arquivo

### Estrutura do Arquivo

```
archive/[nome-do-movimento]/
├── 00-overview.md          → Resumo do movimento (1 página)
├── 01-thesis-evolution.md  → Como a tese evoluiu ao longo do tempo
├── 02-experiment-log.yaml  → Todos os experimentos e resultados
├── 03-metrics-history.md   → Evolução de métricas-chave
├── 04-lessons-learned.md   → Aprendizados estruturados
├── 05-anti-patterns.md     → O que não fazer
├── 06-reusable-assets/     → Templates, pesquisas, dados reutilizáveis
├── 07-community-legacy.md  → Depoimentos, impacto, destino da comunidade
└── 08-final-report.md      → Relatório final (link para fase 03)
```

## Lessons Learned

### Formato por Aprendizado

```yaml
aprendizado:
  id: "LL-XXX"
  categoria: "" # estratégia | execução | comunidade | distribuição | métricas
  título: ""
  contexto: "" # situação que gerou o aprendizado
  o_que_aconteceu: "" # fato
  o_que_aprendemos: "" # insight
  o_que_faríamos_diferente: "" # recomendação acionável
  evidência: "" # dados ou exemplos que sustentam
  aplicabilidade: "" # em que tipo de projeto futuro isso se aplica
  tags: []
```

### Categorias de Aprendizado

| Categoria | O que Capturar |
|-----------|---------------|
| Estratégia | Tese, posicionamento, timing, público-alvo |
| Execução | Processos, cadência, ferramentas, handoffs |
| Comunidade | Recrutamento, engajamento, rituais, champions |
| Distribuição | Canais, formatos, parcerias, amplificação |
| Métricas | O que medir, como medir, benchmarks descobertos |

## Ativos Reutilizáveis

### Classificação de Ativos

| Tipo de Ativo | Exemplo | Ação |
|--------------|---------|------|
| Template validado | Template de manifesto que performou bem | Mover para lib/templates/ |
| Pesquisa | Estudo etnográfico do público | Mover para archive/ com tag pesquisável |
| Dados de audiência | Personas validadas, segmentações | Mover para data/research/ |
| Relacionamentos | Champions, influenciadores, parceiros | Documentar em CRM do squad |
| Frameworks testados | Adaptações de framework que funcionaram | Propor merge no framework original |
| Conteúdo evergreen | Peças que não dependem de timing | Mover para swipe/ |

## Outputs

- [ ] Debriefings realizados com todos os membros do time
- [ ] Inventário completo de registros catalogado
- [ ] Documento de Lessons Learned (mínimo 10 aprendizados)
- [ ] Documento de Anti-Patterns (mínimo 5 anti-patterns)
- [ ] Lista de ativos reutilizáveis com destino definido
- [ ] Entrevistas de legado com membros da comunidade
- [ ] Pacote de arquivo estruturado e armazenado
- [ ] Ativos reutilizáveis movidos para seus destinos

## Quality Gate

| Critério                          | Mínimo Aceitável                            |
|-----------------------------------|---------------------------------------------|
| Debriefings completos             | 100% do time core entrevistado              |
| Lessons learned documentados      | Mínimo 10, cobrindo as 5 categorias         |
| Ativos reutilizáveis identificados | Lista completa com destino definido         |
| Arquivo estruturado               | Seguindo formato padronizado                |
| Entrevistas de legado             | Mínimo 3 membros da comunidade              |
| Anti-patterns documentados        | Mínimo 5 com contexto e evidência           |

## Próxima Fase

→ `03-final-report.md` — Com o legado capturado, consolidar tudo em um relatório
final que serve como registro histórico e referência para o futuro.

### Riscos Comuns Nesta Fase

- Pressa para encerrar sem capturar — investir tempo agora economiza muito depois
- Conhecimento tácito perdido — debriefings individuais são insubstituíveis
- Ativos abandonados — se não mover agora, perde-se para sempre
- Viés de narrativa — documentar falhas com a mesma diligência que sucessos
- Arquivo inacessível — formato e localização devem ser pesquisáveis
