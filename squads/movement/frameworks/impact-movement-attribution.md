---
id: impact-movement-attribution
name: "Movement Attribution"
squad: movement
type: framework
category: agent-specific
agent: impact
version: "1.0"
tags: [atribuição, negócio, impacto, honestidade, impact]
---

# Movement Attribution

## Overview

A pergunta mais difícil para qualquer squad de movimento é: "quanto desse resultado de negócio veio do movimento?" Este framework ensina o agente de Impact a atribuir impacto de movimento para negócio com honestidade radical. Define três tipos de atribuição — direta (rastreada), influenciada (correlacionada) e halo (não rastreável) — e estabelece regras para nunca sobreclamar.

Sobreclamar destrói credibilidade. Subclamar desperdiça oportunidade. O caminho é honestidade com sofisticação.

## Princípios

1. **Honestidade radical** — Nunca atribua ao movimento mais do que você pode provar. Apresente sempre com os limites claros.

2. **Três níveis, três confianças** — Atribuição direta (alta confiança), influenciada (média confiança), halo (baixa confiança). Sempre declare o nível.

3. **Correlação não é causação** — Se as vendas subiram no mesmo mês que o movimento cresceu, isso é correlação. Não é prova de que o movimento causou as vendas.

4. **Incremental é o que importa** — A pergunta não é "quanto vendemos?", é "quanto vendemos A MAIS por causa do movimento?"

5. **Modelo imperfeito é melhor que nenhum modelo** — Atribuição perfeita não existe. Um modelo 70% preciso ainda é melhor que 0%.

6. **Educação dos stakeholders** — Parte do trabalho é ensinar stakeholders sobre os limites da atribuição. Se eles esperam precisão absoluta, a conversa precisa ser calibrada antes dos números.

## Protocolo

### Passo 1: Definir os Três Níveis de Atribuição

1. **Atribuição Direta (alta confiança):**
   - A pessoa veio do movimento E converteu de forma rastreável.
   - Exemplos: usou código do movimento, clicou em UTM do movimento, se cadastrou via link exclusivo.
   - Prova: tracking end-to-end.
   - Confiança: 80-95%.

2. **Atribuição Influenciada (média confiança):**
   - A pessoa teve contato com o movimento antes de converter, mas a conversão não é diretamente rastreável.
   - Exemplos: seguiu o perfil do movimento, interagiu com conteúdo, participou de ritual, e depois converteu por outro canal.
   - Prova: correlação temporal + sobreposição de audiência.
   - Confiança: 40-70%.

3. **Atribuição Halo (baixa confiança):**
   - O movimento gera benefícios indiretos que não são rastreáveis mas são reais.
   - Exemplos: brand awareness, preferência de marca, word-of-mouth, cobertura de mídia espontânea.
   - Prova: pesquisa de brand tracking, NPS, menções orgânicas.
   - Confiança: 10-40%.

### Passo 2: Implementar Tracking para Atribuição Direta

4. Mínimo viável de tracking:
   - **Códigos exclusivos**: código promocional do movimento (ex: TRANSPARENCIA20).
   - **UTMs**: parâmetros de URL em todo link do movimento.
   - **Landing pages dedicadas**: página de conversão exclusiva do movimento.
   - **Pixel de retargeting**: para rastrear visitantes do conteúdo do movimento que convertem depois.

5. Registrar toda conversão com source=movimento em dashboard separado.

### Passo 3: Estimar Atribuição Influenciada

6. Métodos de estimativa:
   - **Análise de sobreposição**: quantos convertidos tiveram interação com conteúdo do movimento nos 30 dias anteriores à conversão?
   - **Uplift por região/canal**: se o movimento é forte em um canal e fraco em outro, comparar taxas de conversão entre eles.
   - **Pesquisa pós-conversão**: perguntar "como você nos conheceu?" e incluir opções relacionadas ao movimento.

7. Fórmula simplificada para influenciados:
   ```
   Influenciados = (Convertidos com exposição ao movimento) - (Taxa de conversão base x Expostos)
   ```
   O excedente é o efeito incremental do movimento.

### Passo 4: Estimar Atribuição Halo

8. Métodos de estimativa:
   - **Brand tracking trimestral**: awareness, consideração e preferência entre público exposto vs. não exposto.
   - **NPS segmentado**: NPS de clientes que são membros do movimento vs. clientes que não são.
   - **Share of voice**: menções orgânicas da marca relacionadas ao tema do movimento.
   - **Média ponderada**: se não há dados sofisticados, estimar como 10-20% da atribuição direta.

9. Sempre apresentar halo com caveats: "Estimativa com baixa confiança. Baseada em [método]. Pode ser superestimada ou subestimada."

### Passo 5: Montar o Relatório de Atribuição

10. Formato do relatório:

**Resumo executivo:**
- Total de conversões atribuídas ao movimento: X.
- Receita atribuída: R$ Y.
- Custo do movimento no período: R$ Z.
- ROI: Y/Z.

**Detalhamento por nível:**

| Nível | Conversões | Receita | Confiança |
|-------|-----------|---------|-----------|
| Direta | X1 | R$ Y1 | Alta |
| Influenciada | X2 | R$ Y2 | Média |
| Halo | X3 | R$ Y3 | Baixa |
| **Total** | **X** | **R$ Y** | **Mista** |

**Nota de honestidade:**
"Os números de atribuição direta são rastreados. Os de influenciada são estimados com [método]. Os de halo são inferidos com [método]. O valor real provavelmente está entre [range inferior] e [range superior]."

### Passo 6: Comparar com Benchmarks

11. Comparar custo de aquisição via movimento com outros canais:
    - CAC movimento vs. CAC paid ads vs. CAC orgânico.
    - LTV de clientes do movimento vs. clientes de outros canais.
    - Retenção de clientes do movimento vs. outros canais.

12. Se o CAC do movimento é menor E o LTV é maior, o argumento é forte. Se não, entender por que e otimizar.

## Quando Usar

- A partir do dia 60 do movimento (antes disso, foco em ressonância, não em conversão).
- Em reuniões mensais de resultado com stakeholders.
- Para justificar investimento contínuo no movimento.
- Para calibrar expectativas da liderança.

## Quando Não Usar

- Na fase de tese/ressonância (0-30 dias) — cedo demais para atribuição.
- Se não há tracking mínimo implementado — implemente primeiro.
- Para provar causação absoluta — não existe, e prometer isso é desonesto.

## Integração

- **Chief** usa o relatório para decisões de investimento e justificativa ao board.
- **Architect** implementa os tracking points no sistema.
- **Manifestor** otimiza artefatos que geram conversão direta.
- **Cycle** alinha momentos de conversão com o calendário.
- **Phenomenology** pesquisa qualitativamente a jornada do membro até a conversão.
- **Identity** garante que a conexão movimento→negócio não compromete a autenticidade.

## Exemplo Aplicado

**Contexto:** Atribuição trimestral do movimento #ExijaClareza para a fintech.

**Relatório Q1/2026:**

| Nível | Conversões (downloads do app) | Receita estimada | Confiança |
|-------|-------------------------------|-----------------|-----------|
| Direta (código CLAREZA) | 1.200 | R$ 180.000 | Alta |
| Influenciada (sobreposição) | 800 | R$ 120.000 | Média |
| Halo (brand tracking) | ~500 | ~R$ 75.000 | Baixa |
| **Total** | **~2.500** | **~R$ 375.000** | **Mista** |

**Custo do movimento no Q1:** R$ 85.000 (equipe + ferramentas + ads mínimos).
**ROI conservador (só direto):** 2.1x.
**ROI otimista (direta + influenciada):** 3.5x.
**ROI máximo (incluindo halo):** 4.4x.

**Apresentação ao board:** "Com alta confiança, o movimento gerou R$180K em receita com investimento de R$85K — ROI de 2.1x. A estimativa real é provavelmente entre 2.1x e 3.5x. O halo existe mas não podemos quantificar com precisão."

**Comparação:** CAC via movimento: R$34. CAC via paid ads: R$52. LTV de membros do movimento: 1.8x maior que clientes de ads.
