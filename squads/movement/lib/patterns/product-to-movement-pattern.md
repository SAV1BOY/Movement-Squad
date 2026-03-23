---
id: product-to-movement-pattern
name: "Padrão Produto → Uso → Advocacia → Cultura"
squad: movement
type: pattern
category: lib/patterns
version: 1.0.0
tags: [produto, advocacia, cultura, brand-movement, padrão-repetível]
---

# Padrão Produto → Uso → Advocacia → Cultura

## Propósito

Padrão repetível para transformar a experiência de uso de um produto em advocacia espontânea e, eventualmente, em cultura — o estágio onde o produto transcende sua função e se torna parte da identidade das pessoas.

## O Padrão

```
PRODUTO (funcional) → USO (experiência) → ADVOCACIA (evangelização) → CULTURA (identidade)
```

### Etapa 1: Produto com Ponto de Vista

```yaml
produto:
  função: "" # o que faz
  ponto_de_vista: "" # o que acredita
  tensão_que_endereça: "" # frustração que resolve
  diferencial_ideológico: "" # por que existe além da função
  experiência_wow: "" # momento que surpreende o usuário
  história_de_origem: "" # por que foi criado
```

**Requisito fundamental:** O produto deve ter um ponto de vista sobre o mundo, não apenas uma funcionalidade. Sem ponto de vista, não há movimento possível.

### Etapa 2: Uso que Gera História

```yaml
uso:
  momento_aha: "" # quando o usuário entende o ponto de vista
  experiência_compartilhável: "" # o que o usuário quer contar
  resultado_visível: "" # mudança observável por outros
  linguagem_gerada: "" # termos que usuários inventam
  hack_de_usuário: "" # usos não previstos que revelam valor
  comunidade_espontânea: "" # onde usuários se reúnem sem convite
```

**Escada de experiência:**
```
1. Funcional: "Funciona bem" (satisfação)
2. Emocional: "Me faz sentir X" (conexão)
3. Social: "Quero que outros vejam" (exibição)
4. Identitário: "Isso sou eu" (incorporação)
```

### Etapa 3: Advocacia Espontânea

```yaml
advocacia:
  gatilho_de_recomendação: "" # o que faz o usuário indicar
  formato_natural: "" # como a recomendação acontece
  história_que_contam: "" # o que advogados dizem sobre o produto
  objeções_que_respondem: "" # como defendem contra críticas
  comunidade_de_advogados: "" # onde se organizam
  reconhecimento: "" # como a marca reconhece advogados
```

**Níveis de advocacia:**
| Nível | Comportamento | Exemplo |
|-------|--------------|---------|
| Passivo | Responde quando perguntado | "Sim, eu uso e gosto" |
| Ativo | Recomenda espontaneamente | "Você precisa conhecer isso" |
| Criativo | Cria conteúdo sobre | Unboxing, review, tutorial |
| Militante | Defende contra críticos | "Você não entendeu o ponto" |
| Missionário | Recruta ativamente | "Deixa eu te mostrar" |

### Etapa 4: Cultura e Identidade

```yaml
cultura:
  declaração_identitária: "" # "eu sou [tipo de pessoa que usa]"
  subcultura: "" # grupo cultural que se forma ao redor
  rituais_emergentes: [] # comportamentos que surgem organicamente
  linguagem_própria: [] # vocabulário criado pela comunidade
  símbolos: [] # símbolos adotados pela comunidade
  valores_compartilhados: [] # crenças que unem a comunidade
  resistência_a_alternativas: "" # por que não mudam
  identidade_anti: "" # o que não são (vs. produtos concorrentes)
```

## Exemplos por Estágio

| Marca | Produto | Uso | Advocacia | Cultura |
|-------|---------|-----|-----------|---------|
| Apple | Computador bonito | Criatividade facilitada | "Sou Mac, não PC" | Identidade criativa |
| CrossFit | Treino funcional | Resultados visíveis | WOD no Instagram | Estilo de vida fitness |
| Tesla | Carro elétrico | Sem gasolina nunca mais | "O futuro é elétrico" | Identidade sustentável |
| Notion | App de notas | Workspace personalizado | Templates compartilhados | Produtividade como arte |

## Aceleradores de Transição

### Produto → Uso
- Onboarding que mostra o ponto de vista, não só o tutorial
- Primeiro resultado em menos de 5 minutos

### Uso → Advocacia
- Resultados visíveis por outras pessoas
- Facilitar compartilhamento do resultado (não do produto)
- Programa de embaixadores com benefícios reais

### Advocacia → Cultura
- Dar nome ao grupo de advogados
- Criar rituais exclusivos para a comunidade
- Permitir que a comunidade co-crie o produto e a narrativa

## Métricas por Estágio

| Estágio | Métrica Principal | Meta |
|---------|------------------|------|
| Produto | NPS | > 50 |
| Uso | DAU/MAU | > 40% |
| Advocacia | % de usuários que indicam | > 30% |
| Cultura | % que se identifica com a marca | > 15% |

## Integração

- Ponto de vista definido pelo `thesis-component`
- Cultura conecta ao `identity-code-component`
- Advocacia usa `community-champion-pattern`
- Escala via `scaling-without-diluting-pattern`
