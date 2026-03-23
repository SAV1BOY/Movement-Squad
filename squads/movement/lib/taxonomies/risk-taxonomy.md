---
id: risk-taxonomy
name: "Taxonomia de Riscos"
squad: movement
type: taxonomy
category: lib/taxonomies
version: 1.0.0
tags: [taxonomia, risco, classificação, mitigação, operacional]
---

# Taxonomia de Riscos

## Propósito

Sistema de classificação para os tipos de riscos operacionais que um movimento pode enfrentar. Riscos não gerenciados matam movimentos silenciosamente. Esta taxonomia permite identificação precoce, categorização consistente e resposta proporcional.

## Categorias de Risco

### 1. Riscos Reputacionais

| Subtipo | Descrição | Exemplo | Indicador Precoce |
|---------|-----------|---------|-------------------|
| Contradição pública | Ação da marca contradiz tese do movimento | Defender sustentabilidade e ser flagrado poluindo | Inconsistências entre discurso e prática |
| Porta-voz tóxico | Champion ou embaixador se envolve em polêmica | Influenciador parceiro faz declaração racista | Histórico controverso não verificado |
| Cooptação narrativa | Tese do movimento usada por grupo indesejado | Extremistas se apropriam do slogan | Uso do slogan em contextos não previstos |
| Percepção de astroturfing | Comunidade percebe que movimento é artificial | "Isso é marketing disfarçado" | Queda de confiança em pesquisas qualitativas |
| Fadiga de causa | Público cansa do tema antes do movimento maturar | "Mais um falando sobre burnout" | Queda de engajamento sem mudança de qualidade |

### 2. Riscos Operacionais

| Subtipo | Descrição | Exemplo | Indicador Precoce |
|---------|-----------|---------|-------------------|
| Dependência de pessoa | Movimento depende de 1-2 pessoas-chave | Fundador sai e movimento colapsa | Concentração de decisões em poucos |
| Esgotamento do time | Cadência insustentável leva a burnout | Time reduz qualidade por exaustão | Atrasos recorrentes, erros aumentando |
| Perda de cadência | Loop operacional para de girar | Semanas sem conteúdo novo | Gap entre publicações aumentando |
| Debt técnico/criativo | Atalhos acumulados degradam qualidade | Templates desatualizados, processos obsoletos | Retrabalho crescente |
| Falha de handoff | Transição entre squads perde contexto | Trabalho refeito por falta de documentação | Handoffs avaliados como REVIEW ou REJECT |

### 3. Riscos Legais

| Subtipo | Descrição | Exemplo | Indicador Precoce |
|---------|-----------|---------|-------------------|
| Propriedade intelectual | Uso de conteúdo protegido sem autorização | Meme com imagem de terceiro sem licença | UGC não curado sem checagem de direitos |
| Privacidade | Exposição de dados pessoais de membros | Vazar lista de emails da comunidade | Processos de dados sem compliance |
| Publicidade enganosa | Afirmações que não podem ser sustentadas | "Nosso método aumenta produtividade em 300%" | Claims sem evidências documentadas |
| Regulatório setorial | Violar regulação específica do setor | Movimento de saúde fazendo claims médicos | Operação em setor regulado sem legal review |
| Difamação | Inimigo do movimento é pessoa/empresa real identificável | Nomear CEO específico como "o inimigo" | Inimigo se tornando pessoal em vez de sistêmico |

### 4. Riscos Culturais

| Subtipo | Descrição | Exemplo | Indicador Precoce |
|---------|-----------|---------|-------------------|
| Insensibilidade cultural | Conteúdo ofensivo para grupo específico | Slogan que tem conotação negativa em outra cultura | Falta de diversidade no time de revisão |
| Bolha ideológica | Movimento se fecha em eco chamber | Só pessoas que concordam permanecem | Queda de diversidade de opiniões |
| Tribalismo tóxico | Identidade de grupo se torna excludente | "Quem não está conosco está contra nós" | Linguagem de guerra contra "os outros" |
| Desconexão geracional | Linguagem ou referências não ressoam com público | Usar gíria que só Gen Z entende para público 35+ | Feedback de confusão ou irrelevância |
| Apropriação cultural | Movimento se apropria de símbolos de outra cultura | Usar estética indígena sem conexão autêntica | Críticas de membros de grupos minoritários |

### 5. Riscos Financeiros

| Subtipo | Descrição | Exemplo | Indicador Precoce |
|---------|-----------|---------|-------------------|
| ROI negativo | Investimento não gera retorno proporcional | Budget queimado sem tração | Custo por membro ativo crescendo |
| Dependência de budget | Movimento só funciona com investimento pago | Sem boost, engajamento cai a zero | Orgânico < 20% do total |
| Custo de escala | Escalar custa exponencialmente mais | Comunidade cresce mas custo por membro triplica | Unit economics deteriorando |
| Perda de sponsor | Patrocinador/stakeholder retira apoio | Budget cortado no meio do projeto | Stakeholder desengajado em reviews |
| Oportunidade perdida | Não investir no momento certo | Concorrente lança movimento similar primeiro | Sinais culturais fortes não aproveitados |

## Severidade do Risco

| Nível | Probabilidade × Impacto | Critério | Ação |
|-------|------------------------|----------|------|
| Crítico | Alta prob. × Alto impacto | Ameaça a existência do movimento | Mitigação imediata — escalar para Chief |
| Alto | Alta prob. × Médio impacto OU Média prob. × Alto impacto | Ameaça a saúde ou reputação | Mitigação em até 48h — plano de ação |
| Médio | Média prob. × Médio impacto | Prejudica operação ou qualidade | Mitigação planejada — incluir no sprint |
| Baixo | Baixa prob. × Baixo impacto | Inconveniente gerenciável | Monitorar — revisar mensalmente |

## Matriz de Probabilidade × Impacto

```
              │ Baixo Impacto │ Médio Impacto │ Alto Impacto │
──────────────┼───────────────┼───────────────┼──────────────│
Alta Prob.    │    Médio      │     Alto      │   Crítico    │
Média Prob.   │    Baixo      │     Médio     │   Alto       │
Baixa Prob.   │    Baixo      │     Baixo     │   Médio      │
```

## Padrões de Mitigação

### Mitigação por Categoria

| Categoria | Padrão de Mitigação | Responsável |
|-----------|-------------------|-------------|
| Reputacional | Protocolo de crise + monitoramento contínuo + alinhamento de valores | Chief + Strategist |
| Operacional | Redundância de papéis + documentação + cadência sustentável | Leads operacionais |
| Legal | Revisão jurídica preventiva + compliance checklist + permissões documentadas | Legal + Ops |
| Cultural | Diversidade no time + revisão cultural + testes com públicos diversos | Community + Researcher |
| Financeiro | Unit economics claro + cenários de contingência + diversificação de canais | Chief + Analyst |

### Protocolo de Resposta por Severidade

| Severidade | Tempo de Resposta | Quem é Notificado | Formato |
|-----------|-------------------|-------------------|---------|
| Crítico | Imediato (< 2h) | Chief + Stakeholders | War room síncrono |
| Alto | Até 48h | Chief + Leads envolvidos | Reunião dedicada |
| Médio | Até 1 semana | Lead responsável | Assíncrono com plano |
| Baixo | Próxima review mensal | Anotado no risk log | Registro no log |

## Integração

- Riscos registrados em `data/risk-log.yaml`
- Mitigação de riscos reputacionais via `crisis-response/` project
- Avaliação de risco no `readiness-review-rubric` e `readiness-review-protocol`
- Chief Risk Appetite definido em `chief-risk-appetite-framework`
- Classificação alimenta decisões de go/no-go em `movement-governance-framework`
