---
id: experiment-component
name: "Componente de Experimento"
squad: movement
type: component
category: lib/components
version: 1.0.0
tags: [experimento, hipótese, teste, validação, componente-reutilizável]
---

# Componente de Experimento

## Propósito

Bloco reutilizável para design e documentação de experimentos dentro do movimento. Cada experimento testa uma hipótese específica com método claro, métricas definidas e critérios objetivos de sucesso ou fracasso. Sem experimentos, decisões viram opiniões.

## Estrutura do Bloco

### 1. Hipótese (O que acreditamos?)

```yaml
hipótese:
  declaração: "" # frase clara do que acreditamos que vai acontecer
  formato: "Se [AÇÃO], então [RESULTADO], porque [RAZÃO]"
  variável_independente: "" # o que vamos mudar
  variável_dependente: "" # o que esperamos que mude como consequência
  premissa: "" # crença subjacente que estamos testando
  falsificável: true # se não pode ser provada errada, não é hipótese
```

**Regras da hipótese:**
- Deve ser específica e falsificável
- Deve ser testável no prazo e com os recursos disponíveis
- Deve estar conectada a uma decisão real (se validada, fazemos X; se invalidada, fazemos Y)
- Deve ser escrita antes de ver os resultados (nunca retroativa)

### 2. Método (Como vamos testar?)

```yaml
método:
  tipo: "" # A/B test | antes/depois | cohort | piloto | survey | etnográfico
  grupo_teste: "" # quem ou o que será exposto à mudança
  grupo_controle: "" # quem ou o que serve de comparação
  tamanho_amostra: "" # quantas observações mínimas para significância
  variáveis_controladas: [] # o que mantemos constante
  vieses_conhecidos: [] # vieses que podem afetar o resultado
  mitigação_de_viés: "" # como minimizamos os vieses
```

**Tipos de método por contexto:**

| Tipo | Quando Usar | Exemplo |
|------|------------|---------|
| A/B test | Comparar duas versões de artefato | Post com CTA vs. sem CTA |
| Antes/depois | Medir impacto de mudança | Engajamento antes e depois de novo ritual |
| Cohort | Comparar grupos ao longo do tempo | Membros novos vs. veteranos |
| Piloto | Testar em escala reduzida antes de expandir | Ritual testado com 10 membros antes de 100 |
| Survey | Coletar percepções estruturadas | Pesquisa de satisfação pós-evento |
| Etnográfico | Entender comportamento em profundidade | Observação em comunidade por 2 semanas |

### 3. Métricas (O que vamos medir?)

```yaml
métricas:
  primária:
    nome: "" # métrica principal que define sucesso
    método_coleta: "" # como coletamos esse dado
    baseline: "" # valor atual antes do experimento
    frequência_coleta: "" # diária | semanal | ao final
  secundárias:
    - nome: ""
      método_coleta: ""
      baseline: ""
  guardrail:
    nome: "" # métrica que não pode piorar
    limite_aceitável: "" # quanto pode variar sem alarme
```

**Regras das métricas:**
- Métrica primária é uma só — nunca mude no meio do experimento
- Métricas secundárias enriquecem mas não definem sucesso
- Métrica guardrail protege contra efeitos colaterais negativos
- Baseline deve ser medido ANTES do experimento começar

### 4. Duração (Quanto tempo?)

```yaml
duração:
  período: "" # ex: 4 semanas
  data_início: "" # YYYY-MM-DD
  data_fim_prevista: "" # YYYY-MM-DD
  checkpoint_intermediário: "" # YYYY-MM-DD (opcional, para experimentos longos)
  condição_de_parada_antecipada: "" # quando parar antes do prazo
```

**Regras da duração:**
- Definir antes de começar — não estender porque "ainda não deu resultado"
- Mínimo 2 semanas para qualquer experimento com métricas de engajamento
- Checkpoint intermediário obrigatório para experimentos > 4 semanas
- Parada antecipada se métricas guardrail forem violadas

### 5. Critério de Sucesso/Fracasso (Como decidimos?)

```yaml
critério:
  sucesso:
    threshold: "" # ex: "2x mais comentários que controle"
    confiança_mínima: "" # ex: "diferença sustentada por 3+ semanas"
    decisão_se_sucesso: "" # o que fazemos se validar
  fracasso:
    threshold: "" # ex: "diferença < 1.2x"
    decisão_se_fracasso: "" # o que fazemos se invalidar
  inconclusivo:
    condição: "" # ex: "diferença entre 1.2x e 1.5x"
    decisão_se_inconclusivo: "" # ex: "repetir com amostra maior"
```

**Regras dos critérios:**
- Definir ANTES do experimento — nunca ajustar após ver resultados
- Três resultados possíveis: sucesso, fracasso, inconclusivo
- Cada resultado tem uma decisão associada
- "Inconclusivo" não é fracasso — é sinal de que precisa de mais dados

### 6. Registro (O que documentamos?)

```yaml
registro:
  resultado: "" # validado | invalidado | inconclusivo
  dados_finais:
    métrica_primária_teste: ""
    métrica_primária_controle: ""
    diferença: ""
  insights_qualitativos: []
  surpresas: [] # o que não esperávamos
  decisão_final: ""
  decidido_por: ""
  data_decisão: ""
  próximos_passos: []
  aprendizado_para_reutilizar: "" # o que outros times podem aproveitar
```

## Teste de Qualidade do Design

| Critério | Pontuação (1-5) |
|----------|----------------|
| A hipótese é falsificável? | |
| O método isola a variável que queremos testar? | |
| A amostra é suficiente para o efeito esperado? | |
| Os critérios de sucesso foram definidos antes? | |
| A duração é adequada para o tipo de experimento? | |

**Interpretação:**
- 20-25: Design robusto — pode executar
- 15-19: Design aceitável — refinar método ou métricas
- 10-14: Design fraco — retrabalhar antes de executar
- < 10: Design insuficiente — voltar à hipótese

## Armadilhas Comuns

1. **Hipótese retroativa**: formular a hipótese depois de ver os dados
2. **Métrica mutante**: mudar a métrica primária no meio do experimento
3. **Amostra insuficiente**: concluir com 5 observações o que precisa de 50
4. **Duração elástica**: estender o experimento até dar o resultado desejado
5. **Viés de confirmação**: interpretar dados ambíguos como sucesso

## Integração

- Experimentos registrados em `data/registries/experiment-log.yaml`
- Hipóteses alimentadas pelo `thesis-component` e `signal-to-claim-pattern`
- Métricas conectadas ao `movement-health-score-framework`
- Resultados alimentam o ciclo `ralphloop-kaizen`
- Design avaliado pelo `experiment-design-framework`
