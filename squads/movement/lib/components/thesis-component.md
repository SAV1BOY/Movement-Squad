---
id: thesis-component
name: "Componente de Tese"
squad: movement
type: component
category: lib/components
version: 1.0.0
tags: [tese, inimigo, sonho, mecanismo, componente-reutilizável]
---

# Componente de Tese

## Propósito

Bloco reutilizável para articular a tese central de um movimento. A tese é o argumento estruturado que conecta o inimigo (o que combatemos), o sonho (o que queremos) e o mecanismo (como chegaremos lá).

## Estrutura do Bloco

### 1. O Inimigo (Contra o quê?)

```yaml
inimigo:
  declaração: "" # frase clara do que combatemos
  tipo: "" # sistema | prática | mentalidade | instituição | narrativa
  evidências:
    - evidência_1: ""
    - evidência_2: ""
    - evidência_3: ""
  quem_sofre: "" # quem é mais prejudicado pelo inimigo
  por_que_persiste: "" # por que o inimigo ainda existe
  custo_da_inação: "" # o que acontece se não agirmos
```

**Regras do inimigo:**
- Deve ser sistêmico, nunca pessoal
- Deve ser reconhecível pelo público em 5 segundos
- Deve provocar indignação legítima
- Deve ser derrotável (não abstrato demais)

### 2. O Sonho (Em direção a quê?)

```yaml
sonho:
  declaração: "" # frase clara do mundo que queremos
  beneficiários_diretos: ""
  beneficiários_indiretos: ""
  indicador_de_sucesso: "" # como saberemos que chegamos lá
  precedentes: [] # exemplos de que é possível
  horizonte: "" # quando isso pode se tornar realidade
```

**Regras do sonho:**
- Deve ser desejável para além do grupo fundador
- Deve ser visualizável — descreva uma cena, não um conceito
- Deve ser grande o suficiente para inspirar, específico o suficiente para medir
- Deve criar tensão produtiva com o presente

### 3. O Mecanismo (Como?)

```yaml
mecanismo:
  declaração: "" # como vamos do inimigo ao sonho
  tipo: "" # educação | organização | produto | legislação | cultura
  etapas:
    - etapa_1:
        ação: ""
        resultado_esperado: ""
        prazo: ""
    - etapa_2:
        ação: ""
        resultado_esperado: ""
        prazo: ""
    - etapa_3:
        ação: ""
        resultado_esperado: ""
        prazo: ""
  recursos_necessários: []
  aliados_estratégicos: []
  riscos_principais: []
```

### 4. A Declaração Unificada

```yaml
declaração_unificada:
  formato: "Combatemos [INIMIGO] porque acreditamos em [SONHO], e faremos isso através de [MECANISMO]."
  versão_curta: "" # máximo 15 palavras
  versão_longa: "" # máximo 50 palavras
  versão_emocional: "" # versão que provoca emoção
```

## Teste de Força da Tese

| Critério | Pontuação (1-5) |
|----------|----------------|
| O inimigo é claro e reconhecível? | |
| O sonho é desejável e visualizável? | |
| O mecanismo é crível e executável? | |
| A tensão entre inimigo e sonho é produtiva? | |
| A declaração cabe em um tweet? | |

**Interpretação:**
- 20-25: Tese forte — pronta para manifesto
- 15-19: Tese promissora — refinar mecanismo
- 10-14: Tese fraca — retrabalhar inimigo ou sonho
- < 10: Tese insuficiente — recomeçar do brief

## Armadilhas Comuns

1. **Inimigo vago demais**: "o sistema" → seja específico
2. **Sonho genérico**: "um mundo melhor" → descreva a cena
3. **Mecanismo mágico**: "vamos mudar a cultura" → defina etapas
4. **Tese sem tensão**: se não incomoda ninguém, não mobiliza
5. **Tese sem urgência**: se pode esperar, vai esperar para sempre

## Integração

- Alimentado pelo `movement-brief-component` (tensão e visão)
- Alimenta o `manifesto-block-component` (contraste e visão)
- Avaliado pelo `thesis-strength-rubric`
- Pode ser arquivado em `archive/deprecated-theses/` quando superado
