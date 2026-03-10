---
id: community-champion-pattern
name: "Padrão de Formação de Campeões"
squad: movement
type: pattern
category: lib/patterns
version: 1.0.0
tags: [campeões, comunidade, liderança-distribuída, embaixadores, padrão-repetível]
---

# Padrão de Formação de Campeões

## Propósito

Padrão repetível para identificar, desenvolver e empoderar campeões que amplificam o movimento de forma autônoma. Campeões são o mecanismo de escala de qualquer movimento sustentável.

## O Padrão

```
IDENTIFICAR (quem tem potencial) → DESENVOLVER (capacitar) → EMPODERAR (dar autonomia) → RECONHECER (celebrar)
```

### Etapa 1: Identificar Potenciais Campeões

```yaml
identificação:
  sinais_de_potencial:
    - "Contribui sem ser pedido"
    - "Defende o movimento para externos"
    - "Traz novos membros espontaneamente"
    - "Cria conteúdo próprio sobre o tema"
    - "Responde dúvidas de outros membros"
  métricas_de_triagem:
    frequência_de_participação: "" # mínimo 3x/semana
    qualidade_de_contribuição: "" # ajuda outros, não só consome
    alinhamento_de_valores: "" # demonstra crenças do movimento
    influência_no_grupo: "" # outros membros o referenciam
  onde_procurar:
    - "Membros mais ativos nos últimos 90 dias"
    - "Quem responde perguntas de novatos"
    - "Quem compartilha o movimento externamente"
    - "Quem sugere melhorias construtivamente"
```

### Etapa 2: Desenvolver Campeões

```yaml
desenvolvimento:
  onboarding:
    convite_pessoal: "" # sempre individual, nunca genérico
    expectativas_claras: "" # o que esperamos e oferecemos
    período: "" # 2-4 semanas de ramp-up
  capacitação:
    conhecimento:
      - "História e tese do movimento"
      - "Linguagem e código de identidade"
      - "Respostas para objeções comuns"
    habilidades:
      - "Facilitação de conversas"
      - "Criação de conteúdo no tom do movimento"
      - "Gestão de conflitos"
    ferramentas:
      - "Kit de materiais do movimento"
      - "Templates de conteúdo"
      - "Canal direto com liderança"
  mentoria:
    mentor_designado: "" # campeão sênior ou líder
    frequência_de_check_in: "" # semanal no início, quinzenal depois
    duração_da_mentoria: "" # 3-6 meses
```

### Etapa 3: Empoderar Campeões

```yaml
empoderamento:
  autonomia:
    decisões_que_pode_tomar: []
    recursos_que_pode_usar: []
    iniciativas_que_pode_criar: []
  limites:
    decisões_que_precisam_de_aprovação: []
    temas_sensíveis: []
    protocolo_de_crise: ""
  suporte:
    canal_de_emergência: ""
    reunião_de_campeões: "" # frequência e formato
    orçamento_disponível: ""
```

### Etapa 4: Reconhecer Campeões

```yaml
reconhecimento:
  reconhecimento_público:
    - "Destaque em canais oficiais"
    - "Badge ou título visível"
    - "Menção em eventos"
  reconhecimento_privado:
    - "Agradecimento pessoal da liderança"
    - "Acesso antecipado a novidades"
    - "Convite para decisões estratégicas"
  reconhecimento_tangível:
    - "Merch exclusivo"
    - "Ingresso para eventos"
    - "Oportunidades profissionais"
  celebração_de_marcos:
    - marco_30_dias: ""
    - marco_100_contribuições: ""
    - marco_1_ano: ""
```

## Métricas do Programa

| Métrica | Meta | Frequência |
|---------|------|-----------|
| Taxa de aceitação do convite | > 70% | Mensal |
| Retenção de campeões (6 meses) | > 60% | Trimestral |
| Contribuições por campeão/mês | > 8 | Mensal |
| Novos membros trazidos por campeão | > 3/mês | Mensal |
| NPS dos campeões | > 80 | Trimestral |

## Anti-padrões

- **Selecionar por popularidade** em vez de contribuição real
- **Treinar demais, empoderar de menos** — campeões não são estagiários
- **Reconhecimento genérico** — "obrigado a todos" não funciona
- **Escalar rápido demais** — melhor 5 campeões excelentes que 50 mediocres
- **Ignorar burnout** — campeões voluntários precisam de pausas

## Integração

- Papéis definidos pelo `community-role-component`
- Rituais de entrada via `ritual-script-component`
- Métricas alimentam `community-health-rubric`
- Classificação via `community-role-taxonomy`
