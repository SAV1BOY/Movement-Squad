---
id: proof-component
name: "Componente de Prova"
squad: movement
type: component
category: lib/components
version: 1.0.0
tags: [prova, dados, narrativa, evidência, componente-reutilizável]
---

# Componente de Prova

## Propósito

Bloco reutilizável para construir provas que sustentam a tese do movimento. Cada prova combina dados quantitativos, narrativa qualitativa e evidência observável para criar convicção.

## Estrutura do Bloco

### 1. Dados (O Número)

```yaml
dados:
  estatística_principal: "" # o número mais impactante
  fonte: "" # fonte verificável
  data_de_coleta: ""
  contexto: "" # por que esse número importa
  tendência: "" # crescendo | estável | caindo
  comparativo: "" # comparação que amplifica o impacto
  visualização_sugerida: "" # gráfico | infográfico | mapa
```

**Regras dos dados:**
- Sempre cite a fonte primária
- Prefira dados recentes (< 2 anos)
- Use comparativos para dar escala ("isso equivale a...")
- Um número forte vale mais que dez fracos

### 2. Narrativa (A História)

```yaml
narrativa:
  protagonista: "" # pessoa real afetada
  situação_antes: "" # como era a vida antes
  momento_de_virada: "" # o que mudou
  situação_depois: "" # como ficou depois
  citação_direta: "" # fala do protagonista
  emoção_dominante: "" # raiva | esperança | orgulho | alívio
  formato: "" # texto | vídeo | áudio | imagem
```

**Regras da narrativa:**
- Use pessoas reais, nunca personas fictícias
- A história deve ser verificável
- Priorize vozes de quem é mais afetado
- Brevidade — a história inteira em menos de 200 palavras

### 3. Evidência (O Observável)

```yaml
evidência:
  tipo: "" # comportamento | tendência | evento | artefato | declaração
  descrição: "" # o que é observável
  onde_encontrar: "" # onde qualquer pessoa pode verificar
  recorrência: "" # evento único | padrão recorrente
  conexão_com_tese: "" # como isso prova a tese
```

**Tipos de evidência por força:**
| Tipo | Força | Exemplo |
|------|-------|---------|
| Experimento controlado | ★★★★★ | Estudo acadêmico publicado |
| Dados longitudinais | ★★★★☆ | Pesquisa anual repetida |
| Estudo de caso | ★★★☆☆ | Documentação de uma transformação |
| Pesquisa de opinião | ★★☆☆☆ | Survey com amostra significativa |
| Anedota verificável | ★☆☆☆☆ | Depoimento individual |

### 4. Síntese da Prova

```yaml
síntese:
  afirmação: "" # o que os dados + narrativa + evidência provam juntos
  nível_de_confiança: "" # alto | médio | baixo
  contra_argumento_principal: "" # a melhor objeção a essa prova
  resposta_ao_contra_argumento: ""
  próxima_prova_necessária: "" # o que fortaleceria essa prova
```

## Regras de Composição

1. **Sempre combine os três elementos** — dados sozinhos não emocionam, histórias sozinhas não convencem
2. **Lide a prova com o elemento mais forte** — se os dados são impressionantes, comece por eles
3. **Antecipe o contra-argumento** — endereçar objeções fortalece a prova
4. **Atualize provas regularmente** — dados desatualizados minam credibilidade
5. **Máximo 3 provas por tese** — mais do que isso dilui o impacto

## Checklist de Qualidade

- [ ] Os dados são de fonte verificável e recente?
- [ ] A narrativa é de uma pessoa real e autorizada?
- [ ] A evidência pode ser observada por qualquer pessoa?
- [ ] Os três elementos se reforçam mutuamente?
- [ ] O contra-argumento foi endereçado?

## Integração

- Alimentado pelo `thesis-component` (o que precisa ser provado)
- Usado no `manifesto-block-component` (bloco de contraste)
- Alimenta o padrão `signal-to-claim-pattern`
- Avaliado pelo `thesis-strength-rubric`
