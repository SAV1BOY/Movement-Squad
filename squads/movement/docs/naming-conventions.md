# Naming Conventions — Convenções de Nomenclatura

## Visão Geral

Convenções de nomenclatura consistentes facilitam encontrar, organizar e
referenciar arquivos. Todos os membros do squad devem seguir estas convenções.

## Regras Gerais

### Para Todos os Arquivos
- Use **kebab-case** (palavras separadas por hífen): `meu-arquivo.md`
- Sempre em **minúsculas**: `trend-brief.md`, nunca `Trend-Brief.md`
- Sem espaços: `nome-do-arquivo.md`, nunca `nome do arquivo.md`
- Sem caracteres especiais: sem acentos, cedilhas ou caracteres não-ASCII
- Sem abreviações obscuras: `competitor-analysis.md`, não `comp-anal.md`

### Para Arquivos com Data
Prefixe com data ISO: `YYYY-MM-DD_descricao.md`
Exemplo: `2026-03-10_sinal-fadiga-automacao.md`

### Para Arquivos Versionados
Sufixe com versão: `manifesto-v1.md`, `manifesto-v2.md`
Ou use data se preferir: `manifesto-2026-03-10.md`

## Convenções por Diretório

### data/research/signals/
```
YYYY-MM-DD_tipo_descricao-curta.md
Exemplo: 2026-03-10_diario_tensao-produtividade-toxica.md
Tipos: diario, semanal, plataforma, mercado, comunidade
```

### data/research/ethnography-notes/
```
YYYY-MM-DD_contexto_descricao.md
Exemplo: 2026-03-10_linkedin_frustracao-metricas-vaidade.md
```

### data/research/interviews/
```
YYYY-MM-DD_tipo_perfil_tema.md
Exemplo: 2026-03-10_entrevista_champion_motivacao-participar.md
Tipos: entrevista, call, dm-sanitizada
```

### data/research/trend-briefs/
```
YYYY-MM-DD_tendencia_descricao-curta.md
Exemplo: 2026-03-10_tendencia_fadiga-automacao.md
```

### data/research/competitor-movements/
```
YYYY-MM-DD_concorrente_aspecto.md
Exemplo: 2026-03-10_marca-x_estrategia-comunidade.md
```

### data/research/platform-dynamics/
```
YYYY-MM-DD_plataforma_aspecto.md
Exemplo: 2026-03-10_linkedin_mudanca-algoritmo-video.md
```

### data/research/counter-narratives/
```
YYYY-MM-DD_contra-narrativa_descricao.md
Exemplo: 2026-03-10_contra-narrativa_movimento-e-marketing.md
```

### data/research/cultural-context/
```
YYYY-MM-DD_mercado_aspecto.md
Exemplo: 2026-03-10_brasil-sudeste_cultura-startup.md
```

### data/registries/
Arquivos YAML com nomes descritivos fixos (não mudam):
```
movement-theses.yaml
identity-codes.yaml
community-roles.yaml
(etc.)
```

### data/metrics/
Definições de métricas (fixas): `nome-da-metrica.md`
Dashboards preenchidos: `YYYY-WXX-weekly-dashboard.md`

### docs/
Nomes descritivos em kebab-case: `nome-do-documento.md`

### frameworks/
Nomes do framework em kebab-case: `nome-do-framework.yaml` ou `.md`

### templates/
Prefixados com `tpl-`: `tpl-nome-do-template.md`

### workflows/
Prefixados com `wf-`: `wf-nome-do-workflow.md`

### checklists/
Prefixados com `cl-`: `cl-nome-da-checklist.md`

## IDs e Referências

### Padrão de IDs
Use prefixo + número sequencial com zero-padding:
- Teses: `THESIS-001`, `THESIS-002`
- Experimentos: `EXP-001`, `EXP-002`
- Decisões: `DEC-001`, `DEC-002`
- Slogans: `SLOGAN-001`, `SLOGAN-002`
- Champions: `CHAMP-001`, `CHAMP-002`
- Sinais: `SIG-001`, `SIG-002`
- Lições: `LESSON-001`, `LESSON-002`
- Códigos: `CODE-001`, `CODE-002`
- Creators: `CREATOR-001`, `CREATOR-002`

### Referências Cruzadas
Ao referenciar outro arquivo, use caminho relativo a partir de
`squads/movement/`: `data/research/signals/2026-03-10_diario_exemplo.md`

## Exceções

- Arquivos `.gitkeep` não seguem convenção (são padrão Git)
- `README.md` usa maiúsculas (convenção universal)
- Arquivos de configuração (`.yaml`, `.json`) na raiz podem usar
  nomes padrão do ecossistema
