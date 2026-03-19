---
id: create-memetic-assets
name: "Criar Assets Meméticos e Variações"
squad: movement
type: task
category: creation
agents: [manifestador, identitario]
frameworks: [manifestor-meme-factory, memetic-variation-selection, cycle-cultural-wave-surfing]
checklists: [memetic-asset-quality, memetics/memetic-fidelity, memetics/meme-variation-and-selection, memetics/format-platform-fit]
templates: [outputs/meme-variation-set]
registry: [data/registries/memetic-assets]
version: "1.0"
tags: [creation, memes, assets, viral, cultura, artefatos]
---

# Criar Assets Meméticos e Variações

## Objetivo

Produzir artefatos meméticos — memes, formatos compartilháveis, imagens de impacto, vídeos curtos e templates remixáveis — que carreguem a mensagem do movimento de forma que as pessoas queiram espalhar espontaneamente.

## Contexto

Memes não são piadas com fotos. São unidades de cultura que se replicam. Um meme de movimento é um pedaço de identidade que as pessoas compartilham porque expressa algo que sentem mas não sabiam articular. O objetivo não é viralizar — é criar artefatos tão verdadeiros que se tornam inevitavelmente compartilhados.

## Inputs Necessários

- Manifesto e slogans aprovados
- Identity System (códigos visuais e verbais)
- Platform Briefs com formatos nativos por plataforma
- Glossário de linguagem do público
- Banco de referências de memes e formatos virais do nicho
- Trend Radar com estéticas e formatos em alta

## Processo

1. **Mapear formatos meméticos do nicho** — Catalogar os formatos de meme que o público-alvo já consome e compartilha. Não inventar formatos novos sem dominar os existentes.

2. **Identificar verdades compartilháveis** — Extrair da thesis e do manifesto 15-20 "verdades" que provocam reação imediata: "isso é muito real", "é exatamente isso", "finalmente alguém disse". Cada verdade é a base de um meme.

3. **Criar matrix de conteúdo** — Cruzar verdades compartilháveis x formatos meméticos x plataformas. Cada célula da matrix é um asset potencial. Priorizar as combinações com maior potencial.

4. **Produzir primeira leva** — Criar 20-30 assets variados: memes estáticos, carrosséis, vídeos curtos (15-30seg), stories templates, wallpapers, stickers, GIFs. Usar linguagem real do público.

5. **Criar templates remixáveis** — Para os formatos de maior potencial, criar versões template que membros da comunidade possam personalizar e repostar: frames, backgrounds, sticker packs, filtros.

6. **Aplicar testes de ressonância** — Para cada asset, aplicar: (a) Teste do screenshot: alguém tiraria print? (b) Teste do envio: alguém mandaria no grupo de amigos? (c) Teste do repost: alguém colocaria no próprio perfil?

7. **Adaptar por plataforma** — Para cada asset aprovado, criar adaptações nativas: dimensões corretas, formato ideal (carrossel no IG, duet-bait no TikTok, quote no X, infográfico no LinkedIn).

8. **Criar sistema de variações** — Para os top 5 assets, criar 3-5 variações cada: mudando copy, mudando visual, mudando formato, adaptando para contextos diferentes. Volume é essencial para testar.

9. **Organizar biblioteca de assets** — Estruturar pasta compartilhada com: assets finalizados organizados por tema/formato/plataforma, templates editáveis, guidelines de uso, tracking de performance.

10. **Planejar cadência de publicação** — Definir quais assets vão quando, em qual canal, com qual sequência narrativa. Não publicar tudo de uma vez.

## Outputs Esperados

- **Assets meméticos** produzidos (mínimo 20-30 por ciclo)
- **Templates remixáveis** para comunidade (mínimo 5)
- **Adaptações por plataforma** para todos os assets
- **Biblioteca organizada** e acessível ao squad
- **Cadência de publicação** planejada

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Assets produzidos | >= 20 por ciclo |
| Formatos variados | >= 4 formatos diferentes |
| Templates remixáveis | >= 5 |
| Teste de ressonância | 100% dos assets testados |
| Adaptação por plataforma | >= 3 plataformas |
| Linguagem do público | 100% usando glossário |

## Decision Points

- **Asset viral inesperado** → Criar variações imediatamente e amplificar
- **Assets sem engajamento** → Analisar se é problema de conteúdo, formato ou distribuição
- **Comunidade remixando espontaneamente** → Amplificar os remixes e reconhecer criadores
- **Asset gerando controvérsia** → Avaliar se é polarização saudável ou backlash — agir conforme protocolo

## Integração

| Tipo | Referência |
|------|-----------|
| **Frameworks** | `frameworks/manifestor-meme-factory.md`, `frameworks/memetic-variation-selection.md`, `frameworks/cycle-cultural-wave-surfing.md` |
| **Checklists** | `checklists/memetic-asset-quality.md`, `checklists/memetics/memetic-fidelity.md`, `checklists/memetics/meme-variation-and-selection.md`, `checklists/memetics/format-platform-fit.md` |
| **Templates** | `templates/outputs/meme-variation-set.md` |
| **Registries** | `data/registries/memetic-assets/` |
| **Workflows** | `workflows/02-artifact-foundry.md` |

### Regras de Fluxo
- **Rework:** Se quality gate reprovar → revisar com feedback específico do quality gate, iterar o artefato e resubmeter
- **Escalation:** Se bloqueio ou decisão fora de escopo → escalar para Movement Chief
- **Handoff:** Output vai para → tasks de Activation (launch-activation, activate-community)
