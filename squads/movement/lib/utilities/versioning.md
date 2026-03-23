---
id: versioning
name: "Versionamento de Artefatos"
squad: movement
type: utility
category: lib/utilities
version: 1.0.0
tags: [versionamento, controle, evolução, utilidade]
---

# Versionamento de Artefatos

## Propósito

Definir como artefatos do squad de movimento são versionados, garantindo rastreabilidade de mudanças e clareza sobre qual versão está ativa.

## Formato de Versão

```
MAJOR.MINOR.PATCH
```

| Componente | Quando Incrementar | Exemplo |
|------------|-------------------|---------|
| MAJOR | Mudança estrutural que quebra compatibilidade | Reestruturação completa de um componente |
| MINOR | Adição de funcionalidade ou seção | Nova seção adicionada a um template |
| PATCH | Correção, clarificação ou ajuste menor | Correção de texto, ajuste de exemplo |

## Exemplos

```
1.0.0 → Versão inicial
1.0.1 → Correção de typo
1.1.0 → Adição de nova seção de exemplos
2.0.0 → Reestruturação completa da estrutura YAML
```

## Regras de Versionamento

1. **Todo artefato começa em 1.0.0**
2. **Nunca pule versões** — vá de 1.0.0 para 1.0.1, não para 1.0.5
3. **MAJOR requer aprovação** — mudanças estruturais devem ser discutidas
4. **MINOR pode ser feito por qualquer contribuidor**
5. **PATCH pode ser feito por qualquer pessoa**

## Registro de Mudanças

Ao atualizar a versão, adicione uma seção no final do arquivo:

```markdown
## Changelog

### 1.1.0 — 2026-03-15
- Adicionada seção de exemplos práticos
- Revisada tabela de tipos de sinal

### 1.0.1 — 2026-03-12
- Corrigido exemplo de YAML na seção 3
- Ajustada descrição do campo "urgência"

### 1.0.0 — 2026-03-10
- Versão inicial do artefato
```

## Ciclo de Vida de um Artefato

```
RASCUNHO (0.x.x) → PUBLICADO (1.0.0) → ITERADO (1.x.x / 2.x.x) → DEPRECIADO → ARQUIVADO
```

### Estados

| Estado | Versão | Localização |
|--------|--------|-------------|
| Rascunho | 0.x.x | Diretório original com flag `draft: true` |
| Publicado | 1.0.0+ | Diretório original |
| Depreciado | Última versão | Mover para `archive/deprecated-theses/` |
| Arquivado | N/A | `archive/` com prefixo de data |

## Depreciação

Quando um artefato é superado:

1. Marcar como depreciado no frontmatter:
```yaml
status: deprecated
deprecated_date: 2026-06-15
replaced_by: novo-artefato-id
reason: "Tese revisada após crise X"
```

2. Mover para `archive/deprecated-theses/`
3. Registrar decisão em `archive/decisions/`

## Compatibilidade

- Artefatos que referenciam outros devem especificar a versão mínima
- Ao fazer MAJOR bump, verificar todos os artefatos que referenciam o alterado
- Manter a versão anterior acessível por pelo menos 90 dias

## Automação Sugerida

```bash
# Verificar versão atual de um artefato
grep "version:" arquivo.md

# Listar todos os artefatos e suas versões
find . -name "*.md" -exec grep -l "version:" {} \; | xargs grep "version:"
```
