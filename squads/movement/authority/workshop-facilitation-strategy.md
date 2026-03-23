---
id: workshop-facilitation-strategy
name: "Estratégia de Facilitação de Workshops"
squad: movement
type: authority
category: authority
version: 1.0.0
tags: [autoridade, workshop, facilitação, educação, estratégia]
---

# Estratégia de Facilitação de Workshops

## Propósito

Framework para projetar e facilitar workshops que constroem autoridade, educam participantes e ampliam o movimento através de experiências transformadoras.

## Por Que Workshops

1. **Transformação > Informação:** Workshops mudam comportamento, palestras mudam opinião
2. **Experiência compartilhada:** Participantes se conectam entre si (não apenas com o facilitador)
3. **Prova de expertise:** Facilitar demonstra domínio profundo do tema
4. **Recrutamento qualificado:** Participantes engajados se tornam membros
5. **Revenue:** Workshops pagos geram receita e filtram participantes sérios

## Tipos de Workshop

| Tipo | Duração | Participantes | Objetivo | Preço Sugerido |
|------|---------|---------------|----------|---------------|
| Lightning | 30-60 min | 10-50 | Introdução ao tema | Gratuito |
| Standard | 2-4 horas | 10-30 | Aplicação prática | Baixo-médio |
| Intensivo | 1 dia | 8-20 | Transformação profunda | Médio-alto |
| Programa | Multi-sessão | 6-15 | Mudança de prática | Alto |
| Retiro | 2-3 dias | 10-25 | Imersão total | Premium |

## Estrutura de Workshop (Standard — 3 horas)

### Bloco 1: Abertura (30 min)

```yaml
abertura:
  check_in: "" # atividade para conectar participantes (10 min)
  contexto: "" # por que estamos aqui, a tensão central (10 min)
  acordo: "" # regras de convivência co-criadas (5 min)
  overview: "" # o que vamos fazer e o que vamos sair com (5 min)
```

**Regra:** Nunca comece com slides. Comece com pessoas.

### Bloco 2: Conteúdo + Prática (120 min)

```yaml
conteúdo:
  módulo_1:
    conceito: "" # framework ou insight (15 min)
    exercício: "" # aplicação prática individual ou em dupla (20 min)
    compartilhamento: "" # 2-3 participantes apresentam (10 min)

  módulo_2:
    conceito: "" # aprofundamento (15 min)
    exercício: "" # aplicação em grupo (25 min)
    compartilhamento: "" # apresentação e feedback (15 min)

  intervalo: "15 min" # café e networking informal

  módulo_3:
    conceito: "" # integração (10 min)
    exercício: "" # exercício final integrador (15 min)
```

**Proporção ideal:** 30% teoria / 70% prática

### Bloco 3: Encerramento (30 min)

```yaml
encerramento:
  síntese: "" # o que aprendemos juntos (10 min)
  compromisso: "" # cada participante declara uma ação (10 min)
  check_out: "" # atividade de fechamento emocional (5 min)
  próximos_passos: "" # como manter conexão (5 min)
```

## Princípios de Facilitação

### 1. Segurança Psicológica
- Criar ambiente onde errar é permitido
- Normalizar "eu não sei" como resposta válida
- Confidencialidade sobre o que é compartilhado

### 2. Participação Ativa
- Nunca mais de 15 minutos sem interação
- Variar formatos: individual → dupla → grupo → plenário
- Dar voz a quem não fala espontaneamente

### 3. Aplicação Imediata
- Todo conceito deve ter exercício prático imediatamente
- Participantes devem sair com artefato tangível (canvas, plano, template)
- Compromisso público de ação no encerramento

### 4. Energia e Ritmo
- Blocos de alta energia (discussão) alternados com reflexão
- Movimentação física a cada 45-60 minutos
- Música nos intervalos e exercícios

## Design de Exercícios

| Formato | Melhor Para | Duração |
|---------|-------------|---------|
| Reflexão individual | Introspecção, autoconhecimento | 5-10 min |
| Dupla | Troca íntima, feedback direto | 10-15 min |
| Trio/quarteto | Diversidade de perspectivas | 15-25 min |
| Grupo (6-8) | Co-criação, brainstorm | 20-30 min |
| Plenário | Compartilhamento, debate | 15-20 min |

## Antes do Workshop

- Enviar questionário pré-workshop (expectativas e nível)
- Preparar materiais (impressos ou digitais)
- Testar tecnologia se online
- Preparar sala/ambiente (para presencial)

## Depois do Workshop

| Ação | Prazo | Formato |
|------|-------|---------|
| Email de agradecimento + materiais | 24h | Email |
| Fotos/registros do workshop | 48h | Email/grupo |
| Pesquisa de feedback | 48h | Formulário |
| Follow-up de compromissos | 2 semanas | Email/mensagem |
| Convite para comunidade | 1 semana | Email |
| Conteúdo derivado publicado | 2-4 semanas | Blog/redes |

## Métricas

| Métrica | Como Medir | Meta |
|---------|-----------|------|
| NPS do workshop | Pesquisa pós | > 70 |
| Taxa de conclusão de compromisso | Follow-up 30 dias | > 40% |
| Taxa de entrada na comunidade | Tracking | > 30% |
| Recomendação espontânea | Tracking | > 20% |
| Receita por participante | Financeiro | Cobrir custos + margem |

## Armadilhas

1. **Muito conteúdo, pouca prática:** Participantes querem fazer, não ouvir
2. **Sem follow-up:** Workshop sem continuidade é evento isolado
3. **Grupo grande demais:** > 30 pessoas reduz qualidade de interação
4. **Facilitador como palestrante:** Facilitar é criar espaço, não preencher
5. **Sem diversidade:** Grupo homogêneo gera perspectiva limitada

## Integração

- Workshops usam componentes do `thesis-component` e `proof-component`
- Exercícios podem aplicar `ritual-script-component`
- Participantes alimentam `community-champion-pattern`
- Complementa `thought-leadership-strategy` e `conference-speaking-strategy`
