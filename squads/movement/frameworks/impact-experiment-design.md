---
id: impact-experiment-design
name: "Experiment Design"
squad: movement
type: framework
category: agent-specific
agent: impact
version: "1.0"
tags: [experimentos, testes, hipóteses, validação, impact]
---

# Experiment Design

## Overview

Movimentos não crescem por intuição. Crescem por experimentação disciplinada. Este framework ensina o agente de Impact a projetar experimentos que testam hipóteses específicas: qual artefato ressoa mais, qual canal converte melhor, qual ritual retém mais. Cada experimento tem hipótese clara, variável controlada, medição definida e protocolo de readout. O objetivo é aprender rápido e decidir com dados.

## Princípios

1. **Hipótese antes de ação** — Não teste sem hipótese. "Vamos ver o que acontece" não é experimento, é loteria.

2. **Uma variável por vez** — Se muda duas coisas ao mesmo tempo, não sabe qual causou o resultado. Isole variáveis.

3. **Mínimo viável** — O menor experimento que gera aprendizado útil. Não precisa de amostra de 10.000 para testar se um formato funciona.

4. **Prazo definido** — Todo experimento tem data de início e fim. Sem prazo, vira projeto eterno.

5. **Resultado negativo é resultado** — Descobrir que algo não funciona é tão valioso quanto descobrir que funciona. Documente ambos.

6. **Readout obrigatório** — Todo experimento termina com readout formal. Sem readout, o aprendizado se perde.

## Protocolo

### Passo 1: Formular a Hipótese

1. Use o formato: "Se [fizermos X], então [Y acontecerá], porque [Z é a razão]."
   - X = a ação/variável que vamos testar.
   - Y = o resultado esperado e mensurável.
   - Z = o racional por trás da expectativa.

2. Exemplos:
   - "Se publicarmos memes em formato carrossel em vez de imagem única, o share rate aumentará em 20%, porque carrosséis incentivam swipe e geram mais tempo de atenção."
   - "Se adicionarmos reconhecimento público aos champions, a taxa de UGC aumentará em 30%, porque reconhecimento social é o principal motivador desse grupo."

3. Hipótese deve ser falsificável — se não há como provar que está errada, não é hipótese.

### Passo 2: Definir o Experimento

4. Para cada hipótese, definir:

| Elemento | Descrição |
|----------|-----------|
| Hipótese | Frase no formato Se/Então/Porque |
| Variável | O que estamos mudando (ex: formato do meme) |
| Controle | O que mantemos igual (ex: mesmo conteúdo, mesmo horário) |
| Métrica primária | O que estamos medindo (ex: share rate) |
| Métrica secundária | Efeito colateral a observar (ex: sentiment) |
| Amostra | Quantas pessoas/posts/dias |
| Duração | Início e fim do experimento |
| Critério de sucesso | Qual número confirma a hipótese |
| Critério de falha | Qual número refuta a hipótese |

### Passo 3: Dimensionar o Experimento

5. **Micro-experimento (1-3 dias):** Testa formato, texto, visual.
   - Amostra: 2-5 posts comparativos.
   - Decisão: qual formato performa melhor.

6. **Experimento padrão (1-2 semanas):** Testa canal, ritual, abordagem.
   - Amostra: 7-14 dias de dados comparativos.
   - Decisão: escalar ou descartar a abordagem.

7. **Experimento estratégico (30-60 dias):** Testa tese, público, modelo.
   - Amostra: ciclo completo de um movimento ou sub-movimento.
   - Decisão: pivotar, escalar ou encerrar.

8. Escolha o menor tamanho que gera confiança suficiente na decisão.

### Passo 4: Executar com Disciplina

9. Durante o experimento:
   - Não mude outras variáveis simultaneamente.
   - Registre anomalias (evento externo que pode ter influenciado).
   - Colete dados conforme o plano (não pule dias).
   - Resista à tentação de concluir antes do prazo (viés de confirmação).

10. Se algo inesperado acontece (crise, viral externo), registre como anomalia e considere estender o experimento.

### Passo 5: Readout

11. Ao final do período, produzir readout com:
    - Hipótese original.
    - Dados coletados (tabela ou gráfico simples).
    - Resultado: confirmada, refutada ou inconclusiva.
    - Anomalias observadas.
    - Aprendizado principal (1-2 frases).
    - Recomendação de ação: escalar, descartar, testar novamente com ajuste.

12. Apresentar na reunião semanal da squad.
13. Arquivar o readout em banco de aprendizados para referência futura.

### Passo 6: Agir sobre o Resultado

14. Se hipótese confirmada:
    - Implementar a mudança como padrão.
    - Comunicar à squad.
    - Registrar no playbook do movimento.

15. Se hipótese refutada:
    - Documentar o aprendizado.
    - Verificar se a hipótese estava errada ou se a execução teve problemas.
    - Decidir: testar variação ou abandonar a linha.

16. Se inconclusivo:
    - Estender o experimento ou aumentar a amostra.
    - Se inconclusivo pela segunda vez, tratar como refutado.

## Quando Usar

- Antes de qualquer mudança significativa no movimento.
- Quando a squad diverge sobre qual abordagem é melhor.
- Para otimizar artefatos, canais, rituais e processos existentes.
- Para validar insights qualitativos com dados quantitativos.

## Quando Não Usar

- Para decisões urgentes que não permitem esperar dados.
- Se a amostra é muito pequena para qualquer conclusão (menos de 100 impressões).
- Para questões que já foram testadas recentemente com resultado claro.

## Integração

- **Chief** prioriza quais experimentos rodar (nem tudo pode ser testado ao mesmo tempo).
- **Manifestor** produz as variações necessárias para os testes.
- **Architect** garante que o experimento não quebra loops existentes.
- **Cycle** aloca espaço no calendário para os experimentos.
- **Phenomenology** formula hipóteses baseadas em insights qualitativos.
- **Identity** verifica que variações experimentais não comprometem a narrativa.

## Exemplo Aplicado

**Contexto:** Experimento para o movimento #CozinhaSemReceita.

**Hipótese:** "Se incluirmos foto do prato 'imperfeito' da equipe junto com o meme de provocação, a taxa de UGC aumentará em 25%, porque normalizar imperfeição reduz a barreira de participação."

**Design:**

| Elemento | Detalhe |
|----------|---------|
| Variável | Adicionar foto imperfeita ao post |
| Controle | Mesmo conteúdo, mesmo horário, mesmo canal |
| Métrica primária | Posts com #CozinhaSemReceita em 7 dias |
| Métrica secundária | Sentiment dos comentários |
| Amostra | 2 semanas (1 com, 1 sem, alternando) |
| Critério de sucesso | +25% de UGC na semana com foto imperfeita |
| Critério de falha | Sem diferença ou diferença < 10% |

**Resultado:**
- Semana com foto imperfeita: 34 UGCs.
- Semana sem: 18 UGCs.
- Diferença: +89%. Hipótese confirmada com margem.
- Anomalia: nenhuma relevante.

**Readout:** "Normalizar imperfeição quase dobra a participação. A barreira principal para UGC era medo de julgamento estético, não falta de interesse."

**Ação:** Implementar como padrão. Toda semana, pelo menos 1 post inclui foto imperfeita da equipe. Criar sub-ritual "Prato Feio Bonito" mensal.
