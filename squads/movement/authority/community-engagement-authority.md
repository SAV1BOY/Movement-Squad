---
id: community-engagement-authority
name: "Autoridade via Engajamento de Comunidade"
squad: movement
type: authority
category: authority
version: 1.0.0
tags: [autoridade, comunidade, engajamento, presença, estratégia]
---

# Autoridade via Engajamento de Comunidade

## Propósito

Framework para construir autoridade não por publicações de cima para baixo, mas por engajamento genuíno e consistente com comunidades relevantes.

## O Princípio

A autoridade mais durável não vem de se declarar expert — vem de ser reconhecido como tal pelas comunidades que servimos. Engajamento comunitário constrói autoridade bottom-up.

## Estratégias de Engajamento

### 1. Presença Consistente em Comunidades Existentes

```yaml
presença:
  comunidades_alvo:
    - nome: ""
      plataforma: "" # Discord, Reddit, Slack, WhatsApp
      papel_inicial: "" # observador | contribuidor | facilitador
      frequência: "" # diário | 3x semana | semanal
      tipo_de_contribuição: "" # respostas | insights | recursos | conexões
```

**Progressão de presença:**
1. **Observar (2 semanas):** Entender cultura, linguagem, normas
2. **Contribuir (4 semanas):** Responder perguntas, compartilhar recursos
3. **Agregar (8 semanas):** Trazer insights únicos, fazer conexões
4. **Liderar (12+ semanas):** Propor iniciativas, facilitar conversas

**Regra de ouro:** Dê valor por 3 meses antes de pedir qualquer coisa.

### 2. Curadoria e Compartilhamento

```yaml
curadoria:
  fontes: [] # de onde você coleta informação relevante
  frequência: "" # diário ou semanal
  formato: "" # newsletter | thread | post | resumo
  valor_adicionado: "" # análise, contexto, implicações — não apenas links
```

**Níveis de curadoria:**
| Nível | Ação | Valor |
|-------|------|-------|
| Repost | Compartilhar link | Baixo |
| Resumo | Sintetizar conteúdo | Médio |
| Análise | Adicionar interpretação | Alto |
| Conexão | Ligar a outros temas/eventos | Muito alto |
| Original | Criar a partir de múltiplas fontes | Máximo |

### 3. Facilitação de Conversas

```yaml
facilitação:
  formato: "" # AMA | roundtable | debate | brainstorm | retrospectiva
  frequência: "" # mensal | quinzenal
  plataforma: "" # Discord | Zoom | Twitter Spaces | presencial
  público: "" # membros da comunidade | aberto
  duração: "" # 30-90 minutos
  registro: "" # gravação | notas | thread resumo
```

**Tipos de evento comunitário:**
| Tipo | Descrição | Tamanho Ideal |
|------|-----------|--------------|
| AMA (Ask Me Anything) | Perguntas abertas a um expert | 20-100 |
| Roundtable | Discussão facilitada sobre tema | 6-15 |
| Show & Tell | Membros apresentam projetos | 10-30 |
| Mastermind | Grupo pequeno resolve problemas juntos | 4-8 |
| Office Hours | Sessão aberta de mentoria | 5-20 |

### 4. Mentoria e Suporte Individual

```yaml
mentoria:
  disponibilidade: "" # horas por semana
  formato: "" # 1:1 | grupo | assíncrono
  público: "" # quem você mentora
  foco: "" # tema específico
  duração: "" # sessão única | programa de X semanas
  visibilidade: "" # pública | privada
```

**Por que funciona:** Cada pessoa mentorada se torna um embaixador natural. Mentoria 1:1 cria lealdade que nenhum conteúdo broadcast consegue.

## Métricas de Engajamento como Autoridade

| Métrica | O que Indica | Como Medir |
|---------|-------------|-----------|
| Menções espontâneas | Pessoas citam você sem serem perguntadas | Monitoramento |
| Perguntas direcionadas | Pessoas procuram você especificamente | Contagem |
| Convites para colaborar | Outros querem criar junto | Contagem |
| Referências de pares | Outros experts indicam você | Monitoramento |
| Retenção de mentorando | Pessoas voltam | Taxa de retorno |

## Armadilhas

1. **Transacional demais:** Contribuir apenas esperando retorno mata confiança
2. **Superficial:** Curtir posts sem adicionar valor não constrói nada
3. **Inconsistente:** Aparecer 2 semanas e sumir 2 meses destrói credibilidade
4. **Auto-promocional:** Cada interação sobre você afasta as pessoas
5. **Ignorar hierarquia social:** Entrar como líder em comunidade alheia é invasivo

## Regras de Engajamento Ético

1. **Declare afiliações** — transparência sobre quem você é e representa
2. **Dê crédito** — cite fontes e reconheça quem inspira
3. **Respeite o espaço** — você é convidado, não dono
4. **Não extraia** — não use comunidade alheia como funil de vendas
5. **Reciprocidade** — dê mais do que pede, sempre

## Integração

- Presença em comunidades informa `signal-taxonomy` (captura de sinais)
- Facilitação usa `ritual-script-component`
- Mentoria conecta ao `community-champion-pattern`
- Complementa `thought-leadership-strategy`
- Métricas alimentam `community-health-rubric`
