---
id: cross-squad-handoff-protocol
name: "Protocolo de Handoff Cross-Squad"
squad: movement
type: doc
category: docs
version: 1.0.0
tags: [handoff, cross-squad, protocolo, transição, qualidade]
---

# Protocolo de Handoff Cross-Squad

## Visão Geral

O protocolo de handoff cross-squad define como transições de trabalho entre squads
devem ser conduzidas. Handoffs são o momento de maior risco operacional — é onde
contexto se perde, qualidade cai e prazos estouram. Este protocolo padroniza o
processo para que toda transição seja rastreável, avaliável e melhorável.

## Tipos de Handoff

| Tipo | Descrição | Exemplo | Complexidade |
|------|-----------|---------|-------------|
| Artefato | Entrega de conteúdo, pesquisa ou template | Pesquisa cultural → squad de criação | Média |
| Estratégia | Entrega de direcionamento estratégico | Tese validada → squad de execução | Alta |
| Dados | Entrega de dataset ou análise | Métricas consolidadas → squad de decisão | Média |
| Projeto | Transferência de ownership de projeto inteiro | Movimento maduro → squad de escala | Muito alta |
| Suporte | Pedido de apoio pontual entre squads | Revisão jurídica → squad solicitante | Baixa |

## Protocolo Passo-a-Passo

### Fase 1: Preparação (Squad de Origem)

**Prazo:** Iniciar 5 dias úteis antes da data de handoff

1. **Identificar o handoff** — Definir claramente o que será entregue, para quem
   e quando. Usar o `handoff-component` como template.

2. **Completar o asset** — Garantir que todos os artefatos estão finalizados,
   revisados e no formato esperado pelo squad receptor.

3. **Documentar contexto** — Escrever contexto estratégico, decisões tomadas,
   alternativas descartadas e limitações conhecidas. O receptor não deveria
   precisar perguntar o básico.

4. **Autoavaliação** — Aplicar a `cross-squad-handoff-rubric` como autoavaliação.
   Se a autoavaliação ficar abaixo de 75 (GOOD), resolver antes de enviar.

5. **Pré-brief** — Enviar notificação ao squad receptor com: o que será entregue,
   quando, e quem é o ponto de contato. Isso evita surpresas.

### Fase 2: Entrega (Momento do Handoff)

**Prazo:** Na data acordada

6. **Envio formal** — Enviar o pacote de handoff completo pelo canal acordado
   (repositório, email, plataforma de projeto). Nunca por mensagem informal.

7. **Briefing de contexto** — Sessão de 30 minutos (síncrona ou vídeo gravado)
   onde o squad de origem apresenta o que está entregando, por que as decisões
   foram tomadas e onde estão os pontos de atenção.

8. **Documentação de entrega** — Registrar formalmente: data, hora, quem entregou,
   quem recebeu, lista de artefatos, canal de dúvidas pós-handoff.

### Fase 3: Aceite (Squad de Destino)

**Prazo:** Até 48h após recebimento

9. **Confirmação de recebimento** — Squad receptor confirma que recebeu o pacote
   completo em até 24h. Silêncio não é confirmação.

10. **Avaliação de qualidade** — Aplicar a `cross-squad-handoff-rubric` em até 48h.
    Avaliar as 5 dimensões: completude, clareza, evidências, rastreabilidade, timing.

11. **Decisão de aceite:**
    - **GOLD/GOOD (75+):** Aceito. Prosseguir.
    - **REVIEW (50-74):** Aceito com ressalvas. Reunião de alinhamento em 48h.
    - **REJECT (0-49):** Rejeitado. Devolver com feedback específico.

12. **Feedback formal** — Comunicar resultado da avaliação ao squad de origem com
    pontuação, classificação e feedback acionável.

### Fase 4: Pós-Handoff

**Prazo:** 5 dias úteis após aceite

13. **Período de suporte** — Squad de origem permanece disponível para dúvidas
    por 5 dias úteis após o aceite. Canal de contato claro e assíncrono.

14. **Registro** — Handoff registrado no log com avaliação, data e participantes.

15. **Retrospectiva** — Se houve problemas (REVIEW ou REJECT), registrar aprendizado
    para melhorar próximos handoffs.

## Quality Gate de Saída (Squad de Origem)

Antes de enviar o handoff, o squad de origem verifica:

| Critério | Verificação | Status |
|----------|------------|--------|
| Asset completo | Todos os artefatos listados no escopo estão prontos | |
| Contexto documentado | Decisões, racional e limitações estão escritos | |
| Formato correto | Segue padrão/template esperado pelo receptor | |
| Revisado por peer | Pelo menos 1 pessoa além do autor revisou | |
| Autoavaliação > 75 | Rubric de handoff aplicada internamente | |
| Pré-brief enviado | Receptor foi notificado com antecedência | |
| Dependências resolvidas | Nenhuma dependência pendente bloquearia o receptor | |

**Regra:** Se qualquer item for "não", o handoff não sai.

## Quality Gate de Entrada (Squad de Destino)

Ao receber o handoff, o squad de destino verifica:

| Critério | Verificação | Status |
|----------|------------|--------|
| Pacote completo | Tudo que foi prometido foi entregue | |
| Autoexplicativo | Entende o material sem precisar de reunião extra | |
| Dados verificáveis | Fontes, datas e métodos estão documentados | |
| Cadeia rastreável | Consegue entender como se chegou aqui | |
| No prazo | Recebido dentro da janela acordada | |
| Sem bloqueios | Nenhuma dependência impede de iniciar o trabalho | |

**Regra:** Avaliação formal com rubric em até 48h.

## Registro

### Template de Registro de Handoff

```yaml
handoff_log:
  id: "HO-XXX"
  data_envio: YYYY-MM-DD
  data_aceite: YYYY-MM-DD
  tipo: "" # artefato | estratégia | dados | projeto | suporte
  de:
    squad: ""
    responsável: ""
  para:
    squad: ""
    responsável: ""
  assets_entregues:
    - nome: ""
      formato: ""
      localização: ""
  autoavaliação_origem:
    total: 0
    classificação: ""
  avaliação_destino:
    total: 0
    classificação: ""
  status: "" # aceito | aceito-com-ressalvas | rejeitado
  feedback: ""
  período_suporte_até: YYYY-MM-DD
```

## Escalação

### Quando Escalar

- Handoff rejeitado (REJECT) e squad de origem contesta
- Prazo de handoff estourado sem comunicação prévia
- Qualidade consistentemente baixa de um squad específico (3+ REVIEW consecutivos)
- Impasse sobre formato ou escopo entre squads

### Para Quem Escalar

| Situação | Escalar Para | Formato |
|----------|-------------|---------|
| Rejeição contestada | Leads dos dois squads | Reunião de mediação |
| Prazo estourado | Lead do squad atrasado + Chief | Notificação formal |
| Qualidade recorrente | Chief | Relatório de tendência |
| Impasse de escopo | Leads + Chief | Sessão de alinhamento |

### Processo de Escalação

```
1. Documentar o problema com evidências
2. Tentar resolver entre leads (24h)
3. Se não resolvido, escalar para Chief com contexto e opções
4. Chief decide em até 48h
5. Decisão documentada e comunicada
```

## Template de Handoff Preenchido

### Exemplo: Pesquisa Cultural para Squad de Criação

```yaml
handoff:
  id: "HO-012"
  data_envio: "2026-03-15"
  tipo: "artefato"

  de:
    squad: "movement-research"
    responsável: "researcher-agent"
    contato: "#movement-research no Slack"
    disponibilidade_pós_handoff: "até 2026-03-22"

  para:
    squad: "movement-creation"
    responsável: "creator-agent"

  asset:
    título: "Pesquisa Etnográfica — Burnout em Tech (Q1 2026)"
    tipo: "pesquisa"
    descrição: >
      Pesquisa etnográfica de 4 semanas em comunidades de tech (Reddit, Discord,
      LinkedIn). Inclui análise de 312 posts, 47 entrevistas curtas e mapeamento
      de 8 sinais convergentes. Foco: linguagem, comportamentos e desejos
      relacionados a burnout e produtividade.
    localização: "data/research/burnout-tech-q1-2026/"
    versão: "1.0"
    dependências:
      - "signal-taxonomy para classificação de sinais"
      - "thesis-component preenchido com tese preliminar"

  contexto_crítico: >
    O sinal mais forte detectado é a demanda por "produtividade sem culpa" —
    pessoas querem ser produtivas mas não querem sentir que estão se sacrificando.
    Isso difere do anti-hustle culture puro, que rejeita produtividade.
    A nuance é crucial para a tese.

  decisões_tomadas:
    - "Focamos em comunidades de devs (não designers) por volume de dados"
    - "Excluímos Reddit r/antiwork por viés extremo que distorceria análise"
    - "Entrevistas foram assíncronas via DM por taxa de resposta maior"

  alternativas_descartadas:
    - "Survey quantitativo foi descartado — respostas eram superficiais demais"
    - "Foco em managers foi descartado — sinais mais fortes em ICs"

  quality_gate:
    autoavaliação_total: 96
    classificação: "GOLD"

  confirmação:
    status: "aceito"
    data: "2026-03-16"
    avaliação_total: 92
    classificação: "GOLD"
```

## Integração

- Avaliação usa a `cross-squad-handoff-rubric`
- Template de handoff usa o `handoff-component`
- Escalação segue o `movement-governance-framework`
- Registro armazenado em `data/registries/`
- Quality gates fazem parte da cascata documentada em `quality-gate-cascade`
- Rework segue protocolo de rework do governance framework
