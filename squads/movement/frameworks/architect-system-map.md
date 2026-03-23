---
id: architect-system-map
name: "System Map"
squad: movement
type: framework
category: agent-specific
agent: architect
version: "1.0"
tags: [sistema, mapeamento, arquitetura, dependências, architect]
---

# System Map

## Overview

Um movimento é um sistema vivo composto por artefatos, rituais, canais, papéis e loops de feedback. Este framework ensina o Architect a mapear todas as peças do sistema, como elas se conectam, onde estão as dependências e onde estão os pontos de falha. Sem um mapa do sistema, a squad opera no escuro — consertando sintomas em vez de causas.

O mapa não precisa ser bonito. Precisa ser verdadeiro.

## Princípios

1. **Tudo está conectado** — Cada artefato, canal e ritual afeta os outros. Mudar uma peça sem entender as conexões gera consequências imprevistas.

2. **Mapeie o que existe, não o que deveria existir** — O primeiro mapa é descritivo. Só depois vem o prescritivo. Não confunda os dois.

3. **Dependências são vulnerabilidades** — Se o manifesto depende de um único canal e esse canal cai, o movimento perde seu centro. Identifique dependências críticas.

4. **Pontos de falha são prioridade** — O mapa revela onde o sistema é frágil. Esses pontos devem ser reforçados ou ter redundância.

5. **Simplicidade vence** — Um sistema com 50 peças é frágil. Prefira 10 peças bem conectadas. Complexidade deve ser justificada.

6. **Atualização contínua** — O mapa muda toda semana. Se o mapa tem mais de 30 dias sem atualização, está mentindo.

## Protocolo

### Passo 1: Inventariar os Componentes

1. Liste todos os artefatos ativos (manifestos, memes, posts, kits, rituais).
2. Liste todos os canais em uso (redes sociais, email, eventos, comunidades).
3. Liste todos os papéis humanos (equipe, champions, colaboradores, público).
4. Liste todos os loops de feedback (como dados voltam para decisões).
5. Liste todos os gatilhos de ação (o que faz alguém agir no sistema).

### Passo 2: Mapear as Conexões

6. Para cada componente, pergunte: "o que alimenta este componente?" e "o que este componente alimenta?"
7. Desenhe setas de direção: A → B significa "A alimenta B".
8. Identifique conexões bidirecionais: A ↔ B significa "A e B se alimentam mutuamente" (loops).
9. Marque a intensidade: linha grossa = conexão forte, linha fina = conexão fraca.

### Passo 3: Identificar Dependências Críticas

10. Marque com vermelho qualquer componente que, se removido, quebra mais de 2 conexões.
11. Esses são os pontos de falha do sistema.
12. Para cada ponto de falha, pergunte: "existe redundância?" e "qual é o plano B?"

### Passo 4: Identificar Loops

13. Trace todos os loops do sistema (caminhos que voltam ao ponto de partida).
14. Classifique cada loop: reforçador (cresce) ou balanceador (estabiliza).
15. Loops reforçadores são o motor do movimento — proteja-os.
16. Loops balanceadores evitam que o sistema saia de controle — não os elimine.

### Passo 5: Simplificar

17. Remova componentes que não participam de nenhum loop (são desperdício).
18. Elimine conexões redundantes que não agregam valor.
19. Busque o sistema mínimo viável: o menor número de peças que mantém os loops funcionando.

### Passo 6: Documentar e Comunicar

20. Crie uma representação visual em uma página (mapa mental, diagrama de fluxo ou quadro).
21. Adicione legenda com categorias (artefato, canal, papel, loop).
22. Compartilhe com toda a squad e valide: "está faltando algo?"
23. Agende revisão quinzenal do mapa.

## Quando Usar

- No início de qualquer novo movimento, antes de produzir artefatos.
- Quando o movimento parece "travado" e ninguém sabe por quê.
- Após grandes mudanças (novo canal, novo artefato-chave, perda de champion).
- Em onboarding de novos membros da squad para dar visão do todo.

## Quando Não Usar

- Para planejamento diário de conteúdo — use o calendário de atenção.
- Se o movimento ainda está na fase de tese (primeiros 15 dias) — não há sistema para mapear.
- Para análise de métricas — use o modelo de métricas do Impact.

## Integração

- **Chief** usa o mapa para decisões de portfólio e alocação.
- **Phenomenology** alimenta o mapa com dados sobre como o público interage com cada componente.
- **Manifestor** usa o mapa para entender onde novos artefatos se encaixam.
- **Identity** verifica se todos os componentes reforçam a identidade coletiva.
- **Cycle** usa o mapa para planejar sequenciamento de ações.
- **Impact** conecta métricas a cada componente do mapa.

## Exemplo Aplicado

**Contexto:** Movimento #TransparênciaFinanceira de uma fintech, 60 dias de vida.

**Inventário:**
- Artefatos: manifesto, 3 séries de memes, kit de comparação de taxas, ritual #MostraSeuExtrato.
- Canais: Twitter, Instagram, TikTok, newsletter.
- Papéis: equipe (5), champions (18), público ativo (~2.000).
- Loops: meme→compartilhamento→novo seguidor→exposição a manifesto→ação no ritual.

**Mapa de conexões simplificado:**

```
[Manifesto] → [Instagram] → [Público novo]
     ↓                            ↓
[Memes] → [Twitter] → [Compartilhamento] → [Alcance orgânico]
     ↓                            ↓
[Kit Taxas] → [Newsletter] ← [Champions]
     ↓                            ↓
[Ritual #MostraSeuExtrato] → [UGC] → [Prova social] → [Novos champions]
                                                              ↓
                                                    [Loop reforçador ↑]
```

**Pontos de falha identificados:**
1. **Champions** — Se os 18 champions pararem, o UGC despenca. Plano B: programa de incentivo para recrutar 10 novos.
2. **Twitter** — 60% do compartilhamento vem de lá. Se o algoritmo mudar, o loop quebra. Plano B: fortalecer TikTok como canal secundário.
3. **Kit de Taxas** — Depende de dados atualizados. Se ficarem defasados, perde credibilidade. Plano B: automação mensal de atualização.

**Ação imediata:** Criar redundância no canal de distribuição (fortalecer TikTok) e implementar automação de dados para o kit.
