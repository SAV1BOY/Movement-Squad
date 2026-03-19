---
id: ugc-to-movement-pattern
name: "Padrão UGC → Movimento"
squad: movement
type: pattern
category: lib/patterns
version: 1.0.0
tags: [ugc, conteúdo-gerado, comunidade, aceleração, padrão-repetível]
---

# Padrão UGC → Movimento

## Propósito

Padrão repetível para transformar conteúdo gerado pela comunidade (UGC) em combustível para o movimento. UGC é a prova viva de que o movimento está funcionando — quando pessoas criam sem que ninguém peça, a identidade coletiva está se fortalecendo. Este padrão captura, amplifica e redireciona essa energia.

## O Padrão

```
DETECTAR (UGC surge) → CURAR (selecionar e contextualizar) → AMPLIFICAR (dar visibilidade) → RITUALIZAR (criar cadência) → RETROALIMENTAR (gerar mais UGC)
```

## Quando Usar

- Quando membros da comunidade começam a criar conteúdo espontaneamente
- Quando há volume suficiente de UGC para curadoria (mínimo 5 peças/semana)
- Quando o movimento precisa de prova social para escalar
- Quando a narrativa precisa de vozes diversas além da equipe editorial
- Quando o custo de produção de conteúdo precisa ser reduzido sem perder qualidade

## Processo

### Etapa 1: Detectar

```yaml
detecção:
  fontes_monitoradas:
    - plataforma: "" # onde buscar UGC
      palavras_chave: [] # termos, hashtags, menções
      frequência: "" # diária | contínua
  critérios_de_relevância:
    - alinhado_com_tese: true # o UGC reforça a tese do movimento?
    - qualidade_mínima: "" # legível, original, autêntico
    - potencial_de_amplificação: "" # alto | médio | baixo
  responsável: "" # quem monitora
  ferramenta: "" # ferramenta de social listening ou monitoramento manual
```

**O que buscar:**
- Posts que usam a linguagem do movimento sem serem instruídos
- Relatos de experiência pessoal conectados à tese
- Criações visuais (memes, artes, fotos) com símbolos do movimento
- Depoimentos espontâneos de transformação
- Críticas construtivas que revelam engajamento profundo

### Etapa 2: Curar

```yaml
curadoria:
  peça_selecionada:
    autor: ""
    plataforma_original: ""
    link: ""
    tipo: "" # texto | imagem | vídeo | áudio | meme | depoimento
    resumo: ""
  contexto_adicionado: "" # por que essa peça é relevante para o movimento
  permissão:
    solicitada: false
    concedida: false
    formato_permissão: "" # DM | email | comentário público
  edição: "" # nenhuma | leve (gramática) | moderada (formatação)
```

**Regras de curadoria:**
- Sempre pedir permissão antes de repostar ou republicar
- Nunca editar o conteúdo sem autorização do autor
- Dar crédito explícito e visível
- Selecionar diversidade de vozes — não sempre os mesmos criadores
- Priorizar autenticidade sobre polimento

### Etapa 3: Amplificar

```yaml
amplificação:
  canal: "" # onde o UGC será republicado/amplificado
  formato: "" # repost | destaque em newsletter | story | compilação
  contexto_editorial: "" # introdução ou enquadramento do time
  call_to_action: "" # o que pedimos que outros façam ao ver isso
  investimento: "" # orgânico | boost pago | ambos
  métricas_esperadas:
    alcance: ""
    engajamento: ""
    novos_UGC_gerados: ""
```

**Estratégias de amplificação:**
| Estratégia | Quando Usar | Exemplo |
|-----------|------------|---------|
| Repost com comentário | UGC de alta qualidade individual | RT + "Isso é exatamente o que acreditamos" |
| Compilação semanal | Volume alto de UGC | "Top 5 contribuições da comunidade esta semana" |
| Destaque em newsletter | UGC com profundidade narrativa | Feature story de um membro |
| Wall of fame | UGC visual/criativo | Galeria de melhores criações da comunidade |
| Co-criação | UGC de criadores recorrentes | Convidar para criar conteúdo oficial junto |

### Etapa 4: Ritualizar

```yaml
ritual:
  nome: "" # nome do ritual de UGC (ex: "Terça da Comunidade")
  cadência: "" # semanal | quinzenal | mensal
  formato: "" # como o ritual funciona
  regras: [] # regras claras de participação
  recompensa: "" # reconhecimento, destaque, acesso, etc.
  responsável: ""
```

**Exemplos de rituais de UGC:**
- **Show & Tell semanal**: membros compartilham o que criaram durante a semana
- **Desafio mensal**: tema proposto, comunidade cria, melhores são destacados
- **Membro do mês**: destaque ao criador mais ativo ou impactante
- **Remix permitido**: comunidade pega artefato oficial e cria variações

### Etapa 5: Retroalimentar

```yaml
retroalimentação:
  sinal_detectado: "" # o que o UGC revela sobre o estado do movimento
  tema_emergente: "" # tema recorrente no UGC que não planejamos
  insight_para_tese: "" # como o UGC valida, refina ou desafia a tese
  ação_derivada: "" # o que vamos fazer com esse aprendizado
  novo_ciclo: "" # como isso gera mais UGC
```

**O ciclo virtuoso:**
- UGC de qualidade → amplificação → mais pessoas veem → mais pessoas criam → mais UGC
- UGC revela tensões e desejos → refina tese → artefatos mais relevantes → mais UGC

## Armadilhas

1. **Exploração sem reciprocidade**: usar UGC sem dar crédito ou retornar valor
2. **Curadoria enviesada**: só amplificar vozes que concordam — incluir diversidade
3. **Excesso de controle**: querer editar ou "melhorar" o UGC — a autenticidade é o valor
4. **Ritual sem energia**: criar ritual que ninguém quer participar — testar antes de oficializar
5. **Ignorar permissões**: repostar sem pedir — risco legal e de confiança

## Exemplo

**Contexto:** Movimento de produtividade consciente para devs.

**Detectar:** Membro do Discord posta foto de seu setup com post-it "Foco de 90 min, pausa de 20" e legenda "3 semanas seguindo o método e nunca produzi tanto sem estresse".

**Curar:** Community architect pede permissão via DM, membro autoriza. Foto selecionada pela autenticidade e resultado relatado.

**Amplificar:** Repost no LinkedIn com comentário do time: "Quando a comunidade mostra que funciona, não precisamos convencer ninguém." Alcance: 12K, 340 engajamentos.

**Ritualizar:** Nasce o "Setup de Sexta" — toda sexta, membros postam seus setups de foco. 15-20 contribuições por semana após 4 semanas.

**Retroalimentar:** Sinal detectado — membros pedindo versão para times, não só individual. Alimenta novo experimento de ritual de foco coletivo.

## Integração

- Sinais de UGC classificados pela `signal-taxonomy` (tipo: comportamento/código)
- Amplificação via `distribution-trident`
- Rituais conectados ao `ritual-reward-loop`
- Métricas de UGC alimentam o `movement-health-score-framework`
- Insights retroalimentam o `signal-to-claim-pattern`
