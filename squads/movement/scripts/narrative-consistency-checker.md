---
id: script-narrative-check
name: Verificador de Consistência Narrativa
squad: movement
type: script
tags:
  - narrativa
  - consistência
  - auditoria
  - qualidade
---

# Verificador de Consistência Narrativa

## Propósito

Avaliar se a narrativa do movimento é comunicada de forma consistente em
todos os canais e por todos os produtores. Inconsistência dilui a tese.

## Elementos a Verificar

```
Tese central: [frase]
Sub-teses: 1.[...] 2.[...] 3.[...]
Palavras que usamos: [lista]
Palavras que evitamos: [lista]
Tom geral: [descrição]
Estilo visual: [descrição]
```

## Processo

### 1. Coletar Amostra
5-10 peças por canal, incluindo time central e criadores/champions.
Total: 20-50 peças. Variar formatos (texto, imagem, vídeo).

### 2. Avaliar Cada Peça

```
ID: NAR-[n] | Canal: [onde] | Autor: [quem] | Formato: [tipo]
Tese presente: [sim/não/implícita] | Alinhada: [total/parcial/não] | [X/10]
Tom de voz: [aderente/parcial/desalinhado] | [X/10]
Visual: [aderente/parcial/desalinhado] | [X/10]
Score: [média]
```

### 3. Calcular Scores

```
Consistência de Tese = Média das notas de tese
Consistência de Tom = Média das notas de tom
Consistência Visual = Média das notas visuais
Score Geral = Tese×0.5 + Tom×0.3 + Visual×0.2
```

### 4. Analisar Padrões

**Por canal:** Qual mais/menos consistente?
**Por autor:** Quem mantém/perde consistência?
**Por formato:** Algum formato dilui a tese?
**Desvios recorrentes:** São evolução ou diluição?

### 5. Classificar Desvios

| Tipo              | Ação                              |
|-------------------|-----------------------------------|
| Erro pontual      | Feedback direto ao autor          |
| Padrão recorrente | Ajustar guidelines, retreinar     |
| Evolução positiva | Considerar incorporar ao guia     |
| Diluição          | Reforçar tese e identidade        |
| Contradição       | Investigar e corrigir urgente     |

## Template de Relatório

```
Período: [datas] | Peças: [n] | Canais: [n] | Autores: [n]

Tese:   [X/10] | Tom: [X/10] | Visual: [X/10]
SCORE GERAL: [X/10] | Tendência: [↑↓→]

Mais consistente: [canal] [X/10]
Menos consistente: [canal] [X/10]

DESVIOS: 1.[desvio]—[tipo]—[ação] 2.[...] 3.[...]
RECOMENDAÇÕES: 1.[...] 2.[...] 3.[...]
```

## Benchmarks

| Score | Classificação | Interpretação                    |
|-------|--------------|----------------------------------|
| 9-10  | Excelente    | Narrativa coesa e reconhecível   |
| 7-8   | Bom          | Consistente com desvios menores  |
| 5-6   | Regular      | Inconsistências perceptíveis     |
| 3-4   | Preocupante  | Narrativa fragmentada            |
| 1-2   | Crítico      | Cada canal parece diferente      |
