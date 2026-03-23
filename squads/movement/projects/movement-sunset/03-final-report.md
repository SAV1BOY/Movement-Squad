---
id: ms-03
name: Relatório Final de Sunset
squad: movement
type: project-phase
category: movement-sunset
phase: 3-final-report
tags:
  - sunset
  - relatório
  - encerramento
  - retrospectiva
  - documentação
---

# 03 · Relatório Final de Sunset

## Objetivo da Fase

Consolidar toda a jornada do movimento em um relatório final que serve como registro
histórico, referência para decisões futuras e prestação de contas para stakeholders.
Este documento é o capítulo final do movimento — deve ser honesto, completo e útil.

## Inputs

- Avaliação de sunset (fase 00)
- Plano de wind-down executado (fase 01)
- Legacy capture completo (fase 02)
- Métricas históricas completas
- Feedback da comunidade durante o sunset
- Status de todos os compromissos

## Processo

1. **Timeline Recap** — Reconstruir a linha do tempo completa do movimento,
   desde a concepção até o encerramento. Marcar momentos-chave: lançamento,
   pivots, picos, declínios, decisão de sunset.

2. **Consolidação de Métricas Finais** — Compilar todas as métricas finais em
   formato comparativo: target original vs. resultado final. Incluir evolução
   temporal das métricas-chave.

3. **Status da Comunidade** — Documentar o destino da comunidade: quantos membros
   migraram, quantos permaneceram em grupo autogerido, impacto percebido.

4. **Síntese de Learnings** — Extrair os 5-7 aprendizados mais importantes de
   todo o legacy capture e apresentá-los de forma executiva.

5. **Recomendações** — Com base nos aprendizados, formular recomendações concretas
   para futuras iniciativas do squad.

6. **Revisão e Aprovação** — Apresentar relatório para stakeholders, coletar
   feedback final, obter sign-off.

7. **Arquivamento** — Armazenar relatório como documento de referência permanente.

## Estrutura do Relatório Final

### Seção 1: Resumo Executivo

```yaml
resumo:
  nome_do_movimento: ""
  período: "" # data início — data fim
  duração_total: "" # em meses
  tese_central: "" # em uma frase
  resultado_geral: "" # em uma frase
  motivo_do_sunset: "" # em uma frase
  investimento_total: "" # budget + horas estimadas
  principal_aprendizado: "" # em uma frase
```

### Seção 2: Timeline Recap

| Data | Marco | Descrição |
|------|-------|-----------|
| YYYY-MM | Concepção | Brief inicial e definição de win conditions |
| YYYY-MM | Pesquisa | Fase de pesquisa cultural e validação de tese |
| YYYY-MM | Lançamento | Primeiro artefato público e ativação da comunidade |
| YYYY-MM | Pico | Momento de maior tração e engajamento |
| YYYY-MM | Pivot (se houver) | Mudança de direção e motivo |
| YYYY-MM | Declínio | Início da queda de métricas |
| YYYY-MM | Decisão de sunset | Avaliação formal e decisão de encerrar |
| YYYY-MM | Encerramento | Última atividade e arquivamento |

### Seção 3: Métricas Finais

```yaml
métricas:
  alcance:
    total_impressões: 0
    alcance_único: 0
    melhor_mês: ""
  engajamento:
    total_interações: 0
    taxa_média_engajamento: ""
    melhor_peça: ""
  comunidade:
    membros_no_pico: 0
    membros_ativos_no_pico: 0
    taxa_retenção_média: ""
    champions_ativos: 0
  conversão:
    leads_gerados: 0
    conversões_atribuídas: 0
    custo_por_lead: ""
  health_score:
    máximo_atingido: 0
    média_geral: 0
    score_final: 0
```

### Seção 4: Win Conditions — Resultado Final

| Win Condition | Target | Resultado | Status |
|--------------|--------|-----------|--------|
| [WC1] | [target] | [resultado] | Superou / Atingiu / Quase / Falhou |
| [WC2] | [target] | [resultado] | Superou / Atingiu / Quase / Falhou |
| [WC3] | [target] | [resultado] | Superou / Atingiu / Quase / Falhou |

### Seção 5: Status da Comunidade Pós-Sunset

```yaml
comunidade_pós_sunset:
  destino: "" # autogerida | migrada | encerrada | hibernada
  membros_transicionados: 0
  canal_atual: "" # onde a comunidade está agora
  liderança: "" # quem lidera (se autogerida)
  sentimento_geral: "" # positivo | neutro | negativo
  depoimentos_finais: []
```

### Seção 6: Top Learnings

Formato para cada aprendizado:

```yaml
learning:
  número: 1
  título: ""
  contexto: "" # em 2-3 frases
  insight: "" # o que aprendemos
  recomendação: "" # o que fazer diferente
  aplicável_a: "" # que tipo de projeto futuro se beneficia
```

### Seção 7: Recomendações para o Futuro

```yaml
recomendações:
  - id: "REC-01"
    área: "" # estratégia | execução | comunidade | distribuição | métricas
    recomendação: ""
    justificativa: ""
    prioridade: "" # alta | média | baixa
  - id: "REC-02"
    área: ""
    recomendação: ""
    justificativa: ""
    prioridade: ""
```

## Outputs

- [ ] Relatório final completo seguindo estrutura padronizada
- [ ] Resumo executivo de 1 página
- [ ] Timeline visual do movimento
- [ ] Comparativo de win conditions (target vs. resultado)
- [ ] Top 5-7 learnings formatados
- [ ] Recomendações priorizadas para futuras iniciativas
- [ ] Sign-off de stakeholders
- [ ] Arquivo permanente criado e catalogado

## Quality Gate

| Critério                          | Mínimo Aceitável                          |
|-----------------------------------|-------------------------------------------|
| Todas as seções preenchidas       | 7 seções completas com dados reais        |
| Métricas finais consolidadas      | Dados de todas as fontes compilados       |
| Win conditions avaliadas          | Todas com status e evidência              |
| Learnings documentados            | Mínimo 5, cobrindo múltiplas categorias   |
| Recomendações formuladas          | Mínimo 3 recomendações acionáveis         |
| Stakeholders sign-off             | Aprovação formal documentada              |

## Fechamento

Este documento marca o encerramento oficial do movimento. O relatório deve ser
armazenado no arquivo permanente do squad e referenciado sempre que um novo
movimento for concebido no mesmo território temático.

Um sunset bem documentado não é um ponto final — é uma vírgula. Os aprendizados
vivem adiante em cada novo movimento que se beneficia do que foi descoberto aqui.

### Riscos Comuns Nesta Fase

- Relatório superficial — investir tempo em profundidade, não apenas em completude
- Métricas maquiadas — reportar com honestidade, incluindo fracassos
- Learnings genéricos — "planejar melhor" não é aprendizado, é platitude
- Recomendações vagas — cada recomendação deve ser acionável por alguém específico
- Arquivo inacessível — garantir que o relatório seja encontrável daqui a 2 anos
