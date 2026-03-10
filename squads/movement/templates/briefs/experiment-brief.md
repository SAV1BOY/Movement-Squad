---
id: tmpl-mov-brief-009
name: Brief de Experimento
squad: movement
type: template
category: briefs
tags: [experimento, teste, hipótese, aprendizado]
---

# Brief de Experimento

## Instruções de Uso

Este brief estrutura experimentos do movimento — testes rápidos para validar hipóteses
antes de investir em escala. Todo movimento deve operar com mentalidade experimental:
testar rápido, aprender rápido, decidir com evidência.

**Quando usar:** Sempre que houver uma hipótese a validar antes de escalar.
**Quem preenche:** Quem propõe o experimento + líder do movimento.
**Princípio:** Se não dá pra testar em 2 semanas com budget mínimo, simplifique.

---

## Template

### 1. Hipótese

**Declaração da hipótese:**
"Acreditamos que {{ação}} para {{público}} resultará em {{resultado}} porque {{razão}}."

**Nível de confiança atual (1-10):** {{confianca}}
**O que muda se for verdade:** {{impacto_se_verdade}}
**O que muda se for falso:** {{impacto_se_falso}}

### 2. Design do Experimento

**Tipo de teste:** {{tipo — ex: A/B, piloto, MVP, enquete, protótipo}}
**Variável independente:** {{variavel_independente — o que estamos mudando}}
**Variável dependente:** {{variavel_dependente — o que estamos medindo}}
**Controle:** {{controle — contra o que comparamos}}

### 3. Execução

**Duração:** {{duracao}}
**Amostra:** {{amostra — tamanho e perfil}}
**Canal:** {{canal}}
**Responsável:** {{responsavel}}

**Passo a passo:**
1. {{passo_1}}
2. {{passo_2}}
3. {{passo_3}}
4. {{passo_4}}
5. {{passo_5}}

### 4. Critérios de Sucesso

**Métrica principal:** {{metrica_principal}}
**Threshold de sucesso:** {{threshold — ex: >15% de conversão}}
**Threshold de fracasso:** {{threshold_fracasso — ex: <5%}}
**Zona cinzenta:** {{zona_cinzenta — o que fazemos se ficar no meio}}

### 5. Recursos Necessários

| Recurso | Quantidade | Custo | Disponível? |
|---------|-----------|-------|-------------|
| {{recurso_1}} | {{qtd_1}} | {{custo_1}} | {{disp_1}} |
| {{recurso_2}} | {{qtd_2}} | {{custo_2}} | {{disp_2}} |
| {{recurso_3}} | {{qtd_3}} | {{custo_3}} | {{disp_3}} |

### 6. Riscos do Experimento

| Risco | Probabilidade | Impacto | Mitigação |
|-------|--------------|---------|-----------|
| {{risco_1}} | {{prob_1}} | {{imp_1}} | {{mit_1}} |
| {{risco_2}} | {{prob_2}} | {{imp_2}} | {{mit_2}} |

### 7. Timeline

| Etapa | Data início | Data fim | Responsável |
|-------|------------|----------|-------------|
| Setup | {{setup_ini}} | {{setup_fim}} | {{resp_setup}} |
| Execução | {{exec_ini}} | {{exec_fim}} | {{resp_exec}} |
| Coleta de dados | {{coleta_ini}} | {{coleta_fim}} | {{resp_coleta}} |
| Análise | {{analise_ini}} | {{analise_fim}} | {{resp_analise}} |
| Decisão | {{decisao_data}} | - | {{resp_decisao}} |

### 8. Decisão Pós-Experimento

**Se sucesso:** {{acao_sucesso}}
**Se fracasso:** {{acao_fracasso}}
**Se inconclusivo:** {{acao_inconclusivo}}

---

## Exemplo Preenchido

### Hipótese
"Acreditamos que enviar um 'desafio do rótulo' por WhatsApp para novos membros nos primeiros
3 dias resultará em aumento de 30% na taxa de engajamento da primeira semana porque as
pessoas agem mais quando recebem um desafio concreto e pessoal."

**Confiança atual:** 6/10
**Se verdade:** Implementamos como parte do onboarding oficial.
**Se falso:** Testamos outro formato de ativação (vídeo curto, quiz).

### Design
**Tipo:** A/B test — grupo com desafio vs. grupo sem desafio.
**Amostra:** 200 novos membros (100 por grupo) ao longo de 10 dias.
**Métrica principal:** % que posta no Discord na primeira semana.
**Sucesso:** >30% de engajamento. **Fracasso:** <10%.

### Timeline
| Etapa | Início | Fim | Resp |
|-------|--------|-----|------|
| Setup | Seg | Ter | Community manager |
| Execução | Qua | +10 dias | CM |
| Análise | +11 | +12 | Estrategista |
| Decisão | +13 | - | Líder |

---

## Dicas

- **Uma hipótese por experimento.** Testar duas coisas ao mesmo tempo invalida ambas.
- **Defina o threshold ANTES de rodar.** Depois dos dados é fácil mover a trave.
- **Documente tudo.** Experimentos fracassados são tão valiosos quanto os bem-sucedidos.
- **Comunique o aprendizado.** Compartilhe resultados com todo o squad, não só com quem rodou.
- **Speed over perfection.** Melhor um teste imperfeito em 5 dias que um perfeito em 5 semanas.
- **Kill your darlings.** Se os dados dizem não, aceite. Ego não é hipótese.
