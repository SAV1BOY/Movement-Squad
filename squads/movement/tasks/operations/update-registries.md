---
id: update-registries
name: "Atualizar Registros"
squad: movement
type: task
category: operations
agents: [movement-architect]
frameworks: [architect-system-map]
checklists: [governance/decision-log-standard]
templates: [operational/decision-log-entry]
registry: [data/registries/decision-log]
version: "1.0"
tags: [operations, registros, atualizacao, base-conhecimento, documentacao]
---

# Atualizar Registros

## Objetivo

Manter todos os registros, documentos-base e bases de conhecimento do squad atualizados — garantindo que qualquer membro possa encontrar informação correta e atual sem depender de memória individual ou threads de chat.

## Contexto

Informação desatualizada é pior que informação inexistente — porque leva a decisões erradas com confiança. O squad opera com múltiplos documentos vivos: thesis, guidelines, playbooks, inventários, glossários. Se não há rotina de atualização, eles apodrecem em silêncio e ninguém confia neles.

## Inputs Necessários

- Lista de documentos/registros oficiais do squad
- Decisões tomadas em reviews e kaizen
- Novos aprendizados documentados
- Mudanças de estratégia, thesis ou guidelines
- Feedback sobre documentação confusa ou desatualizada
- Changelog do período anterior

## Processo

1. **Inventariar registros ativos** — Manter lista master de todos os documentos oficiais: Thesis Document, Identity System, Glossário, Playbooks (conteúdo, crise, creator, comunidade), Inventário de artefatos, Templates, Checklists.

2. **Verificar data de última atualização** — Para cada registro, checar: quando foi atualizado pela última vez? Se > 30 dias, marcar para revisão. Se > 90 dias, marcar como urgente.

3. **Coletar mudanças pendentes** — Reunir: decisões de reviews que impactam documentos, novos aprendizados que precisam ser incorporados, feedback de que algo está confuso ou errado.

4. **Priorizar atualizações** — Classificar por impacto: (a) Documento usado diariamente pelo squad (alta prioridade), (b) Documento de referência consultado ocasionalmente (média), (c) Documento de arquivo (baixa).

5. **Executar atualizações** — Para cada documento priorizado: incorporar mudanças, corrigir inconsistências, atualizar dados, marcar seções que precisam de revisão profunda futura.

6. **Manter changelog** — Para cada atualização: registrar o que mudou, por que mudou, quando mudou, quem atualizou. Changelog é essencial para rastreabilidade.

7. **Verificar links e referências** — Checar: links internos entre documentos funcionam? Referências cruzadas estão corretas? Templates linkados existem? Exemplos ainda são válidos?

8. **Arquivar versões anteriores** — Antes de sobrescrever, salvar versão anterior com data. Manter pelo menos 2 versões anteriores acessíveis.

9. **Comunicar atualizações relevantes** — Se a atualização impacta como o squad trabalha: comunicar no canal do squad com resumo do que mudou e por quê.

10. **Agendar próxima revisão** — Para cada registro atualizado, definir quando será revisado novamente baseado em sua criticidade e velocidade de mudança.

## Outputs Esperados

- **Registros atualizados** conforme prioridade
- **Changelog** do período documentado
- **Inventário de registros** com status e datas
- **Comunicação** de mudanças relevantes
- **Versões anteriores** arquivadas

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Registros revisados | 100% dos urgentes, >= 50% dos pendentes |
| Changelog | 100% das atualizações registradas |
| Links verificados | >= 90% funcionais |
| Comunicação | 100% das mudanças impactantes |
| Versões anteriores | Arquivadas para documentos críticos |

## Decision Points

- **Documento crítico desatualizado** → Prioridade máxima, atualizar antes da próxima ação que depende dele
- **Documento que ninguém usa** → Avaliar se é necessário ou pode ser aposentado
- **Muitos documentos desatualizados** → Bloquear 1 dia para mutirão de atualização
- **Feedback de confusão** → Reescrever seção confusa, não apenas atualizar dados

## Integração

| Tipo | Referência |
|------|-----------|
| **Frameworks** | `frameworks/architect-system-map.md` |
| **Checklists** | `checklists/governance/decision-log-standard.md` |
| **Templates** | `templates/operational/decision-log-entry.md` |
| **Registries** | `data/registries/decision-log.yaml` |
| **Workflows** | `workflows/05-ralphloop-kaizen-weekly.md` |

### Regras de Fluxo
- **Rework:** Se quality gate reprovar → identificar bloqueio, resolver dependência e reexecutar no próximo ciclo
- **Escalation:** Se bloqueio ou decisão fora de escopo → escalar para Movement Chief
- **Handoff:** Output vai para → todas as tasks que dependem dos registros atualizados
