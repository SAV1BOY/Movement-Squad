---
id: handoff-component
name: "Componente de Handoff"
squad: movement
type: component
category: lib/components
version: 1.0.0
tags: [handoff, transição, cross-squad, entrega, componente-reutilizável]
---

# Componente de Handoff

## Propósito

Bloco reutilizável para estruturar transições de trabalho entre squads ou entre fases de projeto. O handoff é o momento mais frágil de qualquer operação — é onde contexto se perde, qualidade degrada e prazos estouram. Este componente padroniza a entrega para eliminar ambiguidade.

## Estrutura do Bloco

### 1. De (Squad de Origem)

```yaml
de:
  squad: "" # nome do squad que está entregando
  responsável: "" # pessoa que lidera o handoff
  papel: "" # papel/agent do responsável
  contato: "" # canal para dúvidas pós-handoff
  disponibilidade_pós_handoff: "" # por quanto tempo estará disponível para dúvidas
```

**Regras do squad de origem:**
- O responsável deve ser quem executou o trabalho, não um intermediário
- Disponibilidade pós-handoff mínima de 5 dias úteis
- Contato deve ser canal assíncrono (não depender de reunião)

### 2. Para (Squad de Destino)

```yaml
para:
  squad: "" # nome do squad que está recebendo
  responsável: "" # pessoa que recebe o handoff
  papel: "" # papel/agent do responsável
  data_recebimento: "" # YYYY-MM-DD
  prazo_para_aceite: "" # YYYY-MM-DD (máximo 48h após recebimento)
```

**Regras do squad de destino:**
- Deve confirmar recebimento em até 24h
- Deve avaliar qualidade do handoff em até 48h
- Deve escalar imediatamente se houver bloqueio crítico

### 3. Asset Entregue

```yaml
asset:
  título: "" # nome descritivo do que está sendo entregue
  tipo: "" # documento | dataset | artefato | código | estratégia | pesquisa | template
  descrição: "" # o que é e para que serve (2-3 frases)
  localização: "" # path ou link para o asset
  versão: "" # versão do asset entregue
  dependências: [] # outros assets necessários para usar este
  contexto_crítico: "" # informação que não está no asset mas é essencial
  decisões_tomadas: [] # decisões que moldaram o asset (e por quê)
  alternativas_descartadas: [] # caminhos que foram considerados e rejeitados
```

**Regras do asset:**
- Deve ser autocontido — o receptor não deveria precisar perguntar o básico
- Decisões tomadas são tão importantes quanto o resultado final
- Alternativas descartadas evitam que o receptor refaça análises já feitas

### 4. Formato Esperado

```yaml
formato:
  padrão_seguido: "" # qual template, rubrica ou padrão foi seguido
  estrutura: "" # como o asset está organizado
  nomenclatura: "" # convenção de nomes usada
  encoding: "" # formato técnico (markdown, yaml, figma, etc.)
  tamanho: "" # volume aproximado (páginas, linhas, slides)
  idioma: "pt-BR"
```

### 5. Quality Gate

```yaml
quality_gate:
  autoavaliação:
    completude: "" # 0-25 (conforme cross-squad-handoff-rubric)
    clareza: "" # 0-25
    evidências: "" # 0-25
    rastreabilidade: "" # 0-25
    timing: "" # 0-25
    total: 0
    classificação: "" # GOLD | GOOD | REVIEW | REJECT
  revisores: [] # quem revisou antes do handoff
  checklist:
    - item: "Asset completo e funcional"
      status: false
    - item: "Contexto e decisões documentados"
      status: false
    - item: "Dependências listadas e acessíveis"
      status: false
    - item: "Formato conforme padrão acordado"
      status: false
    - item: "Testado/validado antes da entrega"
      status: false
```

**Regras do quality gate:**
- Autoavaliação obrigatória — squad de origem se avalia antes de entregar
- Mínimo de 1 revisor além do autor
- Todos os itens do checklist devem ser true para handoff válido

### 6. Confirmação de Recebimento

```yaml
confirmação:
  data_confirmação: "" # YYYY-MM-DD
  confirmado_por: ""
  status: "" # aceito | aceito-com-ressalvas | rejeitado
  ressalvas: [] # se aceito com ressalvas, listar
  motivo_rejeição: "" # se rejeitado, explicar
  avaliação_receptor:
    completude: 0
    clareza: 0
    evidências: 0
    rastreabilidade: 0
    timing: 0
    total: 0
    classificação: ""
  próximos_passos: []
```

**Regras da confirmação:**
- Silêncio não é aceite — confirmação explícita é obrigatória
- Ressalvas devem ser específicas e acionáveis
- Rejeição deve incluir o que falta e prazo esperado para reentrega

## Template Completo de Handoff

```yaml
handoff:
  id: "HO-XXX"
  data: YYYY-MM-DD
  de:
    squad: ""
    responsável: ""
  para:
    squad: ""
    responsável: ""
  asset:
    título: ""
    tipo: ""
    descrição: ""
    localização: ""
  quality_gate:
    autoavaliação_total: 0
    classificação: ""
  confirmação:
    status: "" # pendente | aceito | rejeitado
    data: ""
```

## Fluxo do Handoff

```
1. Squad origem prepara asset
2. Squad origem preenche quality gate (autoavaliação)
3. Squad origem envia handoff formalizado
4. Squad destino confirma recebimento (24h)
5. Squad destino avalia qualidade (48h)
6. Se aceito → prosseguir
7. Se ressalvas → alinhar e resolver
8. Se rejeitado → squad origem complementa e reenvia
```

## Armadilhas Comuns

1. **Handoff verbal**: "te explico na call" — sem documento, sem rastro
2. **Contexto implícito**: assumir que o receptor sabe o que você sabe
3. **Asset sem dono**: entregar e sumir — disponibilidade pós-handoff é obrigatória
4. **Quality gate pulado**: "não deu tempo de revisar" — isso é dívida, não velocidade
5. **Confirmação tácita**: "mandei e ninguém reclamou" — confirmar é responsabilidade do receptor

## Integração

- Avaliado pelo `cross-squad-handoff-rubric`
- Protocolo completo em `cross-squad-handoff-protocol`
- Registrado no log de handoffs em `data/registries/`
- Conecta fases de projeto (ex: `new-movement-launch/` → `movement-scaling/`)
