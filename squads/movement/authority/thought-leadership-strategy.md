---
id: thought-leadership-strategy
name: "Estratégia de Thought Leadership"
squad: movement
type: authority
category: authority
version: 1.0.0
tags: [autoridade, thought-leadership, posicionamento, influência, estratégia]
---

# Estratégia de Thought Leadership

## Propósito

Framework para posicionar o movimento (e seus líderes) como autoridade reconhecida no tema, criando influência que transcende o grupo de membros.

## O Que É Thought Leadership

Thought leadership é ser reconhecido como a referência em um tema — a pessoa ou organização que outros consultam, citam e seguem quando o assunto surge. Não é autopromoção; é construção de autoridade através de valor entregue.

## Os 4 Pilares

### 1. Ponto de Vista Proprietário

```yaml
ponto_de_vista:
  tese_central: "" # sua visão única sobre o tema
  framework_proprietário: "" # modelo ou método que você criou
  vocabulário_próprio: "" # termos que você introduz na conversa
  contrarian_take: "" # onde você discorda do consenso
  evidência: "" # dados ou casos que sustentam
```

**Regra:** Se seu ponto de vista não incomoda ninguém, não é diferenciado o suficiente.

### 2. Conteúdo de Autoridade

```yaml
conteúdo:
  tipo_âncora: "" # long-form que demonstra profundidade
  tipo_distribuição: "" # short-form que espalha
  frequência_mínima: "" # consistência é mais importante que volume
  canais_prioritários: [] # onde seu público busca autoridade
  formato_proprietário: "" # formato que você "possui"
```

**Hierarquia de conteúdo de autoridade:**
| Tipo | Peso | Exemplo |
|------|------|---------|
| Pesquisa original | ★★★★★ | Relatório com dados próprios |
| Framework/metodologia | ★★★★★ | Modelo aplicável e replicável |
| Livro/publicação longa | ★★★★☆ | Livro, whitepaper |
| Estudo de caso detalhado | ★★★★☆ | Análise profunda com resultados |
| Artigo de opinião | ★★★☆☆ | Op-ed em veículo relevante |
| Palestra/keynote | ★★★☆☆ | Conferência reconhecida |
| Thread/post em rede | ★★☆☆☆ | Conteúdo curto mas recorrente |

### 3. Plataformas de Validação

```yaml
validação:
  mídia: [] # veículos que publicam ou citam
  eventos: [] # conferências onde é convidado
  academia: [] # universidades/pesquisadores que referenciam
  indústria: [] # empresas/organizações que adotam
  pares: [] # outros thought leaders que citam
```

**Círculos de validação (construir de dentro para fora):**
```
Comunidade própria → Nicho do setor → Setor amplo → Mídia mainstream → Cultura
```

### 4. Rede de Influência

```yaml
rede:
  aliados_estratégicos: [] # quem amplifica sua mensagem
  plataformas_de_outros: [] # podcasts, newsletters, eventos de outros
  colaborações: [] # projetos conjuntos com pares
  mentores: [] # quem valida acima de você
  mentorados: [] # quem espalha abaixo de você
```

## Roadmap de 12 Meses

| Mês | Foco | Entregas |
|-----|------|---------|
| 1-3 | Fundação | Ponto de vista escrito, framework definido, primeiros artigos |
| 4-6 | Consistência | Publicação regular, primeiros convites para podcasts/eventos |
| 7-9 | Expansão | Guest posts em veículos maiores, primeira pesquisa original |
| 10-12 | Consolidação | Keynote em evento relevante, mídia citando como referência |

## Métricas de Autoridade

| Métrica | Como Medir | Meta Ano 1 |
|---------|-----------|-----------|
| Citações espontâneas | Google Alerts + menções | > 10/mês |
| Convites para falar | Inbound de eventos | > 6/ano |
| Republicações | Conteúdo republicado por outros | > 20/ano |
| Consultas de mídia | Jornalistas que procuram | > 4/ano |
| Adoção de framework | Organizações usando seu modelo | > 5 |

## Armadilhas

1. **Falar de tudo:** Autoridade é específica — "dono de um tema"
2. **Volume sem profundidade:** 100 posts rasos valem menos que 10 profundos
3. **Autopromoção disfarçada:** Se só fala de si, não é thought leadership
4. **Ignorar a comunidade:** Authority sem community é torre de marfim
5. **Inconsistência:** Publicar intensamente por 2 meses e sumir por 6

## Integração

- Ponto de vista vem do `thesis-component`
- Conteúdo usa `proof-component` e `signal-to-claim-pattern`
- Distribuição via `distribution-channel-component`
- Conecta a `podcast-newsletter-strategy` e `conference-speaking-strategy`
