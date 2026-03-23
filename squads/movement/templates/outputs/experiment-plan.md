---
id: tmpl-mov-out-012
name: Plano de Experimento
squad: movement
type: template
category: outputs
tags: [experimento, plano, teste, execução, hipótese]
---

# Plano de Experimento

## Instruções de Uso

O Plano de Experimento é o documento operacional que detalha como executar o teste
definido no brief de experimento. Enquanto o brief define "o que testar e por quê",
este plano define "como testar, passo a passo".

**Quando usar:** Após aprovação do experiment-brief.
**Quem preenche:** Responsável pela execução do experimento.
**Princípio:** Se o plano tem mais de 2 páginas, o experimento é complexo demais.

---

## Template

### 1. Resumo do Experimento

**ID:** {{experiment_id}}
**Nome:** {{nome_experimento}}
**Hipótese:** {{hipotese}}
**Responsável:** {{responsavel}}
**Período:** {{data_inicio}} a {{data_fim}}

### 2. Setup

**Pré-requisitos:**
- [ ] {{prereq_1}}
- [ ] {{prereq_2}}
- [ ] {{prereq_3}}

**Ferramentas necessárias:**
| Ferramenta | Para quê | Acesso |
|------------|----------|--------|
| {{ferr_1}} | {{para_1}} | {{acesso_1}} |
| {{ferr_2}} | {{para_2}} | {{acesso_2}} |

**Grupo teste:** {{descricao_grupo_teste}}
**Grupo controle:** {{descricao_grupo_controle}}
**Tamanho da amostra:** {{tamanho_amostra}}

### 3. Execução Passo a Passo

| Dia | Ação | Detalhe | Responsável | Check |
|-----|------|---------|-------------|-------|
| D1 | {{acao_d1}} | {{det_d1}} | {{resp_d1}} | [ ] |
| D2 | {{acao_d2}} | {{det_d2}} | {{resp_d2}} | [ ] |
| D3 | {{acao_d3}} | {{det_d3}} | {{resp_d3}} | [ ] |
| D{{n}} | {{acao_dn}} | {{det_dn}} | {{resp_dn}} | [ ] |

### 4. Coleta de Dados

**O que medimos:**
| Métrica | Como coletamos | Frequência | Ferramenta |
|---------|---------------|------------|------------|
| {{met_1}} | {{como_1}} | {{freq_1}} | {{ferr_m1}} |
| {{met_2}} | {{como_2}} | {{freq_2}} | {{ferr_m2}} |
| {{met_3}} | {{como_3}} | {{freq_3}} | {{ferr_m3}} |

**Dados qualitativos a observar:**
- {{quali_1}}
- {{quali_2}}

### 5. Critérios de Decisão

| Resultado | Threshold | Decisão |
|-----------|-----------|---------|
| Sucesso | {{threshold_sucesso}} | {{decisao_sucesso}} |
| Parcial | {{threshold_parcial}} | {{decisao_parcial}} |
| Fracasso | {{threshold_fracasso}} | {{decisao_fracasso}} |

### 6. Riscos e Contingências

| Risco | Se acontecer | Ação |
|-------|-------------|------|
| {{risco_1}} | {{sinal_1}} | {{acao_cont_1}} |
| {{risco_2}} | {{sinal_2}} | {{acao_cont_2}} |

### 7. Comunicação

**Quem precisa saber:**
| Pessoa | O quê | Quando |
|--------|-------|--------|
| {{pessoa_1}} | {{info_1}} | {{quando_1}} |
| {{pessoa_2}} | {{info_2}} | {{quando_2}} |

### 8. Pós-Experimento

- [ ] Consolidar dados em relatório
- [ ] Apresentar resultados ao squad
- [ ] Documentar aprendizados no learning-entry
- [ ] Tomar decisão go/no-go
- [ ] Atualizar backlog de experimentos

---

## Exemplo Preenchido

### Resumo
**Nome:** Desafio do Rótulo no Onboarding
**Hipótese:** Enviar desafio por WhatsApp no dia 1 aumenta engajamento em 30%.
**Período:** 10 dias de coleta + 2 dias de análise.

### Execução
| Dia | Ação | Detalhe |
|-----|------|---------|
| D1 | Configurar grupos | 100 novos membros divididos aleatoriamente |
| D2-D11 | Enviar desafio (grupo A) | WhatsApp às 10h: foto do rótulo + pergunta |
| D2-D11 | Monitorar (grupo B) | Onboarding padrão sem desafio |
| D12 | Coletar métricas | Posts no Discord, mensagens, reações |
| D13 | Analisar e decidir | Comparar grupo A vs B |

### Decisão
| Resultado | Threshold | Decisão |
|-----------|-----------|---------|
| Sucesso | >30% engajamento grupo A vs B | Implementar no onboarding oficial |
| Fracasso | <10% diferença | Testar formato alternativo |

---

## Dicas

- **O plano deve caber em 1 página mental.** Se é difícil de explicar, simplifique.
- **Randomize a amostra.** Viés de seleção invalida qualquer resultado.
- **Documente desvios.** Se algo não saiu como planejado, anote. Isso é dado.
- **Não estenda o prazo.** Se os dados não são claros em 2 semanas, o experimento precisa ser redesenhado.
- **Compartilhe resultados crus.** Transparência nos dados gera confiança na decisão.
