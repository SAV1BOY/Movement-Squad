---
id: movement-brief-component
name: "Componente de Brief de Movimento"
squad: movement
type: component
category: lib/components
version: 1.0.0
tags: [brief, movimento, planejamento, componente-reutilizável]
---

# Componente de Brief de Movimento

## Propósito

Bloco reutilizável para estruturar o brief inicial de qualquer movimento. Garante que todas as dimensões críticas sejam endereçadas antes da execução.

## Estrutura do Bloco

### 1. Contexto do Movimento

```yaml
contexto:
  nome_do_movimento: ""
  marca_ou_causa: ""
  estado_atual: "" # nascente | emergente | estabelecido | revitalização
  urgência: "" # baixa | média | alta | crítica
  horizonte_temporal: "" # curto (1-3m) | médio (3-12m) | longo (12m+)
```

### 2. Tensão Fundadora

```yaml
tensão:
  frustração_central: ""
  quem_sente: ""
  por_que_agora: ""
  evidências_da_tensão:
    - sinal_1: ""
    - sinal_2: ""
    - sinal_3: ""
```

### 3. Visão do Movimento

```yaml
visão:
  mundo_que_queremos: ""
  inimigo_declarado: ""
  sonho_compartilhado: ""
  mecanismo_de_mudança: ""
```

### 4. Público-Alvo Primário

```yaml
público:
  perfil_demográfico: ""
  perfil_psicográfico: ""
  dor_principal: ""
  desejo_principal: ""
  onde_se_reúnem: []
  linguagem_que_usam: []
```

### 5. Ativos Existentes

```yaml
ativos:
  comunidade_atual: "" # tamanho e engajamento
  canais_próprios: []
  conteúdo_existente: []
  aliados_potenciais: []
  orçamento_disponível: ""
```

### 6. Métricas de Sucesso

```yaml
métricas:
  indicador_primário: ""
  indicadores_secundários: []
  marco_30_dias: ""
  marco_90_dias: ""
  marco_12_meses: ""
```

## Regras de Uso

1. **Nunca pule a tensão fundadora** — sem tensão real, não há movimento
2. **Evidências são obrigatórias** — mínimo 3 sinais observáveis
3. **O inimigo deve ser sistêmico**, nunca pessoal
4. **Métricas devem ser observáveis**, não aspiracionais
5. **Revise o brief a cada 30 dias** no mínimo

## Exemplo de Preenchimento

```yaml
contexto:
  nome_do_movimento: "Código Aberto para Todos"
  marca_ou_causa: "Comunidade DevBR"
  estado_atual: "nascente"
  urgência: "média"
  horizonte_temporal: "médio"

tensão:
  frustração_central: "Desenvolvedores juniores excluídos do open source"
  quem_sente: "Devs com menos de 2 anos de experiência"
  por_que_agora: "Mercado exige contribuições open source no currículo"
  evidências_da_tensão:
    - sinal_1: "Thread viral no Twitter com 12k likes sobre gatekeeping"
    - sinal_2: "Pesquisa mostra 73% de juniores intimidados por PRs"
    - sinal_3: "Repos com label 'good first issue' abandonados"
```

## Integração

- Alimenta o `thesis-component` com tensão e visão
- Conecta ao `identity-code-component` para linguagem
- Serve de input para `manifesto-block-component`
