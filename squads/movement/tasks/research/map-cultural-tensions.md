---
id: map-cultural-tensions
name: "Mapear Tensões Culturais do Setor"
squad: movement
type: task
category: research
agents: [fenomenologo, identitario]
frameworks: [tension-to-movement-framework, phenomenology-counter-narrative]
checklists: [fenomenologia/tension-mapping, fenomenologia/counter-signal-capture]
templates: [outputs/cultural-insight-report]
registry: [data/research/signals, data/registries/movement-theses]
version: "1.0"
tags: [research, tensoes, cultura, setor, polaridades]
---

# Mapear Tensões Culturais do Setor

## Objetivo

Identificar e documentar as tensões culturais ativas no setor de atuação — contradições, polaridades e conflitos de valores que criam energia emocional e podem ser canalizados pelo movimento como combustível narrativo.

## Contexto

Toda cultura vive em tensão. Movimentos poderosos não inventam tensões — eles nomeiam as que já existem e escolhem um lado. A tensão entre "o que é" e "o que deveria ser" é o motor emocional de qualquer movimento. Sem tensão real, não há urgência. Sem urgência, não há adesão.

## Inputs Necessários

- Signal Cards e Signal Reports recentes
- Mapa de linguagem do público atualizado
- Análise de concorrentes e seus posicionamentos
- Dados de mercado e mudanças regulatórias
- Matérias jornalísticas e editoriais sobre o setor

## Processo

1. **Levantar tensões candidatas** — A partir dos sinais culturais e da escuta do público, listar todas as contradições percebidas. Exemplos de formatos: "X vs Y", "Promessa vs Realidade", "Antes vs Agora", "O que dizem vs O que fazem".

2. **Classificar por tipo** — Categorizar cada tensão: (a) Tensão estrutural (do setor/mercado), (b) Tensão geracional (entre gerações), (c) Tensão de valores (ética vs prática), (d) Tensão estética (velho vs novo), (e) Tensão de poder (quem controla vs quem é controlado).

3. **Validar com evidências** — Para cada tensão, reunir no mínimo 3 evidências concretas: verbatims do público, dados de mercado, matérias jornalísticas, exemplos de comportamento observável.

4. **Medir intensidade emocional** — Avaliar cada tensão em escala 1-5 para: (a) Carga emocional (quanto incomoda/mobiliza), (b) Abrangência (quantas pessoas sentem), (c) Urgência percebida (quão imediata parece), (d) Potencial narrativo (quão bem se conta como história).

5. **Mapear posições existentes** — Para cada tensão, documentar: quem já se posicionou, de que lado, com qual narrativa. Identificar espaços narrativos vazios — lados da tensão que ninguém articulou ainda.

6. **Avaliar autenticidade de conexão** — Para cada tensão, responder: "O movimento/marca tem legitimidade para falar sobre isso?" Pontuar de 1-5 a autenticidade da conexão baseado em: histórico da marca, produto/serviço oferecido, público atual.

7. **Priorizar tensões estratégicas** — Selecionar as 3-5 tensões com maior score combinado de: intensidade emocional + espaço narrativo vazio + autenticidade de conexão.

8. **Formular polaridades acionáveis** — Traduzir cada tensão priorizada em uma polaridade clara: "Nós acreditamos em X. O mundo insiste em Y. Isso precisa mudar." Esse formato alimenta diretamente a thesis do movimento.

9. **Criar Tension Map visual** — Montar mapa visual com: tensões priorizadas no centro, evidências ao redor, posições de concorrentes marcadas, espaços vazios destacados.

10. **Documentar e distribuir** — Compilar tudo no Tension Report e distribuir para o squad como insumo para thesis e criação.

## Outputs Esperados

- **Tension Cards** preenchidos (mínimo 10 tensões mapeadas)
- **Tension Map** visual com priorizações
- **Polaridades acionáveis** formuladas (3-5 priorizadas)
- **Tension Report** consolidado com evidências e recomendações
- **Espaços narrativos vazios** identificados

## Quality Gate

| Critério | Mínimo Aceitável |
|----------|-----------------|
| Tensões identificadas | >= 10 candidatas |
| Evidências por tensão | >= 3 por tensão priorizada |
| Tipologias representadas | >= 3 tipos diferentes |
| Score de autenticidade | >= 3/5 para tensões priorizadas |
| Espaços vazios mapeados | >= 2 identificados |

## Decision Points

- **Tensão com alta intensidade + alta autenticidade** → Priorizar como eixo central da thesis
- **Tensão com alta intensidade + baixa autenticidade** → Monitorar mas não usar diretamente — risco de ser visto como oportunista
- **Tensão em declínio** → Remover do mapa ativo e arquivar
- **Nova tensão emergente com velocidade alta** → Avaliar em sessão emergencial se justifica pivot de narrativa

## Integração

| Tipo | Referência |
|------|-----------|
| **Frameworks** | `frameworks/tension-to-movement-framework.md`, `frameworks/phenomenology-counter-narrative.md` |
| **Checklists** | `checklists/fenomenologia/tension-mapping.md`, `checklists/fenomenologia/counter-signal-capture.md` |
| **Templates** | `templates/outputs/cultural-insight-report.md` |
| **Registries** | `data/research/signals/`, `data/registries/movement-theses.yaml` |
| **Workflows** | `workflows/00-signal-radar-daily.md` |

### Regras de Fluxo
- **Rework:** Se quality gate reprovar → retornar à Fase 1 (varredura) com fontes ampliadas e reexecutar captura
- **Escalation:** Se bloqueio ou decisão fora de escopo → escalar para Movement Chief
- **Handoff:** Output vai para → tasks de Strategy (craft-movement-thesis, design-identity-system)
