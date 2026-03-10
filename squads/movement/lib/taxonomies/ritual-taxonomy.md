---
id: ritual-taxonomy
name: "Taxonomia de Rituais"
squad: movement
type: taxonomy
category: lib/taxonomies
version: 1.0.0
tags: [taxonomia, ritual, classificação, engajamento, comunidade]
---

# Taxonomia de Rituais

## Propósito

Sistema de classificação para os tipos de rituais que sustentam movimentos. Cada tipo de ritual cumpre uma função específica no ciclo de vida do membro e do movimento.

## Tipos de Ritual por Função

### 1. Rituais de Entrada

```yaml
tipo: entrada
função: "Marcar a transição de outsider para membro"
frequência: "Único por membro"
importância: "Crítica — define a primeira impressão"
exemplos:
  - "Primeiro post de apresentação"
  - "Completar um desafio inicial"
  - "Receber badge de boas-vindas"
  - "Mentoria de onboarding 1:1"
duração_típica: "5-30 minutos"
artefato: "Badge, certificado, ou reconhecimento público"
```

### 2. Rituais de Manutenção

```yaml
tipo: manutenção
função: "Manter engajamento e reforçar pertencimento no dia a dia"
frequência: "Diário ou semanal"
importância: "Alta — é o que mantém o movimento vivo"
exemplos:
  - "Check-in diário no canal"
  - "Compartilhar aprendizado da semana"
  - "Stand-up semanal da comunidade"
  - "Desafio semanal temático"
duração_típica: "2-15 minutos"
artefato: "Streak, log de participação"
```

### 3. Rituais de Promoção

```yaml
tipo: promoção
função: "Celebrar progressão de nível dentro do movimento"
frequência: "Conforme progressão do membro"
importância: "Alta — reconhecimento alimenta motivação"
exemplos:
  - "Cerimônia de novo campeão"
  - "Anúncio público de promoção"
  - "Novo badge ou cor de nome"
  - "Acesso a canal exclusivo"
duração_típica: "5-15 minutos"
artefato: "Novo badge, título, acesso"
```

### 4. Rituais de Celebração

```yaml
tipo: celebração
função: "Comemorar conquistas coletivas e marcos do movimento"
frequência: "Mensal, trimestral ou por marco"
importância: "Média-alta — reforça senso de progresso"
exemplos:
  - "Comemoração de marco de membros (1k, 10k)"
  - "Aniversário do movimento"
  - "Celebração de vitória coletiva"
  - "Retrospectiva de fim de ano"
duração_típica: "30-120 minutos"
artefato: "Post comemorativo, vídeo, evento"
```

### 5. Rituais de Luto / Encerramento

```yaml
tipo: luto
função: "Processar perdas, falhas e encerramentos com dignidade"
frequência: "Conforme necessidade"
importância: "Média — negligenciado mas essencial"
exemplos:
  - "Retrospectiva de projeto que falhou"
  - "Despedida de membro importante"
  - "Reconhecimento de erro público"
  - "Encerramento de capítulo/iniciativa"
duração_típica: "15-60 minutos"
artefato: "Post de encerramento, lição documentada"
```

### 6. Rituais de Transição

```yaml
tipo: transição
função: "Marcar mudanças significativas no movimento"
frequência: "Conforme necessidade"
importância: "Alta em momentos de mudança"
exemplos:
  - "Mudança de plataforma"
  - "Revisão de tese ou manifesto"
  - "Troca de liderança"
  - "Fusão com outro grupo"
duração_típica: "30-120 minutos"
artefato: "Documento de transição, novo manifesto"
```

### 7. Rituais de Renovação

```yaml
tipo: renovação
função: "Reconectar o movimento com sua essência e energia original"
frequência: "Anual ou quando necessário"
importância: "Alta para movimentos maduros"
exemplos:
  - "Releitura coletiva do manifesto"
  - "Evento de refundação"
  - "Renovação de compromissos"
  - "Hackathon de reinvenção"
duração_típica: "2-8 horas"
artefato: "Manifesto atualizado, compromissos renovados"
```

## Matriz de Rituais por Estágio

| Estágio do Movimento | Rituais Prioritários |
|----------------------|---------------------|
| Nascente | Entrada + Manutenção |
| Crescimento | Manutenção + Promoção + Celebração |
| Maduro | Todos os tipos |
| Revitalização | Renovação + Transição + Luto |

## Checklist de Design de Ritual

- [ ] O ritual tem nome memorável?
- [ ] Pode ser executado sem o fundador presente?
- [ ] Gera artefato tangível (badge, post, certificado)?
- [ ] Reforça a identidade do movimento?
- [ ] É simples o suficiente para novatos entenderem em 2 minutos?
- [ ] Há versão digital e presencial (se aplicável)?

## Integração

- Rituais projetados com `ritual-script-component`
- Conectados à progressão via `community-role-component`
- Transição ritual → hábito via `ritual-to-habit-pattern`
- Saúde medida pelo `community-health-rubric`
