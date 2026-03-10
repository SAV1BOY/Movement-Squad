---
id: identity-code-component
name: "Componente de Código de Identidade"
squad: movement
type: component
category: lib/components
version: 1.0.0
tags: [identidade, código, linguagem, cultura, componente-reutilizável]
---

# Componente de Código de Identidade

## Propósito

Bloco reutilizável para definir os elementos de identidade que tornam um movimento reconhecível, pertencente e distinto. O código de identidade é o DNA cultural do movimento.

## Estrutura do Bloco

### 1. Linguagem Própria

```yaml
linguagem:
  termo_central: "" # palavra ou frase que define o grupo
  gírias_internas: [] # termos que só membros entendem
  saudação: "" # como membros se cumprimentam
  despedida: "" # como membros se despedem
  grito_de_guerra: "" # frase de mobilização
  hashtags_oficiais: []
  palavras_proibidas: [] # termos que o movimento rejeita
```

### 2. Símbolos Visuais

```yaml
símbolos:
  ícone_principal: "" # descrição do símbolo central
  cores_do_movimento: []
  gesto_ou_pose: "" # gesto físico identificador
  objeto_totêmico: "" # objeto que membros carregam/usam
  estética_visual: "" # estilo visual geral
```

### 3. Crenças Compartilhadas

```yaml
crenças:
  crença_fundadora: "" # a verdade que nos une
  valores_inegociáveis:
    - valor_1: ""
    - valor_2: ""
    - valor_3: ""
  mitos_de_origem: "" # a história que contamos sobre nosso início
  herói_arquetípico: "" # quem admiramos
  vilão_arquetípico: "" # o que combatemos
```

### 4. Comportamentos Marcadores

```yaml
comportamentos:
  ritual_diário: "" # o que membros fazem todo dia
  ritual_semanal: "" # o que membros fazem toda semana
  teste_de_pertencimento: "" # como sabemos quem é "dos nossos"
  sacrifício_esperado: "" # o que membros abrem mão
  recompensa_social: "" # o que membros ganham por pertencer
```

### 5. Fronteiras do Grupo

```yaml
fronteiras:
  quem_somos: "" # definição positiva
  quem_não_somos: "" # definição por contraste
  como_entrar: "" # ritual de entrada
  como_subir: "" # progressão de status
  como_sair: "" # o que acontece quando alguém sai
```

## Regras de Uso

1. **Linguagem deve ser natural**, nunca forçada — se precisa explicar, não funciona
2. **Símbolos devem ser replicáveis** — qualquer membro pode reproduzir
3. **Crenças devem ser sentidas**, não apenas declaradas
4. **Comportamentos devem ser observáveis** no dia a dia
5. **Fronteiras devem ser claras** mas não excludentes de forma tóxica

## Teste de Qualidade

| Critério | Sim/Não |
|----------|---------|
| Um membro reconhece outro em 30 segundos? | |
| A linguagem surge naturalmente em conversas? | |
| Os símbolos são compartilhados com orgulho? | |
| As crenças motivam ação, não apenas concordância? | |
| Os comportamentos criam hábito, não obrigação? | |

## Exemplo Parcial

```yaml
linguagem:
  termo_central: "Construtores" (não "usuários")
  gírias_internas: ["shipar", "iterar", "buildar em público"]
  saudação: "Bora construir?"
  grito_de_guerra: "Ship or die"
```

## Integração

- Alimentado pelo `movement-brief-component` (público e tensão)
- Alimenta o `ritual-script-component` com comportamentos
- Conecta ao `manifesto-block-component` para tom e voz
