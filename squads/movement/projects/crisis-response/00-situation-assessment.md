---
id: cr-00
name: Avaliação da Situação
squad: movement
type: project-phase
category: crisis-response
phase: 0-assessment
tags:
  - crise
  - avaliação
  - diagnóstico
  - urgência
---

# 00 · Avaliação da Situação

## Objetivo da Fase

Avaliar rapidamente a natureza, gravidade e escopo da crise que afeta o movimento.
Velocidade importa, mas diagnóstico errado leva a resposta errada. Esta fase deve
ser concluída em no máximo 24 horas — idealmente em 4-6 horas para crises agudas.

## Inputs

- Sinal(is) que disparou(aram) a crise
- Dados de sentimento e menções em tempo real
- Feedback da comunidade e stakeholders
- Contexto do movimento (saúde, narrativa, comunidade)
- Histórico de crises anteriores (se houver)
- Time de resposta disponível e seus papéis

## Processo

1. **Triagem Inicial (1ª hora)** — Classificar a crise em:
   - **Nível 1 — Ruído:** Menção negativa isolada, sem tração
   - **Nível 2 — Incidente:** Problema real, tração moderada
   - **Nível 3 — Crise:** Ameaça significativa ao movimento
   - **Nível 4 — Emergência:** Risco existencial, resposta imediata

2. **Mapeamento de Fatos** — Separar fatos confirmados de rumores e
   especulações. Para cada fato: fonte, data, verificação. Para cada
   rumor: origem provável, probabilidade de ser verdadeiro.

3. **Análise de Stakeholders Afetados** — Quem está sendo impactado?
   Comunidade, marca, parceiros, público geral? Mapear cada grupo
   com nível de impacto e expectativa de resposta.

4. **Monitoramento de Velocidade** — A crise está acelerando ou
   desacelerando? Monitorar volume de menções, sentimento, alcance
   e engajamento com o tema. Usar `sentiment-analysis-skeleton.md`.

5. **Análise de Cenários** — Projetar 3 cenários: melhor caso (resolve
   naturalmente), caso provável (requer ação), pior caso (escalada).
   Para cada cenário: probabilidade, impacto, timeline.

6. **Identificação da Causa-Raiz** — Qual é a causa real da crise?
   Pode ser: erro do time, problema de produto/serviço, mudança de
   contexto externo, ataque coordenado, mal-entendido, problema
   legítimo da comunidade.

7. **Definição de Prioridades** — O que precisa ser resolvido AGORA
   vs. o que pode esperar? Listar ações imediatas (< 4h), curto prazo
   (< 24h) e médio prazo (< 1 semana).

8. **Briefing para Stakeholders** — Preparar briefing conciso para
   stakeholders com: o que aconteceu, gravidade, impacto, cenários,
   recomendação de próximo passo. Máximo 1 página.

## Outputs

- [ ] Classificação de nível da crise (1-4)
- [ ] Mapa de fatos vs. rumores
- [ ] Mapa de stakeholders afetados com impacto
- [ ] Análise de velocidade e tendência
- [ ] 3 cenários com probabilidades
- [ ] Causa-raiz identificada (ou hipóteses)
- [ ] Lista de prioridades (imediato/curto/médio prazo)
- [ ] Briefing para stakeholders

## Quality Gate

| Critério                          | Mínimo Aceitável                         |
|-----------------------------------|------------------------------------------|
| Tempo de avaliação                | < 24h (< 6h para nível 3-4)             |
| Fatos verificados                 | Separação clara fato vs. rumor           |
| Nível classificado                | Com critérios documentados               |
| Stakeholders mapeados             | Todos os grupos impactados listados      |
| Causa-raiz                        | Identificada ou hipóteses priorizadas    |
| Briefing pronto                   | Conciso e acionável                      |

## Próxima Fase

→ `01-response-strategy.md` — Com diagnóstico claro, definir estratégia
de resposta adequada ao nível e natureza da crise.

### Erros Críticos em Avaliação de Crise

- Minimizar a gravidade por desejo de que "passe sozinha"
- Reagir ao rumor sem verificar fatos
- Demorar demais na avaliação enquanto a crise escala
- Avaliar sozinho sem consultar quem está mais perto do problema
- Confundir volume de menções com gravidade real

### Protocolo de Ativação por Nível

- **Nível 1:** Monitorar. Responsável: community manager
- **Nível 2:** Resposta coordenada. Ativar: lead + community manager
- **Nível 3:** War room. Ativar: time completo + stakeholders
- **Nível 4:** All-hands. Ativar: liderança + jurídico + comunicação
