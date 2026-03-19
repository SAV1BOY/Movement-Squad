---
id: map-audience-language
name: "Mapear Linguagem Real do Público"
squad: movement
type: task
category: research
agents: [fenomenologo]
frameworks: [phenomenology-language-mapping, phenomenology-rapid-ethnography]
checklists: [fenomenologia/language-and-phrasing-truth, cultural-insight-quality]
templates: [outputs/cultural-insight-report]
registry: [data/registries/identity-codes, data/research/ethnography-notes]
version: "1.0"
tags: [research, linguagem, audiencia, verbatim, etnografia]
---

# Mapear Linguagem Real do Público

## Objetivo

Documentar a linguagem real — palavras, expressões, gírias, metáforas e formas de argumentação — que o público-alvo usa para descrever seus problemas, desejos, frustrações e aspirações, criando um glossário vivo que serve de base para toda comunicação do movimento.

## Contexto

Movimentos culturais autênticos falam a língua do povo, não a língua do marketing. A diferença entre "conteúdo que ressoa" e "conteúdo que parece forçado" está quase sempre na linguagem. Este mapeamento garante que cada peça do movimento use palavras que o público reconhece como suas — não como jargão corporativo traduzido.

## Inputs Necessários

- Definição clara das personas/segmentos do público-alvo
- Acesso a canais onde o público se expressa organicamente
- Signal Cards do ciclo atual de detecção
- Histórico de linguagem mapeada anteriormente
- Dados de SAC, reviews, comentários e DMs (anonimizados)

## Processo

1. **Selecionar fontes orgânicas** — Priorizar espaços onde o público fala sem filtro: reviews de produto, comentários em posts, threads de reclamação, grupos de WhatsApp/Telegram, fóruns, enquetes abertas e entrevistas não-estruturadas.

2. **Coletar verbatims brutos** — Extrair no mínimo 100 verbatims por segmento de público. Copiar ipsis litteris — com erros de digitação, abreviações, emojis e formatação original.

3. **Categorizar por tema** — Organizar verbatims em categorias: (a) Como descrevem o problema, (b) Como descrevem a solução ideal, (c) Como descrevem a concorrência, (d) Como descrevem a identidade do grupo, (e) Expressões emocionais recorrentes.

4. **Identificar padrões linguísticos** — Mapear: palavras mais frequentes, metáforas recorrentes, estruturas frasais típicas, gírias exclusivas do grupo, termos que rejeitam, tom predominante (irônico, revoltado, esperançoso, etc.).

5. **Construir glossário do movimento** — Criar documento com: (a) Palavras que USAMOS (linguagem do público), (b) Palavras que NUNCA usamos (jargão corporativo), (c) Expressões-chave por contexto, (d) Tom de voz por canal.

6. **Mapear espectro emocional** — Identificar as 5-7 emoções dominantes do público e as palavras associadas a cada uma. Criar um mapa emocional que conecte sentimentos a expressões reais.

7. **Testar resonância** — Selecionar 10-15 frases candidatas para comunicação do movimento e testar com amostra do público (poll, A/B em stories, micro-entrevistas) para validar que soam naturais.

8. **Documentar anti-linguagem** — Listar explicitamente termos, expressões e tons que provocam rejeição no público. Incluir exemplos reais de comunicações de marcas que foram criticadas por "soar fake".

9. **Criar banco de frases-semente** — Selecionar os 30-50 verbatims mais poderosos que podem virar base para manifestos, headlines, captions e scripts do movimento.

10. **Atualizar e versionar** — Linguagem é viva. Definir cadência de atualização do glossário e criar sistema de flag para termos que estão perdendo relevância ou ganhando novo significado.

## Outputs Esperados

- **Glossário do Movimento** com termos aprovados e proibidos
- **Banco de verbatims** categorizado (mínimo 100 por segmento)
- **Mapa emocional** com palavras associadas a cada sentimento
- **Anti-linguagem** documentada com exemplos de rejeição
- **Frases-semente** para criação de conteúdo e manifestos

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Verbatims coletados | >= 100 por segmento |
| Fontes orgânicas | >= 8 canais diferentes |
| Categorias mapeadas | Todas as 5 categorias obrigatórias |
| Teste de ressonância | >= 10 frases testadas |
| Anti-linguagem | >= 20 termos documentados |
| Frases-semente | >= 30 selecionadas |

## Decision Points

- **Linguagem muito fragmentada entre segmentos** → Avaliar se o movimento precisa de sub-linguagens por segmento ou unificar em um tom central
- **Linguagem em mutação rápida** → Aumentar cadência de atualização para quinzenal
- **Desconexão entre linguagem do público e thesis** → Sinalizar para revisão de thesis
- **Termos do público colidem com posicionamento da marca** → Escalar para decisão do Arquiteto de Movimento

## Integração

| Tipo | Referência |
|------|-----------|
| **Frameworks** | `frameworks/phenomenology-language-mapping.md`, `frameworks/phenomenology-rapid-ethnography.md` |
| **Checklists** | `checklists/fenomenologia/language-and-phrasing-truth.md`, `checklists/cultural-insight-quality.md` |
| **Templates** | `templates/outputs/cultural-insight-report.md` |
| **Registries** | `data/registries/identity-codes.yaml`, `data/research/ethnography-notes/` |
| **Workflows** | `workflows/00-signal-radar-daily.md` |

### Regras de Fluxo
- **Rework:** Se quality gate reprovar → retornar à Fase 1 (varredura) com fontes ampliadas e reexecutar captura
- **Escalation:** Se bloqueio ou decisão fora de escopo → escalar para Movement Chief
- **Handoff:** Output vai para → tasks de Strategy (craft-movement-thesis, design-identity-system)
