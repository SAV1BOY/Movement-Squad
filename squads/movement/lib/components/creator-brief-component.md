---
id: creator-brief-component
name: "Componente de Brief para Criadores"
squad: movement
type: component
category: lib/components
version: 1.0.0
tags: [criador, brief, conteúdo, influenciador, componente-reutilizável]
---

# Componente de Brief para Criadores

## Propósito

Bloco reutilizável para briefar criadores de conteúdo, influenciadores e embaixadores que vão amplificar a mensagem do movimento. Equilibra direção estratégica com liberdade criativa.

## Estrutura do Bloco

### 1. Contexto do Movimento

```yaml
contexto:
  nome_do_movimento: ""
  tese_resumida: "" # máximo 2 frases
  momento_atual: "" # lançamento | crescimento | crise | celebração
  público_alvo: ""
  tom_do_movimento: "" # combativo | inspiracional | educativo | provocativo
```

### 2. Objetivo da Peça

```yaml
objetivo:
  tipo: "" # awareness | engajamento | conversão | retenção | advocacy
  ação_desejada: "" # o que queremos que a audiência faça
  métrica_de_sucesso: ""
  prazo: ""
  contexto_temporal: "" # sazonalidade, evento, data relevante
```

### 3. Diretrizes Criativas

```yaml
criativo:
  mensagem_central: "" # a única coisa que deve ficar
  pontos_obrigatórios:
    - ponto_1: ""
    - ponto_2: ""
  pontos_proibidos:
    - proibido_1: ""
    - proibido_2: ""
  tom_de_voz: ""
  referências_visuais: []
  hashtags_obrigatórias: []
  hashtags_sugeridas: []
  call_to_action: ""
```

### 4. Formato e Canal

```yaml
formato:
  canal_primário: "" # Instagram | TikTok | YouTube | Twitter | LinkedIn | Podcast
  tipo_de_conteúdo: "" # reels | stories | post | thread | vídeo longo | áudio
  duração_ideal: ""
  dimensões: "" # se aplicável
  legendas: "" # sim | não | opcional
  idioma: ""
  acessibilidade: [] # legenda, audiodescrição, alt text
```

### 5. Perfil do Criador

```yaml
criador:
  tipo: "" # micro | macro | nano | especialista | celebridade | comunidade
  nicho: ""
  valores_alinhados: []
  audiência_estimada: ""
  histórico_com_movimento: "" # novo | parceiro | membro
  compensação: "" # orgânica | permuta | paga | equity social
```

### 6. Entregas e Prazos

```yaml
entregas:
  quantidade_de_peças: 0
  prazo_de_produção: ""
  prazo_de_publicação: ""
  aprovação_necessária: "" # sim | não
  fluxo_de_aprovação: ""
  direitos_de_uso: "" # orgânico | pago | perpétuo
```

## Regras de Uso

1. **A mensagem central deve caber em uma frase** — se o criador não entende, a audiência não entenderá
2. **Menos pontos obrigatórios = melhor conteúdo** — máximo 3
3. **Pontos proibidos são mais importantes** que pontos obrigatórios
4. **Dê exemplos, não scripts** — criadores criam melhor com referência do que com roteiro
5. **Respeite a voz do criador** — autenticidade supera controle

## Checklist de Qualidade

- [ ] O criador entende a tese do movimento?
- [ ] O objetivo é único e mensurável?
- [ ] Os pontos obrigatórios são realmente obrigatórios?
- [ ] O formato é nativo do canal escolhido?
- [ ] A compensação é justa e transparente?
- [ ] Os direitos de uso estão claros?

## Anti-padrões

- **Brief de 10 páginas**: se é longo demais, ninguém lê
- **Roteiro palavra por palavra**: mata autenticidade
- **Múltiplos CTAs**: um CTA por peça, sempre
- **Ignorar o estilo do criador**: adaptação > imposição
- **Sem métricas definidas**: sem métrica = sem aprendizado

## Integração

- Alimentado pelo `movement-brief-component` (contexto e público)
- Usa linguagem do `identity-code-component`
- Canal definido pelo `distribution-channel-component`
- Métricas alimentam `memetic-spread-rubric`
