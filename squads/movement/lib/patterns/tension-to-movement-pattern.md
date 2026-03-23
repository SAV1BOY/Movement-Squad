---
id: tension-to-movement-pattern
name: "Padrão Tensão → Tese → Ação"
squad: movement
type: pattern
category: lib/patterns
version: 1.0.0
tags: [tensão, tese, ação, mobilização, padrão-repetível]
---

# Padrão Tensão → Tese → Ação

## Propósito

Padrão repetível para transformar uma tensão cultural, social ou de mercado em um movimento organizado. É o padrão fundacional — todo movimento começa aqui.

## O Padrão

```
TENSÃO (o que incomoda) → TESE (por que incomoda e o que deveria ser) → AÇÃO (o que faremos a respeito)
```

### Etapa 1: Mapear a Tensão

```yaml
tensão:
  descrição: "" # a frustração em uma frase
  quem_sente: "" # grupo afetado
  intensidade: "" # latente | crescente | em ebulição | crise
  há_quanto_tempo: "" # nova | crônica | ressurgente
  gatilho_recente: "" # evento que amplificou a tensão
  sinais_observáveis:
    - sinal_1: ""
    - sinal_2: ""
    - sinal_3: ""
  conversas_onde_aparece: [] # fóruns, redes, mídia
```

**Teste de tensão real vs. tensão inventada:**
| Critério | Tensão Real | Tensão Inventada |
|----------|-------------|------------------|
| Pessoas falam sobre sem serem perguntadas? | Sim | Não |
| Existe linguagem própria para descrever? | Sim | Não |
| Pessoas já tentaram resolver sozinhas? | Sim | Não |
| A tensão aparece em múltiplos contextos? | Sim | Não |
| Há emoção visível quando o tema surge? | Sim | Não |

### Etapa 2: Formular a Tese

```yaml
tese:
  diagnóstico: "" # por que essa tensão existe
  declaração: "" # o que acreditamos que deveria ser diferente
  inimigo: "" # o sistema/prática que perpetua a tensão
  sonho: "" # o mundo que queremos
  mecanismo: "" # como pretendemos chegar lá
  urgência: "" # por que agora e não depois
  versão_tweet: "" # a tese em 280 caracteres
```

**Critérios de uma boa tese:**
1. **Específica** — não "melhorar o mundo", mas "mudar X para Y"
2. **Provocativa** — deve incomodar pelo menos um grupo
3. **Defensável** — tem evidências que a sustentam
4. **Acionável** — aponta para ação, não apenas diagnóstico
5. **Compartilhável** — cabe em uma frase memorável

### Etapa 3: Desenhar a Ação

```yaml
ação:
  ação_fundadora: "" # o primeiro ato público do movimento
  formato: "" # manifesto | evento | conteúdo | protesto | produto | comunidade
  participação_mínima: "" # quantas pessoas para ser viável
  canal_principal: ""
  data_ou_gatilho: "" # quando lançar
  convite: "" # como as pessoas aderem
  primeira_vitória: "" # marco alcançável em 30 dias
  narrativa_da_ação: "" # a história que contaremos sobre esse momento
```

**Escada de compromisso (usar em sequência):**
```
1. Assinar / Curtir / Compartilhar (1 minuto)
2. Comentar / Testemunhar (5 minutos)
3. Criar conteúdo próprio (30 minutos)
4. Participar de evento (2 horas)
5. Organizar iniciativa local (1 dia)
6. Liderar capítulo (compromisso contínuo)
```

## Exemplo Completo

```yaml
tensão:
  descrição: "Profissionais de saúde mental não conseguem pagar suas contas"
  quem_sente: "Psicólogos recém-formados"
  intensidade: "em ebulição"
  gatilho_recente: "Tabela de honorários defasada há 8 anos"

tese:
  diagnóstico: "O sistema de saúde trata terapia como luxo, não como necessidade"
  declaração: "Saúde mental é infraestrutura, não privilégio"
  inimigo: "O modelo que desvaloriza o trabalho do cuidado"
  versão_tweet: "Se saúde mental é prioridade, por que quem cuida dela não consegue se sustentar?"

ação:
  ação_fundadora: "Publicação simultânea de 100 psicólogos com seus custos reais"
  formato: "conteúdo coordenado + manifesto"
  primeira_vitória: "Cobertura em 3 veículos de mídia em 30 dias"
```

## Armadilhas

1. **Tensão sem tese**: reclamar sem propor = desabafo, não movimento
2. **Tese sem tensão**: propor sem dor real = projeto acadêmico
3. **Ação sem escada**: pedir compromisso alto de estranhos = fracasso
4. **Timing errado**: movimento sem gatilho = indiferença
5. **Tese mutável**: mudar a tese a cada semana = confusão

## Integração

- Tensão mapeada via `signal-taxonomy` e `signal-to-claim-pattern`
- Tese construída com `thesis-component`
- Ação conecta ao `ritual-script-component` e `manifesto-block-component`
- Avaliada pelo `thesis-strength-rubric`
