---
id: naming-and-tagging
name: "Convenções de Nomeação e Tagging"
squad: movement
type: utility
category: lib/utilities
version: 1.0.0
tags: [nomeação, tagging, convenção, organização, utilidade]
---

# Convenções de Nomeação e Tagging

## Propósito

Definir padrões de nomeação e tagging para todos os artefatos do squad de movimento, garantindo consistência, buscabilidade e organização.

## Nomeação de Arquivos

### Formato Geral

```
[tipo]-[nome-descritivo].[extensão]
```

### Prefixos por Tipo

| Tipo | Prefixo | Exemplo |
|------|---------|---------|
| Componente | (nenhum, usa diretório) | `thesis-component.md` |
| Padrão | (nenhum, usa diretório) | `enemy-to-hero-pattern.md` |
| Utilidade | (nenhum, usa diretório) | `versioning.md` |
| Taxonomia | (nenhum, usa diretório) | `signal-taxonomy.md` |
| Arquivo de caso | `archive-` | `archive-apple-think-different.md` |
| Evolução | `evolution-` | `evolution-movement-marketing.md` |
| Autoridade | (nenhum, usa diretório) | `tribes-seth-godin.md` |
| Decisão | `decision-YYYY-MM-DD-` | `decision-2026-03-10-nome.md` |
| Tese depreciada | `deprecated-YYYY-MM-DD-` | `deprecated-2026-03-10-tese.md` |

### Regras de Nomeação

1. **Sempre em inglês para nomes de arquivo** — conteúdo em português
2. **Usar kebab-case** — palavras separadas por hífen
3. **Sem acentos ou caracteres especiais** em nomes de arquivo
4. **Máximo 60 caracteres** no nome do arquivo (sem extensão)
5. **Descritivo e específico** — evite nomes genéricos

## Sistema de Tags

### Tags Estruturais (obrigatórias)

```yaml
tags:
  - [tipo] # component | pattern | utility | taxonomy | archive | authority
  - [categoria] # lib | archive | authority
```

### Tags de Domínio (escolher pelo menos 2)

```yaml
domínio:
  - movimento
  - comunidade
  - narrativa
  - identidade
  - ritual
  - tese
  - manifesto
  - distribuição
  - métricas
  - crise
  - escala
  - cultura
  - prova
  - sinal
```

### Tags de Estágio do Movimento

```yaml
estágio:
  - pré-movimento # pesquisa e planejamento
  - lançamento # primeiros 90 dias
  - crescimento # escala ativa
  - maturidade # movimento estabelecido
  - revitalização # renovação necessária
```

### Tags de Formato

```yaml
formato:
  - template
  - rubrica
  - checklist
  - framework
  - case-study
  - guia
  - referência
```

## Frontmatter YAML Padrão

```yaml
---
id: identificador-único-kebab-case
name: "Nome Legível em Português"
squad: movement
type: component | pattern | utility | taxonomy | archive | authority
category: lib/components | lib/patterns | lib/utilities | lib/taxonomies | archive/* | authority
version: 1.0.0
tags: [tag1, tag2, tag3]
---
```

## Regras de Tagging

1. **Mínimo 3 tags** por artefato
2. **Máximo 8 tags** por artefato
3. **Tags sempre em português** (diferente do nome do arquivo)
4. **Sem tags redundantes** com o tipo ou categoria
5. **Tags devem ser de vocabulário controlado** — use as listas acima

## Busca e Navegação

### Buscar por tipo
```bash
ls lib/components/    # todos os componentes
ls lib/patterns/      # todos os padrões
```

### Buscar por tag
```bash
grep -rl "tags:.*ritual" lib/    # tudo sobre rituais
grep -rl "tags:.*crise" .        # tudo sobre crise
```

## Manutenção

- Revisar tags a cada trimestre
- Adicionar novas tags ao vocabulário controlado antes de usar
- Remover tags não utilizadas em nenhum artefato
