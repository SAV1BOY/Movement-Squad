---
id: readiness-review-rubric
name: "Rubrica de Readiness Review (Go/No-Go)"
squad: movement
type: utility
category: lib/utilities
version: 1.0.0
tags: [rubrica, readiness, go-no-go, lançamento, avaliação]
---

# Rubrica de Readiness Review (Go/No-Go)

## Propósito

Ferramenta padronizada para avaliar se um movimento está pronto para lançamento ou para avançar para uma nova fase crítica. Previne lançamentos prematuros e garante que todas as condições mínimas estejam atendidas antes de investir recursos em escala.

## Dimensões de Avaliação

### 1. Tese Validada (0-25 pontos)

| Pontuação | Critério |
|-----------|----------|
| 0-5 | Sem tese clara — não há inimigo, sonho ou mecanismo definidos |
| 6-10 | Tese rascunhada — existe mas não foi testada com público real |
| 11-15 | Tese testada — validada qualitativamente com amostra pequena |
| 16-20 | Tese validada — dados quantitativos e qualitativos confirmam ressonância |
| 21-25 | Tese magnética — público-alvo se mobiliza espontaneamente ao ouvi-la |

**O que verificar:**
- A tese foi articulada no formato inimigo-sonho-mecanismo?
- Pelo menos 3 sinais convergentes sustentam a tese?
- A tese foi testada com mínimo 10 pessoas do público-alvo?
- Taxa de concordância espontânea é superior a 60%?
- Contra-argumentos foram mapeados e rebatidos?

### 2. Identidade Pronta (0-25 pontos)

| Pontuação | Critério |
|-----------|----------|
| 0-5 | Sem identidade — não há linguagem, símbolos ou código definidos |
| 6-10 | Identidade conceitual — existe no papel mas não foi testada |
| 11-15 | Identidade básica — nome, linguagem e símbolos definidos e testados |
| 16-20 | Identidade completa — kit de identidade pronto com manifesto e slogans |
| 21-25 | Identidade adotada — early adopters já usam espontaneamente a linguagem |

**O que verificar:**
- O movimento tem nome que ressoa com o público-alvo?
- Existe manifesto aprovado e pronto para publicação?
- Slogans foram testados e pelo menos 1 tem recall comprovado?
- Código visual (cores, tipografia, símbolo) está definido?
- Linguagem do grupo (termos, saudações, jargões) está documentada?

### 3. Artefatos Prontos (0-25 pontos)

| Pontuação | Critério |
|-----------|----------|
| 0-5 | Sem artefatos — nada materializado |
| 6-10 | Artefatos em rascunho — existem mas sem qualidade para publicação |
| 11-15 | Artefatos mínimos — conteúdo de lançamento pronto para 1-2 canais |
| 16-20 | Artefatos completos — conteúdo para todos os canais planejados + variações |
| 21-25 | Artefatos testados — variações testadas com A/B e otimizadas |

**O que verificar:**
- Há conteúdo suficiente para as primeiras 2 semanas pós-lançamento?
- Cada canal planejado tem pelo menos 3 peças prontas?
- Templates para a comunidade foram criados e testados?
- Conteúdo está revisado quanto a tom de voz e qualidade narrativa?
- Variações para teste A/B foram preparadas para peças-chave?

### 4. Comunidade Seed (0-25 pontos)

| Pontuação | Critério |
|-----------|----------|
| 0-5 | Sem comunidade — nenhum membro recrutado |
| 6-10 | Lista de contatos — potenciais membros identificados mas não engajados |
| 11-15 | Grupo formado — 10-30 membros iniciais recrutados e engajados |
| 16-20 | Comunidade ativa — 30-100 membros com rituais e papéis definidos |
| 21-25 | Comunidade autônoma — membros geram conteúdo e recrutam sem pedir |

**O que verificar:**
- Existe um grupo seed com mínimo 10 membros comprometidos?
- Champions foram identificados e receberam onboarding?
- Pelo menos 1 ritual comunitário foi testado e funcionou?
- Canais de comunicação da comunidade estão configurados?
- Membros seed demonstram disposição para amplificar no lançamento?

### 5. Métricas Baseline (0-25 pontos)

| Pontuação | Critério |
|-----------|----------|
| 0-5 | Sem métricas — não há definição de sucesso |
| 6-10 | Métricas vagas — intenções sem números ("aumentar engajamento") |
| 11-15 | Métricas definidas — KPIs com targets mas sem baseline atual |
| 16-20 | Métricas com baseline — KPIs com baseline medido e targets realistas |
| 21-25 | Métricas operacionais — dashboards configurados, tracking ativo, alertas definidos |

**O que verificar:**
- Win conditions estão traduzidas em KPIs mensuráveis?
- Baseline atual foi medido para cada KPI?
- Targets são ambiciosos mas alcançáveis (SMART)?
- Ferramentas de medição estão configuradas e testadas?
- Existe cadência definida para revisão de métricas?

## Classificação Geral

| Pontuação Total | Classificação | Decisão |
|----------------|---------------|---------|
| 100-125 | GOLD — Pronto com excelência | GO imediato |
| 75-99 | GOOD — Pronto com ressalvas | GO com monitoramento próximo |
| 50-74 | REVIEW — Quase pronto | NO-GO até resolver gaps críticos |
| 0-49 | REJECT — Não está pronto | NO-GO, voltar à fase de preparação |

## Regras de Decisão

- **Veto absoluto:** Se qualquer dimensão pontuar abaixo de 6, é NO-GO independente do total
- **Mínimo por dimensão:** Cada dimensão deve pontuar pelo menos 11 para GO
- **Reavaliação:** Após NO-GO, a reavaliação deve acontecer em no máximo 14 dias
- **Registro:** Toda decisão (GO ou NO-GO) deve ser documentada com racional

## Como Usar

1. **Agende a review** — convoque todos os avaliadores com 48h de antecedência
2. **Prepare os materiais** — cada dimensão deve ter evidências disponíveis para consulta
3. **Avalie individualmente** — cada avaliador pontua antes da discussão em grupo
4. **Discuta divergências** — foque em dimensões onde as notas divergem mais de 5 pontos
5. **Consolide a pontuação** — média das avaliações individuais arredondada para baixo
6. **Documente a decisão** — registre pontuações, decisão, condições e próximos passos

## Template de Avaliação

```yaml
readiness_review:
  data: YYYY-MM-DD
  movimento: ""
  fase: ""  # lançamento | escala | pivot
  avaliadores: []
  pontuações:
    tese_validada: 0
    identidade_pronta: 0
    artefatos_prontos: 0
    comunidade_seed: 0
    métricas_baseline: 0
  total: 0
  classificação: ""  # GOLD | GOOD | REVIEW | REJECT
  decisão: ""  # GO | NO-GO
  condições: []
  gaps_críticos: []
  data_reavaliação: ""
  próximos_passos: []
```

## Integração

- Alimentado pelos outputs de cada fase do `new-movement-launch/`
- Resultado registrado em `data/readiness-reviews/`
- Protocolo completo descrito em `readiness-review-protocol`
- Dimensão "Tese Validada" avaliada em detalhe pelo `thesis-strength-rubric`
- Dimensão "Identidade Pronta" avaliada pelo `identity-code-component`
- Dimensão "Métricas Baseline" conectada ao `movement-health-score`
