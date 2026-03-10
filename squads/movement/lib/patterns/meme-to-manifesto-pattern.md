---
id: meme-to-manifesto-pattern
name: "Padrão Meme → Manifesto (Escala de Profundidade)"
squad: movement
type: pattern
category: lib/patterns
version: 1.0.0
tags: [meme, manifesto, profundidade, viralidade, padrão-repetível]
---

# Padrão Meme → Manifesto (Escala de Profundidade)

## Propósito

Padrão repetível para escalar a profundidade da mensagem do movimento, desde um meme viral (superficial, alto alcance) até um manifesto completo (profundo, alto compromisso). Cada nível atrai e converte para o próximo.

## O Padrão

```
MEME (captura) → SLOGAN (memoriza) → ARGUMENTO (convence) → MANIFESTO (converte)
```

### Nível 1: Meme (Captura de Atenção)

```yaml
meme:
  formato: "" # imagem + texto | vídeo curto | tweet | sticker
  mensagem: "" # uma ideia em < 10 palavras
  emoção: "" # humor | indignação | pertencimento | surpresa
  tempo_de_consumo: "< 3 segundos"
  ação_esperada: "compartilhar"
  métricas: ["compartilhamentos", "impressões", "saves"]
  vida_útil: "1-7 dias"
```

**Características do bom meme de movimento:**
- Entendido sem contexto prévio
- Provoca reação emocional instantânea
- Fácil de replicar e adaptar
- Carrega a tensão central do movimento
- Não precisa de explicação

### Nível 2: Slogan (Memorização)

```yaml
slogan:
  formato: "" # frase | hashtag | grito | pergunta retórica
  mensagem: "" # a tese em uma frase (< 15 palavras)
  repetibilidade: "" # fácil de falar em voz alta?
  tempo_de_consumo: "< 10 segundos"
  ação_esperada: "repetir e adotar"
  métricas: ["uso espontâneo", "menções", "adoção"]
  vida_útil: "meses a anos"
```

**Fórmulas de slogan:**
| Fórmula | Exemplo |
|---------|---------|
| Imperativo | "Think Different" |
| Declaração | "Black Lives Matter" |
| Pergunta | "Got Milk?" |
| Contraste | "Real Beauty, Not Photoshop" |
| Identidade | "We Are the 99%" |

### Nível 3: Argumento (Convencimento)

```yaml
argumento:
  formato: "" # thread | artigo curto | vídeo de 2-5 min | carrossel
  mensagem: "" # tese + evidência + implicação
  estrutura: "" # problema-solução | mito-verdade | antes-depois
  tempo_de_consumo: "2-5 minutos"
  ação_esperada: "concordar e engajar"
  métricas: ["tempo de leitura", "comentários", "saves", "bookmarks"]
  vida_útil: "semanas a meses"
```

### Nível 4: Manifesto (Conversão)

```yaml
manifesto:
  formato: "" # texto longo | vídeo longo | site dedicado | documento
  mensagem: "" # tese completa + visão + chamada à ação
  estrutura: "" # abertura + contraste + visão + CTA
  tempo_de_consumo: "5-15 minutos"
  ação_esperada: "aderir ao movimento"
  métricas: ["leitura completa", "assinaturas", "ações tomadas"]
  vida_útil: "anos"
```

## Funil de Profundidade

```
         MEME          ← 1.000.000 alcançados
        /    \
     SLOGAN            ←   100.000 memorizam
      /    \
  ARGUMENTO            ←    10.000 se convencem
     /    \
 MANIFESTO             ←     1.000 aderem
```

**Taxa de conversão esperada entre níveis:** ~10% em cada transição

## Estratégia de Transição Entre Níveis

| De → Para | Mecanismo | Exemplo |
|-----------|-----------|---------|
| Meme → Slogan | Repetição do meme com frase fixa | Meme vira template com hashtag |
| Slogan → Argumento | Link no perfil / thread explicativa | "Quer saber por quê? Link na bio" |
| Argumento → Manifesto | CTA no final do argumento | "Leia o manifesto completo" |

## Regras do Padrão

1. **Cada nível deve funcionar sozinho** — quem só vê o meme deve ser impactado
2. **A transição deve ser convidativa**, não obrigatória
3. **O tom muda com a profundidade** — meme é leve, manifesto é sério
4. **Memes devem ser criados pela comunidade**, não só pela liderança
5. **O manifesto deve ser revisado** quando os memes evoluem organicamente

## Integração

- Memes classificados pela `artifact-taxonomy`
- Manifesto construído com `manifesto-block-component`
- Espalhamento medido pelo `memetic-spread-rubric`
- Argumento usa `proof-component` e `signal-to-claim-pattern`
