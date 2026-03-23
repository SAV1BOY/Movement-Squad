---
id: artifact-taxonomy
name: "Taxonomia de Artefatos"
squad: movement
type: taxonomy
category: lib/taxonomies
version: 1.0.0
tags: [taxonomia, artefato, classificação, conteúdo, manifesto]
---

# Taxonomia de Artefatos

## Propósito

Sistema de classificação para todos os tipos de artefatos que um movimento produz. Artefatos são os objetos tangíveis que carregam e espalham a mensagem.

## Tipos de Artefato

### 1. Artefatos Narrativos

| Artefato | Descrição | Extensão | Vida Útil | Exemplo |
|----------|-----------|----------|-----------|---------|
| Manifesto | Declaração completa de crenças e chamada à ação | 400-800 palavras | Anos | "Think Different" manifesto |
| Slogan | Frase-síntese do movimento | 3-10 palavras | Anos | "Just Do It" |
| Meme | Imagem/vídeo viral que carrega a mensagem | 1-10 seg | Dias-semanas | Meme de "It's fine" |
| Thread | Argumento desenvolvido em posts sequenciais | 5-25 posts | Semanas | Thread de Twitter viral |
| Carta aberta | Comunicação pública endereçada a um alvo | 500-1500 palavras | Meses | Carta aberta ao CEO |
| Origem | História de como o movimento nasceu | 200-500 palavras | Permanente | "Começou quando..." |

### 2. Artefatos Visuais

| Artefato | Descrição | Formato | Vida Útil | Exemplo |
|----------|-----------|---------|-----------|---------|
| Logo/Símbolo | Marca visual do movimento | Imagem vetorial | Anos | Punho erguido |
| Paleta de cores | Cores oficiais do movimento | Guia de cores | Anos | Rosa do feminismo |
| Template | Modelo visual replicável | PSD/Figma/Canva | Meses | Frame de Instagram |
| Infográfico | Dados do movimento em formato visual | Imagem | Meses | Estatísticas da causa |
| Banner | Imagem de capa para canais | Imagem | Meses | Banner de comunidade |

### 3. Artefatos Físicos

| Artefato | Descrição | Formato | Vida Útil | Exemplo |
|----------|-----------|---------|-----------|---------|
| Camiseta | Vestuário com identidade do movimento | Textil | Anos | Camiseta "I ♥ NY" |
| Sticker | Adesivo para distribuição | Vinil/papel | Meses-anos | Stickers de laptop |
| Pin/Badge | Broche de identificação | Metal/acrílico | Anos | Laço de conscientização |
| Zine | Publicação independente | Impresso | Meses | Zine do movimento punk |
| Cartaz | Pôster para eventos/protestos | Papel/digital | Dias-meses | Cartazes do Occupy |

### 4. Artefatos de Experiência

| Artefato | Descrição | Formato | Vida Útil | Exemplo |
|----------|-----------|---------|-----------|---------|
| Evento | Encontro presencial ou virtual | Ao vivo | Único + memória | TEDx talks |
| Workshop | Sessão de aprendizado coletivo | Presencial/online | Recorrente | Workshop de fermentação |
| Desafio | Atividade com prazo e objetivo | Digital | Dias-semanas | 30-day challenge |
| Kit | Pacote de materiais para ação | Digital/físico | Meses | Kit do embaixador |
| Podcast/Episódio | Conteúdo em áudio | Áudio | Meses-anos | Episódio do manifesto |

### 5. Artefatos de Comunidade

| Artefato | Descrição | Formato | Vida Útil | Exemplo |
|----------|-----------|---------|-----------|---------|
| FAQ | Perguntas frequentes do movimento | Documento | Atualizado | "O que somos" |
| Código de conduta | Regras de convivência | Documento | Anos | CoC da comunidade |
| Guia do membro | Orientação para novos membros | Documento | Meses | Onboarding guide |
| Diretório | Lista de membros e capítulos | Base de dados | Atualizado | Mapa de capítulos |
| Newsletter | Comunicação periódica | Email | Recorrente | Resumo semanal |

## Matriz de Artefatos por Estágio

| Estágio | Artefatos Essenciais | Artefatos Desejáveis |
|---------|---------------------|---------------------|
| Nascente | Manifesto, Slogan, Origem | Logo, FAQ |
| Crescimento | Todos narrativos + Template, Kit | Camiseta, Evento |
| Maduro | Todos os tipos | Diretório, Newsletter, Zine |

## Ciclo de Vida do Artefato

```
CRIAÇÃO → PUBLICAÇÃO → DISTRIBUIÇÃO → ITERAÇÃO → DEPRECIAÇÃO → ARQUIVO
```

## Checklist de Qualidade por Artefato

- [ ] O artefato carrega a tese do movimento?
- [ ] É compartilhável no formato nativo do canal?
- [ ] Reforça a identidade visual e verbal?
- [ ] Tem versão acessível (alt text, legendas)?
- [ ] Está versionado conforme `versioning.md`?

## Integração

- Artefatos narrativos criados com `manifesto-block-component`
- Distribuição via `distribution-channel-component`
- Espalhamento medido pelo `memetic-spread-rubric`
- Artefatos deprecados vão para `archive/`
