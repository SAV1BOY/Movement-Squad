---
id: signal-taxonomy
name: "Taxonomia de Sinais"
squad: movement
type: taxonomy
category: lib/taxonomies
version: 1.0.0
tags: [taxonomia, sinal, classificação, detecção, linguagem]
---

# Taxonomia de Sinais

## Propósito

Sistema de classificação para os tipos de sinais que indicam tensões, desejos e oportunidades para movimentos. Sinais são a matéria-prima da tese.

## Tipos de Sinal

### 1. Sinais de Linguagem

| Subtipo | Descrição | Exemplo | Onde Encontrar |
|---------|-----------|---------|----------------|
| Neologismo | Novas palavras criadas por um grupo | "Quiet quitting" | Twitter, Reddit |
| Repetição | Mesma frase aparecendo em contextos diferentes | "Estou exausto de..." | Comunidades, SAC |
| Eufemismo | Palavras usadas para evitar o real | "Saí para buscar novos desafios" | LinkedIn |
| Grito de guerra | Frase que mobiliza espontaneamente | "Ninguém solta a mão de ninguém" | Redes sociais |
| Silêncio | Assunto que todos evitam | Salário em entrevistas | Fóruns |

### 2. Sinais de Comportamento

| Subtipo | Descrição | Exemplo | Onde Encontrar |
|---------|-----------|---------|----------------|
| Hack | Solução improvisada pelo usuário | Usar post-it no webcam | Observação direta |
| Migração | Grupo abandonando plataforma/prática | Devs saindo do Twitter | Métricas de plataforma |
| Ritual espontâneo | Comportamento coletivo não planejado | "Sexta de deploy não" | Comunidades |
| Recusa | Pessoas parando de fazer algo aceito | Não responder fora do horário | Tendências de RH |
| Organização | Pessoas se reunindo sem convite | Grupos de WhatsApp temáticos | Redes sociais |

### 3. Sinais de Fricção

| Subtipo | Descrição | Exemplo | Onde Encontrar |
|---------|-----------|---------|----------------|
| Reclamação recorrente | Mesma queixa em múltiplas fontes | "O processo é burocrático demais" | SAC, reviews |
| Abandono | Pessoas desistindo em um ponto específico | Desistência no onboarding | Dados de funil |
| Workaround | Solução alternativa para evitar o processo | Usar planilha em vez do sistema | Uso real |
| Frustração pública | Desabafo em plataformas abertas | Thread reclamando de X | Twitter, Reddit |
| Competição inesperada | Perder clientes para soluções improváveis | Planilha substituindo SaaS | Dados de churn |

### 4. Sinais de Desejo

| Subtipo | Descrição | Exemplo | Onde Encontrar |
|---------|-----------|---------|----------------|
| Pedido repetido | Feature ou mudança pedida insistentemente | "Vocês podiam fazer X" | Feedback, forums |
| Aspiração declarada | O que pessoas dizem querer ser | "Quero ser nômade digital" | Bio de redes |
| Investimento de tempo | Onde pessoas gastam tempo voluntariamente | Horas em side projects | GitHub, comunidades |
| Consumo de conteúdo | Que tipo de conteúdo está crescendo | Vídeos sobre "como largar emprego" | YouTube trends |
| Gasto discricionário | Onde pessoas gastam dinheiro por escolha | Cursos de criatividade | Marketplaces |

### 5. Sinais de Código (Identidade)

| Subtipo | Descrição | Exemplo | Onde Encontrar |
|---------|-----------|---------|----------------|
| Símbolo adotado | Objeto/imagem que grupo usa | Adesivo de laptop | Observação |
| Dress code emergente | Estilo que grupo adota | All-black dos designers | Eventos |
| Bio padronizada | Formato que se repete em perfis | "🚀 Builder | Shipper" | Twitter, LinkedIn |
| Saudação própria | Forma de cumprimento do grupo | "E aí, dev?" | Comunidades |
| Marca como identidade | Produto usado como declaração | Usar Moleskine = "sou criativo" | Observação |

### 6. Sinais de Ausência

| Subtipo | Descrição | Exemplo | Onde Encontrar |
|---------|-----------|---------|----------------|
| Lacuna de mercado | Necessidade sem solução | Mentoria acessível para juniores | Pesquisa |
| Representação ausente | Grupo sem voz em um espaço | Mulheres em painéis de tech | Eventos |
| Conversa inexistente | Tema importante que ninguém aborda | Saúde mental de founders | Mídia |
| Dado que falta | Informação que deveria existir mas não | Salários no Brasil por role | Pesquisas |

## Força do Sinal

| Nível | Critério | Ação |
|-------|----------|------|
| Fraco | Observado 1-2 vezes, fonte única | Monitorar |
| Moderado | Observado 3-5 vezes, múltiplas fontes | Investigar |
| Forte | Observado 6+ vezes, padrão claro | Formular afirmação |
| Convergente | Múltiplos tipos de sinal apontando para mesma tensão | Construir tese |

## Integração

- Sinais alimentam o `signal-to-claim-pattern`
- Afirmações derivadas alimentam o `thesis-component`
- Sinais de código conectam ao `identity-code-component`
- Força avaliada pelo `thesis-strength-rubric`
