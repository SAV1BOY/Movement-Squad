---
id: case-study-creation-guide
name: "Guia de Criação de Case Studies"
squad: movement
type: authority
category: authority
version: 1.0.0
tags: [autoridade, case-study, criação, narrativa, prova]
---

# Guia de Criação de Case Studies

## Propósito

Framework para criar case studies que demonstram a eficácia do movimento e seus métodos, servindo simultaneamente como prova de impacto e ferramenta de recrutamento.

## Por Que Case Studies Importam

1. **Prova concreta** de que a tese funciona
2. **Ferramenta de recrutamento** — "veja o que aconteceu com quem participou"
3. **Conteúdo de autoridade** — demonstra profundidade e resultados
4. **Material de vendas** — para parceiros, investidores, mídia
5. **Aprendizado interno** — documentar o que funciona e o que não

## Estrutura do Case Study

### Template Padrão (800-1500 palavras)

```markdown
# [Nome do Case] — [Resultado em Uma Frase]

## Contexto
- Quem é o protagonista (pessoa, organização, comunidade)
- Qual era a situação antes
- Qual era o desafio específico

## Desafio
- O problema em detalhes concretos
- Métricas do "antes"
- O que já tinha sido tentado
- Por que as soluções anteriores falharam

## Abordagem
- Como o movimento/método foi aplicado
- Quais componentes foram usados
- Timeline da implementação
- Decisões-chave tomadas

## Resultados
- Métricas do "depois" (comparadas com "antes")
- Resultados quantitativos
- Resultados qualitativos
- Citação direta do protagonista

## Lições
- O que funcionou e por quê
- O que foi surpreendente
- O que fariam diferente
- Recomendação para outros
```

## Tipos de Case Study

| Tipo | Foco | Extensão | Melhor Para |
|------|------|----------|-------------|
| Micro-case | Um resultado específico | 300-500 palavras | Redes sociais |
| Case padrão | Jornada completa | 800-1500 palavras | Blog, newsletter |
| Case profundo | Análise detalhada com dados | 2000-4000 palavras | Whitepaper, apresentação |
| Vídeo case | Depoimento visual | 3-8 minutos | YouTube, eventos |
| Case interativo | Timeline navegável | Variável | Site dedicado |

## Processo de Criação

### Etapa 1: Seleção do Caso

```yaml
critérios_de_seleção:
  resultado_mensurável: true # deve ter números
  protagonista_disposto: true # deve autorizar uso
  representativo: true # reflete experiência típica (não outlier)
  diversidade: true # variar perfis entre cases
  recência: true # preferencialmente < 12 meses
```

### Etapa 2: Coleta de Informação

**Entrevista com protagonista (30-60 min):**
1. "Como era antes?" — contexto e dor
2. "O que tentou antes?" — soluções anteriores
3. "O que mudou?" — momento de virada
4. "Qual foi o resultado?" — métricas e sentimentos
5. "O que diria para quem está na mesma situação?" — citação-ouro

**Dados complementares:**
- Métricas antes/depois
- Screenshots, fotos, evidências visuais
- Depoimentos de terceiros (colegas, clientes)

### Etapa 3: Narrativa

**Regras de storytelling para cases:**
1. Comece com a dor, não com a solução
2. O protagonista é o herói, não o movimento
3. Mostre vulnerabilidade — imperfeições tornam crível
4. Uma citação forte vale mais que três parágrafos
5. Termine com a transformação, não com o método

### Etapa 4: Revisão

- Protagonista revisa para precisão e aprovação
- Editor revisa para clareza e impacto
- Métricas verificadas com fontes
- Citações aprovadas para uso público

## Distribuição do Case Study

| Canal | Formato | Adaptação |
|-------|---------|-----------|
| Blog | Texto completo | SEO-otimizado com imagens |
| LinkedIn | Resumo + link | Foco em lição de negócio |
| Instagram | Carrossel visual | Dados visuais + citação |
| Newsletter | Destaque | Gancho + link para completo |
| Apresentação | Slides | 3-5 slides com antes/depois |
| Proposta comercial | Resumo | 1 parágrafo com resultado-chave |

## Métricas de Eficácia do Case

| Métrica | O que Mede | Meta |
|---------|-----------|------|
| Tempo de leitura | Engajamento | > 3 min |
| Taxa de compartilhamento | Ressonância | > 3% |
| Menções do case em conversas | Memorabilidade | Tracking qualitativo |
| Leads/membros gerados | Conversão | Atribuição direta |
| Citações por mídia/pares | Autoridade | > 2 por case |

## Armadilhas

1. **Case perfeito demais:** Sem dificuldades = não crível
2. **Foco no método, não no protagonista:** As pessoas se conectam com pessoas
3. **Métricas vagas:** "Melhorou muito" não é métrica
4. **Sem autorização:** Nunca publique sem aprovação escrita
5. **Case único:** Um case é anedota; 3+ cases são padrão

## Integração

- Cases usam estrutura do `proof-component`
- Narrativa segue `manifesto-block-component`
- Distribuição via `distribution-channel-component`
- Alimentam `thought-leadership-strategy`
- Arquivados em `archive/iconic-movements/` quando históricos
