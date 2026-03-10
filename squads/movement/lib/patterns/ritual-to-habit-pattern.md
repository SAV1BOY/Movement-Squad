---
id: ritual-to-habit-pattern
name: "Padrão Ritual → Hábito → Identidade"
squad: movement
type: pattern
category: lib/patterns
version: 1.0.0
tags: [ritual, hábito, identidade, retenção, padrão-repetível]
---

# Padrão Ritual → Hábito → Identidade

## Propósito

Padrão repetível para transformar rituais pontuais em hábitos recorrentes que eventualmente se tornam parte da identidade do membro. É o mecanismo de retenção mais poderoso de um movimento.

## O Padrão

```
RITUAL (experiência projetada) → HÁBITO (comportamento automático) → IDENTIDADE (eu sou isso)
```

### Etapa 1: Projetar o Ritual

```yaml
ritual:
  nome: ""
  gatilho: "" # o que inicia o comportamento
  ação: "" # o que a pessoa faz
  recompensa: "" # o que a pessoa ganha imediatamente
  investimento: "" # o que a pessoa deposita (tempo, dados, conteúdo)
  frequência_ideal: "" # diário | semanal | mensal
  tempo_necessário: "" # < 5 min para rituais diários
  visibilidade_social: "" # outros membros veem a participação?
```

**O loop do ritual:**
```
Gatilho → Ação → Recompensa → Investimento → (loop)
                                    ↓
                            Aumenta custo de saída
```

### Etapa 2: Facilitar a Transição para Hábito

```yaml
hábito:
  repetições_até_hábito: "" # geralmente 21-66 dias
  lembretes:
    - tipo: "" # push | email | social | ambiental
      momento: "" # quando o lembrete chega
      mensagem: "" # tom motivacional, não coercivo
  redução_de_fricção:
    - barreira_1: ""
      solução: ""
    - barreira_2: ""
      solução: ""
  progressão:
    semana_1: "" # versão simplificada do ritual
    semana_2_4: "" # versão completa
    mês_2_3: "" # versão expandida
    mês_4_plus: "" # versão autônoma
  accountability:
    tipo: "" # parceiro | grupo | público | automonitoramento
    mecanismo: ""
```

**Indicadores de que o ritual virou hábito:**
- A pessoa faz sem ser lembrada
- A pessoa sente falta quando não faz
- A pessoa adapta sua rotina para encaixar o ritual
- A pessoa convida outros a participar

### Etapa 3: Consolidar como Identidade

```yaml
identidade:
  declaração_de_identidade: "" # "eu sou alguém que..."
  comportamentos_derivados: [] # outros comportamentos que surgem
  resistência_a_abandono: "" # por que é difícil parar
  evangelização_natural: "" # como a pessoa espalha
  marcadores_visíveis: [] # como outros reconhecem
```

**A escada de identidade:**
```
"Eu fiz isso" (ação pontual)
    ↓
"Eu faço isso" (hábito)
    ↓
"Eu sou isso" (identidade)
    ↓
"Nós somos isso" (identidade coletiva)
```

## Mecanismos de Reforço

| Mecanismo | Como Funciona | Exemplo |
|-----------|--------------|---------|
| Streak | Contagem de dias consecutivos | "47 dias de contribuição" |
| Artefato | Objeto que acumula significado | Badge, camiseta, sticker |
| Status | Posição visível no grupo | Ranking, título, cor |
| Narrativa | História pessoal de transformação | "Antes eu era X, agora sou Y" |
| Comunidade | Pertencimento a grupo exclusivo | Canal só para quem completou |

## Exemplo Completo

```yaml
ritual:
  nome: "Build Log Diário"
  gatilho: "Notificação às 18h: 'O que você construiu hoje?'"
  ação: "Postar 1-3 frases sobre o que fez no dia"
  recompensa: "Reações da comunidade em < 5 minutos"
  investimento: "Histórico de build logs acumulado"
  frequência_ideal: "diário"
  tempo_necessário: "2 minutos"

hábito:
  repetições_até_hábito: "30 dias"
  progressão:
    semana_1: "Apenas 1 frase, emoji de 🔨 basta"
    mês_2_3: "Frases + aprendizados + próximos passos"

identidade:
  declaração: "Eu sou um Builder — eu construo todo dia"
  evangelização: "Builders convidam amigos: 'vem buildar comigo'"
```

## Armadilhas

1. **Ritual complexo demais**: se leva mais de 5 min/dia, não vira hábito
2. **Recompensa atrasada**: precisa ser imediata no início
3. **Sem progressão**: mesmo ritual para sempre = tédio
4. **Coerção**: lembrete virar cobrança mata motivação intrínseca
5. **Identidade forçada**: identidade deve emergir, não ser imposta

## Integração

- Rituais projetados com `ritual-script-component`
- Identidade conecta ao `identity-code-component`
- Progressão via `community-role-component`
- Métricas alimentam `community-health-rubric`
