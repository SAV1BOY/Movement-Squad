---
id: enemy-to-hero-pattern
name: "Padrão Inimigo → Herói → Ação"
squad: movement
type: pattern
category: lib/patterns
version: 1.0.0
tags: [inimigo, herói, ação, narrativa, padrão-repetível]
---

# Padrão Inimigo → Herói → Ação

## Propósito

Padrão repetível para construir narrativas de movimento que mobilizam através da estrutura clássica: identificar o inimigo, posicionar o herói e definir a ação transformadora.

## O Padrão

```
INIMIGO (o que combatemos) → HERÓI (quem somos juntos) → AÇÃO (o que fazemos)
```

### Etapa 1: Nomear o Inimigo

```yaml
inimigo:
  nome: "" # rótulo claro e memorável
  tipo: "" # sistema | prática | mentalidade | narrativa | instituição
  manifestações:
    - como_aparece_1: ""
    - como_aparece_2: ""
    - como_aparece_3: ""
  quem_protege: "" # quem se beneficia do status quo
  por_que_persiste: "" # mecanismo de perpetuação
  frase_do_inimigo: "" # o que o inimigo diria se pudesse falar
```

**Tipos de inimigo eficazes:**
| Tipo | Exemplo | Risco |
|------|---------|-------|
| Sistema | "A burocracia que mata inovação" | Baixo — difícil personalizar |
| Prática | "O feedback sanduíche que mente" | Baixo — específico e reconhecível |
| Mentalidade | "A crença de que arte não paga" | Médio — pode alienar quem pensa assim |
| Narrativa | "O mito da meritocracia pura" | Alto — desafia crenças profundas |
| Instituição | "O modelo educacional do séc. XIX" | Alto — muitos defensores |

### Etapa 2: Posicionar o Herói

```yaml
herói:
  identidade: "" # quem é o herói (sempre coletivo)
  qualidade_definidora: "" # o que nos diferencia
  vulnerabilidade: "" # o que nos torna humanos
  transformação: "" # o que nos tornamos ao agir
  grito: "" # a frase que nos define
  diferencial: "" # por que nós e não outros
```

**Regras do herói:**
- O herói é sempre coletivo ("nós"), nunca individual
- O herói tem vulnerabilidade — perfeição não mobiliza
- O herói é definido pela ação, não pelo status
- O herói existe em contraste com o inimigo

### Etapa 3: Definir a Ação

```yaml
ação:
  ação_imediata: "" # o que qualquer pessoa pode fazer agora (< 2 min)
  ação_de_compromisso: "" # o que membros fazem regularmente
  ação_heroica: "" # o ato que define os verdadeiros campeões
  mecanismo_de_escala: "" # como a ação se multiplica
  evidência_de_impacto: "" # como sabemos que está funcionando
```

**Escada de ação:**
```
Nível 1: Reconhecer (curtir, compartilhar, assinar)
Nível 2: Participar (comentar, comparecer, usar)
Nível 3: Contribuir (criar, ensinar, organizar)
Nível 4: Liderar (recrutar, mobilizar, representar)
Nível 5: Sacrificar (arriscar, investir, transformar)
```

## Exemplo Completo

```yaml
inimigo:
  nome: "A cultura do burnout glorificado"
  tipo: "mentalidade"
  manifestações:
    - "Posts celebrando trabalhar 80h/semana"
    - "Cultura de 'hustle' como virtude"
    - "Demissão de quem pede equilíbrio"
  frase_do_inimigo: "Se você ama o que faz, não é trabalho"

herói:
  identidade: "Profissionais que entregam resultado com saúde"
  qualidade_definidora: "Coragem de estabelecer limites"
  vulnerabilidade: "Medo de ser visto como preguiçoso"
  grito: "Resultados, não horas"

ação:
  ação_imediata: "Poste seu horário de saída com a hashtag #ResultadosNãoHoras"
  ação_de_compromisso: "Não responda emails depois das 19h por 30 dias"
  ação_heroica: "Implemente política de desconexão na sua empresa"
```

## Armadilhas

1. **Inimigo pessoal**: atacar CEOs específicos vira bullying, não movimento
2. **Herói perfeito**: sem vulnerabilidade, ninguém se identifica
3. **Ação impossível**: se a primeira ação é "mude o sistema", ninguém começa
4. **Vitimismo**: o herói age, não reclama
5. **Maniqueísmo**: o mundo não é preto e branco — nuance fortalece

## Integração

- Inimigo alimentado pelo `thesis-component`
- Herói definido pelo `identity-code-component`
- Ação conecta ao `ritual-script-component`
- Narrativa usada no `manifesto-block-component`
