---
id: impact-learning-loop
name: "Learning Loop"
squad: movement
type: framework
category: agent-specific
agent: impact
version: "1.0"
tags: [aprendizado, loop, melhoria-contínua, dados, impact]
---

# Learning Loop

## Overview

Dados sem ação são relatórios. Ação sem dados é chute. O Learning Loop é o meta-framework que transforma dados em insights, insights em ações, ações em playbooks, e playbooks em frameworks atualizados. É o loop de melhoria contínua da squad — como a squad aprende e evolui ao longo do tempo. Sem learning loop, os mesmos erros se repetem. Com ele, cada ciclo é melhor que o anterior.

## Princípios

1. **Dados viram insight, não decoração** — Cada dado coletado deve passar pelo filtro: "isso muda alguma decisão?" Se não muda, não colete.

2. **Insight vira ação, não slide** — Um insight que não gera mudança de comportamento é entretenimento intelectual, não aprendizado.

3. **Ação vira playbook** — Quando uma ação funciona 3 vezes, vira processo. Quando vira processo, é documentada como playbook.

4. **Playbook vira framework** — Quando um playbook é validado repetidamente, ele evolui para framework. Os frameworks deste repositório nasceram de loops anteriores.

5. **Velocidade do loop define velocidade do movimento** — Squads que aprendem rápido vencem squads com mais recursos mas que aprendem devagar.

6. **Transparência alimenta o loop** — Dados, erros e acertos devem ser compartilhados abertamente. Esconder falhas trava o aprendizado coletivo.

## Protocolo

### Passo 1: Coletar Dados (Contínuo)

1. Fontes de dados para o learning loop:
   - **Quantitativos**: métricas do modelo (North Star, inputs, guardrails), resultados de experimentos, cohort analysis, atribuição.
   - **Qualitativos**: feedback de members, observações da squad, notas de campo do Phenomenology, sentiment analysis.
   - **Operacionais**: tempo de produção de artefatos, taxa de cumprimento do calendário, velocidade de decisão.

2. Coletar de forma contínua e organizada. Não esperar o "momento de análise" para começar a registrar.

3. Ferramentas: banco de dados simples (planilha), board de notas (Notion), ou qualquer sistema que a squad já use.

### Passo 2: Transformar Dados em Insight (Semanal)

4. No ritual semanal de leitura de métricas, aplicar as 3 perguntas:

**Pergunta 1: "O que aconteceu?"**
- Descrever o fato objetivo: métrica subiu, caiu, permaneceu.
- Sem interpretação nesse momento.

**Pergunta 2: "Por que aconteceu?"**
- Hipóteses causais: o que pode ter causado essa mudança?
- Triangular com dados qualitativos.
- Marcar nível de confiança: certeza, provável, especulação.

**Pergunta 3: "O que fazemos com isso?"**
- Se o resultado é positivo: como replicar ou amplificar?
- Se negativo: como corrigir ou prevenir?
- Se neutro: precisamos de mais dados ou é irrelevante?

5. O insight é a resposta ao "por que" + "o que fazemos". Documentar em formato:
   - "Descobrimos que [X] porque [Y]. Recomendação: [Z]."

### Passo 3: Transformar Insight em Ação (Semanal)

6. Cada insight relevante deve gerar uma ação concreta:
   - Quem faz? (responsável)
   - O que faz? (ação específica)
   - Até quando? (prazo)
   - Como medimos se funcionou? (métrica)

7. Ações entram no backlog da squad e são priorizadas pelo Chief.
8. Limite: máximo 3 novas ações por semana. Mais que isso, nada é feito direito.

### Passo 4: Transformar Ação em Playbook (Mensal)

9. A cada mês, revisar as ações executadas:
   - Quais funcionaram? (resultado positivo repetido)
   - Quais falharam? (resultado negativo ou neutro)
   - Quais são inconclusivas? (precisam de mais teste)

10. Ações que funcionaram 3+ vezes viram playbook:
    - Título: o que é.
    - Contexto: quando usar.
    - Passos: como executar.
    - Métrica de sucesso: como saber se funcionou.
    - Exemplo: caso real que validou.

11. Playbooks são documentos vivos — atualizados quando novos dados chegam.

### Passo 5: Transformar Playbook em Framework Update (Trimestral)

12. A cada trimestre, revisar todos os playbooks:
    - Quais foram usados repetidamente com sucesso?
    - Quais precisam de ajuste?
    - Quais são candidatos a se tornar frameworks formais?

13. Playbooks maduros são promovidos a frameworks:
    - Estruturados com os campos padrão (Overview, Princípios, Protocolo, etc.).
    - Revisados pelo Chief.
    - Adicionados ao repositório oficial.

14. Frameworks existentes são revisados:
    - Algum framework está desatualizado com base nos novos aprendizados?
    - Algum princípio foi refutado por dados?
    - Algum protocolo precisa de ajuste?

### Passo 6: Compartilhar e Celebrar Aprendizados

15. Criar ritual mensal de "Aprendizado do Mês":
    - A squad seleciona o insight mais valioso do mês.
    - Apresenta brevemente: o que aprendemos, como mudou nosso comportamento.
    - Celebra o aprendizado (positivo ou negativo — aprender com erro é valioso).

16. Manter banco de aprendizados acessível a toda squad:
    - Buscável por tema, data, agente.
    - Cada aprendizado com: insight, ação, resultado, status (validado, refutado, em teste).

17. Compartilhar aprendizados relevantes com stakeholders trimestralmente.

## Quando Usar

- Como processo contínuo da squad (não é pontual).
- Na estruturação de rituais de revisão (semanal, mensal, trimestral).
- Quando a squad sente que "repete os mesmos erros".
- Para onboarding de novos membros ("aqui está o que já aprendemos").

## Quando Não Usar

- Como substituto para análise profunda — este é o processo, não a análise em si.
- Se não há dados mínimos — implemente coleta primeiro.
- Para justificar decisões já tomadas (cherry-picking de dados).

## Integração

- **Chief** prioriza ações derivadas de insights e aprova promoção de playbooks a frameworks.
- **Architect** atualiza o sistema baseado em aprendizados sobre loops e canais.
- **Manifestor** ajusta produção baseado em aprendizados sobre artefatos.
- **Cycle** refina calendário e timing baseado em padrões identificados.
- **Phenomenology** alimenta o loop com dados qualitativos e pesquisa.
- **Identity** evolui narrativa e símbolos baseado em dados de ressonância.

## Exemplo Aplicado

**Contexto:** Learning Loop da squad do movimento #SaúdeSemNeura, trimestre 2.

**Dados coletados no trimestre:**
- 12 semanas de métricas.
- 3 experimentos concluídos.
- 2 análises de cohort.
- 45 notas qualitativas.

**Top 5 insights do trimestre:**

| # | Insight | Ação | Resultado |
|---|---------|------|-----------|
| 1 | Posts com foto imperfeita geram 89% mais UGC | Adotar como padrão | UGC semanal subiu de 35 para 62 |
| 2 | Cohort newsletter retém 3x mais que TikTok | Criar ponte TikTok→newsletter | Taxa de captura subiu 40% |
| 3 | Ritual semanal perde energia após 8 semanas | Introduzir variação temática mensal | Participação estabilizada |
| 4 | Champions inativos por 14+ dias raramente voltam | Criar check-in D10 preventivo | Churn de champions caiu 25% |
| 5 | Memes de humor ácido performam 2x melhor que dados | Aumentar proporção humor/dados | Engajamento médio subiu 35% |

**Playbooks criados:**
- "Foto Imperfeita" — como produzir e incorporar fotos imperfeitas da equipe em posts.
- "Check-in de Champions" — processo de contato proativo com champions silenciosos.

**Framework updates:**
- Meme Factory: adicionado formato "Humor Ácido" como formato principal.
- Ritual Design: adicionada recomendação de variação temática a cada 8 semanas.
- Cohort Analysis: refinada a definição de "ação mágica" com novos dados.

**Aprendizado do Mês (votação da squad):** "A imperfeição é mais poderosa que a perfeição para gerar participação." — Validado por experimento + cohort data + feedback qualitativo.
