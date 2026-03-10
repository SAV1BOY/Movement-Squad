---
id: scaling-without-diluting-pattern
name: "Padrão Crescer sem Diluir"
squad: movement
type: pattern
category: lib/patterns
version: 1.0.0
tags: [escala, crescimento, integridade, diluição, padrão-repetível]
---

# Padrão Crescer sem Diluir

## Propósito

Padrão repetível para escalar um movimento sem perder sua essência, identidade e coerência. O maior risco de um movimento bem-sucedido é crescer a ponto de não significar mais nada.

## O Padrão

```
ESSÊNCIA (o que não muda) → ESCALA (o que se multiplica) → GUARDIÕES (quem protege)
```

### Etapa 1: Definir a Essência Inegociável

```yaml
essência:
  tese_imutável: "" # a crença central que nunca muda
  valores_inegociáveis:
    - valor_1: ""
    - valor_2: ""
    - valor_3: ""
  rituais_sagrados: [] # rituais que devem ser preservados
  linguagem_protegida: [] # termos que não podem ser ressignificados
  fronteira_de_identidade: "" # o que define quem está dentro
  teste_de_essência: "" # pergunta que revela se a essência está intacta
```

### Etapa 2: Desenhar a Escala

```yaml
escala:
  modelo: "" # capítulos | franquias | células | federação | rede
  unidade_mínima: "" # menor grupo funcional
  autonomia_local:
    pode_decidir: []
    não_pode_decidir: []
  adaptação_permitida:
    pode_adaptar: [] # formato, linguagem local, canais
    não_pode_adaptar: [] # tese, valores, rituais sagrados
  recursos_compartilhados: []
  comunicação_entre_unidades: "" # como unidades se conectam
```

**Modelos de escala:**
| Modelo | Controle | Velocidade | Coerência | Exemplo |
|--------|----------|-----------|-----------|---------|
| Capítulos | Alto | Média | Alta | TEDx |
| Franquias | Muito alto | Lenta | Muito alta | CrossFit |
| Células | Baixo | Rápida | Média | Anonymous |
| Federação | Médio | Média | Média | Wikipedia |
| Rede | Muito baixo | Muito rápida | Baixa | #MeToo |

### Etapa 3: Instalar Guardiões

```yaml
guardiões:
  papel: "" # quem protege a essência
  como_são_selecionados: ""
  poderes:
    - poder_1: ""
    - poder_2: ""
  limitações:
    - limitação_1: ""
    - limitação_2: ""
  accountability: "" # a quem respondem
  rotação: "" # mandato fixo ou permanente
  número: "" # quantos guardiões
```

## Sinais de Diluição

| Sinal | Estágio | Ação |
|-------|---------|------|
| Novos membros não conhecem a tese | Inicial | Reforçar onboarding |
| Linguagem própria sendo usada incorretamente | Moderado | Criar guia de linguagem |
| Capítulos agindo contra valores | Avançado | Intervenção de guardiões |
| Mídia define o movimento diferente do que é | Crítico | Campanha de reposicionamento |
| Fundadores não reconhecem o movimento | Terminal | Refundação ou cisão |

## Estratégias de Proteção

### 1. Onboarding Forte
- Todo novo membro passa por ritual de entrada
- A tese é comunicada antes de qualquer ação
- Mentoria obrigatória no primeiro mês

### 2. Conteúdo Canônico
- Manifesto acessível e atualizado
- FAQ de "o que somos e não somos"
- Histórias de origem contadas regularmente

### 3. Feedback Loops
- Pesquisa trimestral de alinhamento
- Canal aberto para denúncia de desvios
- Revisão anual da essência com comunidade

### 4. Poda Estratégica
- Coragem de dizer "isso não somos nós"
- Encerrar capítulos que desviaram
- Recusar crescimento que dilui

## Métricas de Saúde na Escala

| Métrica | Frequência | Alerta |
|---------|-----------|--------|
| % de membros que conhecem a tese | Trimestral | < 70% |
| Consistência de linguagem entre capítulos | Trimestral | < 60% |
| NPS de membros antigos | Semestral | < 50 |
| Taxa de retenção por capítulo | Mensal | < 40% |
| Incidentes de desvio de valores | Mensal | > 3/mês |

## Integração

- Essência definida pelo `thesis-component` e `identity-code-component`
- Guardiões via `community-role-component` e `community-champion-pattern`
- Métricas via `community-health-rubric`
- Desvios documentados em `archive/decisions/`
