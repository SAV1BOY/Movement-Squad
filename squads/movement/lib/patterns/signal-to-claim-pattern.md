---
id: signal-to-claim-pattern
name: "Padrão Sinal → Afirmação → Prova"
squad: movement
type: pattern
category: lib/patterns
version: 1.0.0
tags: [sinal, afirmação, prova, argumentação, padrão-repetível]
---

# Padrão Sinal → Afirmação → Prova

## Propósito

Padrão repetível para transformar sinais fracos do mercado/cultura em afirmações defensáveis sustentadas por provas. É o motor argumentativo de qualquer movimento.

## O Padrão

```
SINAL (observação) → AFIRMAÇÃO (interpretação) → PROVA (evidência)
```

### Etapa 1: Capturar o Sinal

```yaml
sinal:
  o_que_observamos: "" # fato bruto, sem interpretação
  onde_observamos: "" # fonte específica
  quando: ""
  frequência: "" # único | recorrente | crescente
  tipo: "" # linguagem | comportamento | fricção | desejo | código | ausência
  força: "" # fraco | moderado | forte
```

**Fontes de sinais:**
- Conversas em comunidades (Reddit, Discord, Twitter)
- Reclamações recorrentes em reviews e SAC
- Mudanças de linguagem em um grupo
- Comportamentos improvisados de usuários (hacks, workarounds)
- Ausências notáveis (o que ninguém fala mas todos sentem)
- Dados de busca e tendências

### Etapa 2: Formular a Afirmação

```yaml
afirmação:
  declaração: "" # o que esse sinal significa
  tipo: "" # descritiva | causal | preditiva | prescritiva
  público_alvo: "" # para quem essa afirmação importa
  implicação: "" # se isso é verdade, então...
  ousadia: "" # conservadora | moderada | provocativa
```

**Escala de afirmações:**
| Tipo | Exemplo | Risco |
|------|---------|-------|
| Descritiva | "X está acontecendo" | Baixo |
| Causal | "X está acontecendo por causa de Y" | Médio |
| Preditiva | "X vai levar a Y" | Alto |
| Prescritiva | "Devemos fazer Y por causa de X" | Muito alto |

### Etapa 3: Construir a Prova

```yaml
prova:
  dados: "" # número ou estatística que sustenta
  narrativa: "" # história que ilustra
  evidência: "" # fato observável que confirma
  contra_argumento: "" # melhor objeção e resposta
  nível_de_confiança: "" # alto | médio | baixo
```

## Exemplo Completo

```yaml
sinal:
  o_que_observamos: "Devs juniores criando accounts anônimas para fazer perguntas básicas"
  onde_observamos: "Reddit r/learnprogramming, Discord de bootcamps"
  frequência: "crescente"
  tipo: "comportamento"

afirmação:
  declaração: "A cultura tech pune a vulnerabilidade e isso está afastando talentos"
  tipo: "causal"
  implicação: "Se não criarmos espaços seguros, perderemos uma geração de devs"
  ousadia: "provocativa"

prova:
  dados: "67% dos devs juniores relatam medo de fazer perguntas (Stack Overflow Survey 2025)"
  narrativa: "Ana, bootcamp grad, criou 3 contas anônimas antes de postar sua primeira dúvida"
  evidência: "Comunidades 'no stupid questions' cresceram 340% em 2 anos"
```

## Regras do Padrão

1. **Sinais primeiro, afirmações depois** — nunca comece com a conclusão
2. **Um sinal não faz verão** — mínimo 3 sinais convergentes para uma afirmação
3. **Afirmações devem ser falsificáveis** — se não pode ser provada errada, não é útil
4. **Provas devem ser atualizáveis** — dados com data de validade
5. **Escale a ousadia gradualmente** — comece descritivo, avance para prescritivo

## Checklist

- [ ] O sinal é um fato observável, não uma opinião?
- [ ] A afirmação vai além da observação óbvia?
- [ ] A prova combina dados + narrativa + evidência?
- [ ] O contra-argumento foi considerado?
- [ ] A afirmação seria compartilhável em uma frase?

## Integração

- Sinais classificados pela `signal-taxonomy`
- Provas construídas com `proof-component`
- Afirmações alimentam o `thesis-component`
- Avaliado pelo `thesis-strength-rubric`
