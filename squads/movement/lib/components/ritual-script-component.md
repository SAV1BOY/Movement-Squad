---
id: ritual-script-component
name: "Componente de Script de Ritual"
squad: movement
type: component
category: lib/components
version: 1.0.0
tags: [ritual, script, engajamento, hábito, componente-reutilizável]
---

# Componente de Script de Ritual

## Propósito

Bloco reutilizável para projetar rituais que transformam participantes casuais em membros comprometidos. Rituais são a cola social que mantém movimentos vivos.

## Estrutura do Bloco

### 1. Definição do Ritual

```yaml
ritual:
  nome: ""
  tipo: "" # entrada | manutenção | promoção | celebração | luto | transição
  frequência: "" # único | diário | semanal | mensal | anual | gatilho
  duração: "" # tempo estimado de execução
  participantes_mínimos: 0
  canal: "" # presencial | digital | híbrido
```

### 2. Estrutura do Script

```yaml
script:
  abertura:
    ação: "" # o que acontece primeiro
    quem_lidera: ""
    frase_de_abertura: ""
    duração: ""

  desenvolvimento:
    etapas:
      - etapa_1:
          ação: ""
          instrução: ""
          duração: ""
      - etapa_2:
          ação: ""
          instrução: ""
          duração: ""
      - etapa_3:
          ação: ""
          instrução: ""
          duração: ""

  encerramento:
    ação: ""
    frase_de_encerramento: ""
    próximo_passo: ""
```

### 3. Elementos Sensoriais

```yaml
sensorial:
  visual: "" # o que participantes veem
  auditivo: "" # o que participantes ouvem
  cinestésico: "" # o que participantes fazem fisicamente
  social: "" # como participantes interagem
  artefato: "" # o que participantes levam consigo
```

### 4. Mecânica de Engajamento

```yaml
engajamento:
  gatilho_de_início: "" # o que dispara o ritual
  recompensa_imediata: "" # o que participantes ganham na hora
  recompensa_social: "" # reconhecimento do grupo
  elemento_de_escassez: "" # o que torna o ritual especial
  mecanismo_de_compartilhamento: "" # como participantes espalham
```

### 5. Métricas do Ritual

```yaml
métricas:
  taxa_de_participação: ""
  taxa_de_repetição: ""
  taxa_de_convite: "" # participantes que trazem novos
  sentimento_pós_ritual: ""
  tempo_até_próxima_ação: ""
```

## Regras de Uso

1. **Rituais devem ser simples** — se precisa de manual, é complexo demais
2. **Deve haver um artefato** — algo tangível que marca a participação
3. **O encerramento deve apontar para o próximo** — continuidade é essencial
4. **Frequência importa mais que intensidade** — prefira rituais curtos e frequentes
5. **Cada ritual deve reforçar a identidade** do movimento

## Checklist de Qualidade

- [ ] O ritual pode ser executado sem o líder presente?
- [ ] Novatos entendem o que fazer em menos de 2 minutos?
- [ ] Participantes querem repetir sem serem lembrados?
- [ ] O ritual gera conteúdo compartilhável naturalmente?
- [ ] Existe progressão para participantes veteranos?

## Exemplo: Ritual de Entrada

```yaml
ritual:
  nome: "Primeiro Ship"
  tipo: "entrada"
  frequência: "único"
  duração: "15 minutos"
  canal: "digital"

script:
  abertura:
    frase_de_abertura: "Hoje você se torna um Construtor."
  desenvolvimento:
    etapas:
      - etapa_1:
          ação: "Compartilhar primeiro projeto no canal #primeiro-ship"
      - etapa_2:
          ação: "Receber 3 emojis de 🚀 da comunidade"
      - etapa_3:
          ação: "Adicionar badge 'Builder' no perfil"
  encerramento:
    frase_de_encerramento: "Bem-vindo. Agora, bora construir o próximo."
```

## Integração

- Alimentado pelo `identity-code-component` (comportamentos e linguagem)
- Conecta ao `community-role-component` para quem lidera rituais
- Métricas alimentam `community-health-rubric`
