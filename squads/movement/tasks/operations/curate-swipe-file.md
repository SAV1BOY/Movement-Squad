---
id: curate-swipe-file
name: "Curadoria do Swipe File"
squad: movement
type: task
category: operations
agents: [manifestador, fenomenologo, identitario]
frameworks: [memetic-variation-selection]
checklists: [memetic-asset-quality]
templates: []
registry: [data/registries/memetic-assets]
version: "1.0"
tags: [operations, swipe-file, referencias, inspiracao, curadoria]
---

# Curadoria do Swipe File

## Objetivo

Manter um swipe file vivo e organizado — coleção curada de referências inspiracionais de movimentos, campanhas, memes, manifestos, rituais e estéticas — que sirva como banco de inspiração e benchmarking para todo o squad de criação.

## Contexto

Criatividade não nasce do vácuo. Os melhores criativos são também os melhores consumidores de referências. O swipe file é a biblioteca de inspiração do squad — onde qualquer membro vai quando precisa de uma faísca, uma referência para briefing ou um benchmark para avaliar a qualidade do próprio trabalho.

## Inputs Necessários

- Referências coletadas por membros do squad ao longo da semana
- Exemplos encontrados durante pesquisa de sinais e tendências
- Cases de creators e movimentos referência
- Benchmarks de concorrentes e movimentos similares
- Pedidos de referência de membros do squad

## Processo

1. **Coletar referências contínuas** — Todo membro do squad alimenta: ao encontrar algo inspirador (post, campanha, meme, manifesto, ritual, estética), salvar imediatamente no canal compartilhado com tag de categoria.

2. **Categorizar por tipo** — Organizar em: (a) Manifestos e textos, (b) Memes e formatos virais, (c) Identidade visual, (d) Rituais e experiências, (e) Campanhas de movimento, (f) Creators e influenciadores, (g) PR e earned media, (h) Community building.

3. **Tagear por qualidade e relevância** — Para cada entrada, adicionar: (a) Score de inspiração (1-5), (b) Relevância para nosso movimento (1-5), (c) O que especificamente é bom nesta referência.

4. **Escrever nota de curadoria** — Para entradas com score >= 4: escrever 2-3 frases sobre por que é relevante, o que podemos aprender, como poderia ser adaptada para nosso contexto.

5. **Criar boards temáticos** — Organizar referências em boards visuais por tema/projeto: board de manifesto, board de memes, board de estética, board de rituais. Boards são mais acessíveis que listas.

6. **Destacar referência da semana** — Toda semana, selecionar 1 referência excepcional e compartilhar com o squad no ritual de abertura: o que é, por que importa, o que aprendemos.

7. **Limpar e arquivar** — Mensalmente: revisar entradas antigas. Se referência ficou datada ou irrelevante, mover para arquivo. Manter o swipe file fresco e navegável.

8. **Catalogar anti-referências** — Criar seção de "o que não fazer": exemplos de movimentos que falharam, campanhas que deram errado, estéticas ultrapassadas. Anti-referências educam tanto quanto boas referências.

9. **Solicitar referências direcionadas** — Quando o squad precisa de inspiração específica (ex: "rituais digitais para comunidades de 1000+ pessoas"), fazer call de contribuição direcionado.

10. **Medir utilização** — Rastrear: com que frequência o swipe file é consultado? Quais boards são mais acessados? Quais categorias têm mais/menos entradas? Ajustar curadoria conforme uso real.

## Outputs Esperados

- **Swipe file** organizado e atualizado continuamente
- **Boards temáticos** visuais navegáveis
- **Notas de curadoria** para entradas destaque
- **Referência da semana** compartilhada
- **Seção de anti-referências** mantida

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Novas entradas/semana | >= 5 |
| Categorias cobertas | >= 6 das 8 |
| Notas de curadoria | >= 50% das entradas score 4+ |
| Referência da semana | Toda semana |
| Limpeza mensal | Realizada |
| Anti-referências | >= 10 catalogadas |

## Decision Points

- **Swipe file pouco consultado** → Melhorar organização, tornar mais visual e acessível
- **Categoria vazia** → Direcionar pesquisa para preencher gaps
- **Referências muito concentradas em uma estética** → Diversificar intencionalmente
- **Equipe não contribui** → Criar incentivo ou integrar contribuição em rituais existentes

## Integração

| Tipo | Referência |
|------|-----------|
| **Frameworks** | `frameworks/memetic-variation-selection.md` |
| **Checklists** | `checklists/memetic-asset-quality.md` |
| **Templates** | — |
| **Registries** | `data/registries/memetic-assets/` |
| **Workflows** | `workflows/05-ralphloop-kaizen-weekly.md` |

### Regras de Fluxo
- **Rework:** Se quality gate reprovar → identificar bloqueio, resolver dependência e reexecutar no próximo ciclo
- **Escalation:** Se bloqueio ou decisão fora de escopo → escalar para Movement Chief
- **Handoff:** Output vai para → todas as tasks que dependem dos registros atualizados
