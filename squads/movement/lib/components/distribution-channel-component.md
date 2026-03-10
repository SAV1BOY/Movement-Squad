---
id: distribution-channel-component
name: "Componente de Canal de Distribuição"
squad: movement
type: component
category: lib/components
version: 1.0.0
tags: [distribuição, canal, alcance, amplificação, componente-reutilizável]
---

# Componente de Canal de Distribuição

## Propósito

Bloco reutilizável para mapear, selecionar e otimizar os canais de distribuição de um movimento. Define onde, como e quando a mensagem chega ao público.

## Estrutura do Bloco

### 1. Mapeamento do Canal

```yaml
canal:
  nome: ""
  tipo: "" # próprio | pago | conquistado | compartilhado
  plataforma: "" # Instagram | TikTok | YouTube | Twitter | LinkedIn | Email | WhatsApp | Presencial | Podcast
  formato_nativo: "" # vídeo curto | imagem | texto | áudio | ao vivo
  audiência_estimada: ""
  perfil_da_audiência: ""
  custo: "" # gratuito | baixo | médio | alto
  controle_editorial: "" # total | parcial | nenhum
```

### 2. Estratégia por Canal

```yaml
estratégia:
  objetivo_no_canal: "" # awareness | engajamento | conversão | comunidade
  frequência: "" # diário | 3x semana | semanal | quinzenal | mensal
  melhor_horário: ""
  tipo_de_conteúdo: []
  tom_específico: "" # pode variar do tom geral do movimento
  métricas_do_canal:
    - métrica_1: ""
    - métrica_2: ""
  responsável: ""
```

### 3. Mix de Canais

```yaml
mix:
  canal_âncora: "" # onde está o conteúdo principal
  canais_de_amplificação: [] # onde o conteúdo é redistribuído
  canal_de_comunidade: "" # onde membros se reúnem
  canal_de_conversão: "" # onde a ação acontece
  canal_de_retenção: "" # onde membros se mantêm engajados
```

### 4. Fluxo de Conteúdo Entre Canais

```yaml
fluxo:
  origem: "" # onde o conteúdo nasce
  adaptações:
    - de: ""
      para: ""
      transformação: "" # como o conteúdo é adaptado
    - de: ""
      para: ""
      transformação: ""
  ciclo_de_vida: "" # quanto tempo o conteúdo permanece ativo
  reaproveitamento: "" # como conteúdo antigo volta a circular
```

## Matriz de Canais por Objetivo

| Canal | Awareness | Engajamento | Conversão | Comunidade | Retenção |
|-------|-----------|-------------|-----------|------------|----------|
| TikTok/Reels | ★★★★★ | ★★★☆☆ | ★☆☆☆☆ | ★☆☆☆☆ | ★★☆☆☆ |
| Twitter/X | ★★★★☆ | ★★★★☆ | ★★☆☆☆ | ★★★☆☆ | ★★☆☆☆ |
| Instagram Feed | ★★★☆☆ | ★★★★☆ | ★★★☆☆ | ★★☆☆☆ | ★★★☆☆ |
| YouTube | ★★★☆☆ | ★★★★★ | ★★★☆☆ | ★★☆☆☆ | ★★★★☆ |
| LinkedIn | ★★★☆☆ | ★★★☆☆ | ★★★★☆ | ★★☆☆☆ | ★★★☆☆ |
| Email/Newsletter | ★☆☆☆☆ | ★★★☆☆ | ★★★★★ | ★★☆☆☆ | ★★★★★ |
| WhatsApp/Telegram | ★☆☆☆☆ | ★★★★★ | ★★★☆☆ | ★★★★★ | ★★★★★ |
| Discord/Slack | ★☆☆☆☆ | ★★★★★ | ★★☆☆☆ | ★★★★★ | ★★★★☆ |
| Podcast | ★★☆☆☆ | ★★★★★ | ★★★☆☆ | ★★★☆☆ | ★★★★★ |
| Presencial | ★★☆☆☆ | ★★★★★ | ★★★★★ | ★★★★★ | ★★★★★ |

## Regras de Uso

1. **Máximo 3 canais ativos no início** — presença fraca em muitos é pior que forte em poucos
2. **Cada canal deve ter objetivo claro** — se não sabe por que está lá, saia
3. **Conteúdo deve ser nativo** — nunca poste o mesmo formato em todos os canais
4. **Canal de comunidade é inegociável** — sem espaço próprio, não há movimento
5. **Meça por canal, não agregado** — cada canal tem sua métrica

## Checklist de Qualidade

- [ ] O canal âncora está definido e priorizado?
- [ ] Existe canal de comunidade onde membros interagem?
- [ ] O fluxo entre canais está mapeado?
- [ ] Cada canal tem responsável definido?
- [ ] As métricas por canal são específicas e mensuráveis?

## Integração

- Alimentado pelo `movement-brief-component` (público e onde se reúnem)
- Define onde o `creator-brief-component` será executado
- Métricas alimentam `memetic-spread-rubric`
- Conecta ao padrão `scaling-without-diluting-pattern`
