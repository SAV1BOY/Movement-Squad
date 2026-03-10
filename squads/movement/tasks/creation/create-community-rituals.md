---
id: create-community-rituals
name: "Criar Rituais Comunitários (Semanal e Mensal)"
squad: movement
type: task
category: creation
agents: [community-builder, manifestador-criativo]
frameworks: [community-ritual-framework, engagement-cadence-model]
checklists: [ritual-execution-checklist, community-event-checklist]
templates: [weekly-ritual-template, monthly-ritual-template]
version: "1.0"
tags: [creation, rituais, comunidade, semanal, mensal, engajamento]
---

# Criar Rituais Comunitários (Semanal e Mensal)

## Objetivo

Desenvolver e implementar rituais comunitários recorrentes — semanais e mensais — que criem ritmo, expectativa e hábito na comunidade, mantendo o engajamento vivo e dando aos membros momentos regulares de conexão e pertencimento.

## Contexto

Comunidades morrem de silêncio, não de conflito. Rituais recorrentes são o batimento cardíaco — garantem que sempre há algo acontecendo, que membros têm motivo para voltar e que o momentum nunca para completamente. Sem ritmo, até a comunidade mais engajada perde energia.

## Inputs Necessários

- Rituais base desenhados no task `design-rituals`
- Community Structure e papéis definidos
- Platform Briefs para espaços comunitários
- Calendário do movimento e do setor
- Feedback de membros sobre preferências de formato e horário
- Champions disponíveis para facilitar

## Processo

1. **Definir rituais semanais** — Criar 2-3 rituais semanais fixos: (a) Ritual de abertura da semana (segunda — intenção/foco coletivo), (b) Ritual de meio de semana (quarta — troca/aprendizado), (c) Ritual de fechamento (sexta — celebração/review).

2. **Definir rituais mensais** — Criar 1-2 rituais mensais: (a) Encontro mensal da comunidade (live, AMA, painel), (b) Celebração de marcos (reconhecimento de membros, milestones do movimento).

3. **Detalhar formato de cada ritual semanal** — Para cada um: duração (15-30min máx para semanais), plataforma, formato (texto, áudio, vídeo, live), estrutura (abertura 2min, core 15min, fechamento 3min), facilitador.

4. **Detalhar formato de cada ritual mensal** — Para cada um: duração (45-90min), plataforma, formato, agenda detalhada, convidados especiais, material de preparação para participantes.

5. **Criar templates recorrentes** — Para cada ritual, produzir: post de convocação (template), roteiro para facilitador, template de registro/resumo pós-ritual, assets visuais padrão.

6. **Definir temas rotativos** — Criar banco de 12-20 temas que rodam nos rituais semanais: desafios do setor, histórias de membros, debates de valores, análise de tendências, co-criação de ideias.

7. **Treinar facilitadores** — Capacitar 3-5 champions para facilitar rituais: técnicas de moderação, como manter energia, como lidar com silêncio, como incluir tímidos, como encerrar no horário.

8. **Criar sistema de registro** — Definir como cada ritual é documentado: resumo textual, highlights, quotes memoráveis, decisões tomadas, próximos passos. Publicar resumo para quem não participou.

9. **Testar cadência por 4 semanas** — Rodar os rituais por 1 mês e medir: taxa de participação, satisfação (quick poll), retenção semana a semana, feedback qualitativo.

10. **Ajustar e estabilizar** — Com base nos dados de 4 semanas, ajustar: horários, duração, formatos, temas. Depois de ajustado, publicar calendário permanente e comunicar à comunidade.

## Outputs Esperados

- **Rituais semanais** definidos e testados (2-3)
- **Rituais mensais** definidos e testados (1-2)
- **Templates recorrentes** prontos para uso
- **Banco de temas** com 12-20 opções
- **Facilitadores treinados** (3-5 champions)
- **Calendário permanente** publicado
- **Resultados do teste** de 4 semanas

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Rituais semanais | >= 2 implementados |
| Rituais mensais | >= 1 implementado |
| Participação semanal | >= 15% da comunidade ativa |
| Participação mensal | >= 25% da comunidade ativa |
| Facilitadores treinados | >= 3 |
| Teste de 4 semanas | Completo com dados |
| Satisfação | >= 7/10 média |

## Decision Points

- **Participação caindo** → Ajustar horário, formato ou reduzir frequência antes de cancelar
- **Participação crescendo** → Avaliar se escalar formato ou criar sub-rituais por tema
- **Facilitadores cansados** → Ampliar pool de facilitadores e implementar rotação
- **Comunidade pedindo outros rituais** → Avaliar viabilidade e testar em formato piloto

## Integração

- **Alimenta:** `activate-community`, `measure-community-health`
- **Recebe de:** `design-rituals`, `design-community-structure`, `create-champion-program`
- **Workflow relacionado:** `08-community-build-and-nurture`, `05-ralphloop-kaizen-weekly`
- **Cadência:** Semanal (execução) + mensal (execução) + trimestral (revisão de formato)
- **Handoff:** Templates e calendário vão para community managers e champions facilitadores
