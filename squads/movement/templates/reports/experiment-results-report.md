---
id: tmpl-mov-rep-005
name: Relatório de Resultados de Experimento
squad: movement
type: template
category: reports
tags: [experimento, resultados, análise, decisão, aprendizado]
---

# Relatório de Resultados de Experimento

## Instruções de Uso

Este relatório documenta os resultados de um experimento concluído. É o documento que
transforma dados em decisão. Deve ser claro o suficiente para que qualquer pessoa do
squad entenda o que testamos, o que descobrimos e o que fazer a seguir.

**Quando usar:** Imediatamente após a conclusão do período de teste.
**Quem preenche:** Responsável pela execução do experimento.
**Prazo:** Até 48h após o fim da coleta de dados.

---

## Template

### 1. Ficha do Experimento

| Campo | Valor |
|-------|-------|
| ID | {{experiment_id}} |
| Nome | {{nome}} |
| Hipótese | {{hipotese}} |
| Período | {{data_inicio}} a {{data_fim}} |
| Responsável | {{responsavel}} |
| Amostra | {{tamanho_amostra}} |

### 2. Resultado Principal

**Veredicto:** {{veredicto — Confirmada / Refutada / Inconclusiva}}

**Resumo em 1 frase:** {{resumo}}

### 3. Dados

**Métrica principal:**
| Grupo | Valor | N |
|-------|-------|---|
| Teste | {{valor_teste}} | {{n_teste}} |
| Controle | {{valor_controle}} | {{n_controle}} |
| Diferença | {{diferenca}} | — |

**Threshold definido:** {{threshold}}
**Resultado vs. threshold:** {{resultado_vs_threshold}}

**Métricas secundárias:**
| Métrica | Teste | Controle | Diferença |
|---------|-------|----------|-----------|
| {{sec_1}} | {{test_s1}} | {{ctrl_s1}} | {{dif_s1}} |
| {{sec_2}} | {{test_s2}} | {{ctrl_s2}} | {{dif_s2}} |

### 4. Dados Qualitativos

**Observações durante o experimento:**
- {{obs_1}}
- {{obs_2}}
- {{obs_3}}

**Feedback dos participantes:**
{{feedback}}

**Comportamentos inesperados:**
{{inesperados}}

### 5. Análise

**Por que achamos que isso aconteceu:**
{{analise_causal}}

**Fatores que podem ter influenciado:**
{{fatores_confusao}}

**Limitações do experimento:**
{{limitacoes}}

### 6. Decisão

| Opção | Descrição | Recomendação |
|-------|-----------|-------------|
| Escalar | {{desc_escalar}} | {{rec_escalar}} |
| Iterar | {{desc_iterar}} | {{rec_iterar}} |
| Pivotar | {{desc_pivotar}} | {{rec_pivotar}} |
| Abandonar | {{desc_abandonar}} | {{rec_abandonar}} |

**Decisão tomada:** {{decisao_final}}
**Aprovada por:** {{aprovador}}

### 7. Próximos Passos

| Ação | Responsável | Prazo |
|------|-------------|-------|
| {{prox_1}} | {{resp_1}} | {{prazo_1}} |
| {{prox_2}} | {{resp_2}} | {{prazo_2}} |

### 8. Aprendizados para o Banco

{{aprendizados — o que agora sabemos que antes não sabíamos}}

---

## Exemplo Preenchido

### Ficha
| Campo | Valor |
|-------|-------|
| Nome | Desafio do Rótulo no Onboarding |
| Hipótese | WhatsApp no dia 1 aumenta engajamento em 30% |
| Período | 01/03 a 11/03/2026 |
| Amostra | 200 (100 teste, 100 controle) |

### Resultado
**Veredicto:** Confirmada
**Resumo:** O desafio por WhatsApp aumentou o engajamento da primeira semana em 42%.

### Dados
| Grupo | Engajamento 7d | N |
|-------|---------------|---|
| Teste (com desafio) | 47% | 100 |
| Controle (sem) | 33% | 100 |
| Diferença | +42% relativo | — |

### Decisão
**Decisão:** Escalar — implementar como parte oficial do onboarding a partir de 15/03.

---

## Dicas

- **Dados antes de opinião.** Mostre os números crus antes de interpretar.
- **Reconheça limitações.** Experimentos imperfeitos são normais. Transparência é obrigatória.
- **Decisão clara.** O relatório deve terminar com UMA decisão, não com "vamos pensar".
- **Documente para o futuro.** Alguém vai querer saber por que fizemos X. Este relatório responde.
- **Comportamentos inesperados são ouro.** Muitas vezes o aprendizado está no que não medimos.
