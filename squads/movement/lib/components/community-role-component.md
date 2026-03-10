---
id: community-role-component
name: "Componente de Papel na Comunidade"
squad: movement
type: component
category: lib/components
version: 1.0.0
tags: [comunidade, papéis, liderança, estrutura, componente-reutilizável]
---

# Componente de Papel na Comunidade

## Propósito

Bloco reutilizável para definir e estruturar os papéis que membros exercem dentro de um movimento. Papéis claros criam senso de pertencimento, progressão e responsabilidade distribuída.

## Estrutura do Bloco

### 1. Definição do Papel

```yaml
papel:
  nome: ""
  nome_interno: "" # como a comunidade chama
  nível: "" # observador | participante | contribuidor | líder | fundador
  descrição_curta: "" # 1 frase
  responsabilidades:
    - responsabilidade_1: ""
    - responsabilidade_2: ""
    - responsabilidade_3: ""
  direitos:
    - direito_1: ""
    - direito_2: ""
  tempo_esperado: "" # horas por semana
```

### 2. Critérios de Entrada

```yaml
entrada:
  pré_requisitos: []
  ritual_de_entrada: "" # referência ao ritual-script-component
  aprovação_necessária: "" # automática | por pares | por líder
  período_probatório: ""
  mentor_designado: "" # sim | não
```

### 3. Critérios de Progressão

```yaml
progressão:
  próximo_papel: ""
  métricas_de_progressão:
    - métrica_1: ""
    - métrica_2: ""
  tempo_mínimo: ""
  avaliação: "" # auto | pares | líder | comunidade
  celebração_de_promoção: "" # como reconhecemos a transição
```

### 4. Suporte ao Papel

```yaml
suporte:
  recursos_disponíveis: []
  canal_de_comunicação: ""
  reunião_periódica: ""
  feedback_loop: "" # como o membro recebe feedback
  saída_graciosa: "" # como sair do papel sem estigma
```

## Mapa de Papéis Padrão

```
Fundador(es)
    ↕
Líderes de Comunidade
    ↕
Campeões / Embaixadores
    ↕
Contribuidores Ativos
    ↕
Participantes Regulares
    ↕
Observadores / Lurkers
```

### Descrição de Cada Nível

| Nível | Tempo/Semana | Ação Principal | Métrica |
|-------|-------------|----------------|---------|
| Observador | < 1h | Consome conteúdo | Views |
| Participante | 1-3h | Reage e comenta | Interações |
| Contribuidor | 3-5h | Cria conteúdo/ajuda | Contribuições |
| Campeão | 5-10h | Lidera iniciativas | Impacto |
| Líder | 10h+ | Define direção | Crescimento |

## Regras de Uso

1. **Todo papel deve ter nome memorável** — evite jargão corporativo
2. **Progressão deve ser transparente** — critérios públicos e objetivos
3. **Saída deve ser tão digna quanto entrada** — sem punição por sair
4. **Papéis devem ser voluntários** — obrigação mata engajamento
5. **Reconhecimento deve ser público** — visibilidade alimenta motivação

## Anti-padrões

- **Hierarquia rígida**: movimentos não são empresas
- **Papéis sem poder real**: título sem responsabilidade é insulto
- **Progressão por tempo**: premie ação, não antiguidade
- **Papéis infinitos**: máximo 6 níveis distintos
- **Papel de "moderador" como punição**: moderação deve ser honra

## Checklist de Qualidade

- [ ] Cada papel tem responsabilidades claras e direitos associados?
- [ ] A progressão é baseada em ações observáveis?
- [ ] Existe caminho de saída sem estigma?
- [ ] Os nomes dos papéis refletem a identidade do movimento?
- [ ] Papéis criam interdependência, não dependência?

## Integração

- Alimentado pelo `identity-code-component` (fronteiras e progressão)
- Conecta ao `ritual-script-component` (rituais de entrada e promoção)
- Classificado pela `community-role-taxonomy`
- Métricas alimentam `community-health-rubric`
