# Workflow Guide — Como Executar Workflows

## Visão Geral

Workflows são fluxos de trabalho estruturados que guiam o squad na execução
de tarefas complexas. Cada workflow tem passos definidos, responsáveis claros
e outputs esperados.

## Como Usar Workflows

### 1. Identifique o Workflow Correto
Veja a lista abaixo e escolha o que corresponde à tarefa que precisa executar.
Se nenhum se encaixa, pode ser necessário criar um novo (veja `contribution-guide.md`).

### 2. Leia o Workflow Completo Antes de Começar
Nunca comece a executar sem ler tudo primeiro. Entenda os passos, outputs
esperados e dependências entre etapas.

### 3. Reúna os Inputs Necessários
Cada workflow lista os inputs necessários. Garanta que tem tudo antes de
começar para evitar bloqueios no meio do processo.

### 4. Execute Passo a Passo
Siga a ordem dos passos. Alguns podem ser paralelizados — o workflow indica
quando isso é possível.

### 5. Documente os Outputs
Todo workflow gera deliverables. Salve nos diretórios corretos seguindo
as convenções de nomenclatura em `naming-conventions.md`.

## Workflows Disponíveis

### Workflows Estratégicos
- **Definição de Tese**: Como criar e validar uma nova tese (enemy/dream/mechanism)
- **Revisão Estratégica**: Como conduzir a revisão mensal/trimestral
- **Análise Competitiva**: Como mapear movimentos concorrentes

### Workflows de Pesquisa
- **Captura de Sinais**: Como capturar e registrar sinais culturais
- **Etnografia Digital**: Como conduzir observações etnográficas online
- **Entrevista de Profundidade**: Como conduzir e documentar entrevistas

### Workflows de Narrativa
- **Criação de Manifesto**: Como criar um manifesto para o movimento
- **Desenvolvimento de Slogan**: Como criar e testar slogans
- **Resposta a Contra-Narrativa**: Como responder a críticas e oposição

### Workflows de Comunidade
- **Onboarding de Membro**: Como receber novos membros
- **Promoção de Champion**: Como identificar e promover champions
- **Criação de Ritual**: Como desenhar e lançar um novo ritual

### Workflows de Conteúdo e Distribuição
- **Criação de Conteúdo**: Como criar conteúdo alinhado com o movimento
- **Co-criação com Champions**: Como co-criar com champions
- **Lançamento em Nova Plataforma**: Como expandir para nova plataforma

### Workflows de Métricas
- **Dashboard Semanal**: Como preencher e analisar o dashboard
- **Análise de Coorte**: Como analisar retenção por coorte
- **Report de Impacto**: Como medir e reportar impacto de negócio

## Onde Encontrar os Workflows

Workflows detalhados ficam em `squads/movement/workflows/`. Cada workflow
é um arquivo separado com passos numerados.

## Quando Criar um Novo Workflow

Crie um novo workflow quando:
- Uma tarefa complexa se repete mais de 3 vezes
- Diferentes agentes fazem a mesma tarefa de formas diferentes
- Erros acontecem por falta de processo

## Formato de um Workflow

```
1. Nome e objetivo
2. Agente(s) responsável(is)
3. Inputs necessários
4. Passos numerados com descrição
5. Outputs esperados
6. Critérios de qualidade
7. Onde salvar os resultados
```

## Dicas de Execução

- **Não pule passos** — Cada passo existe por um motivo
- **Adapte quando necessário** — Workflows são guias, não prisões
- **Documente desvios** — Se precisou mudar algo, registre para melhorar o workflow
- **Peça feedback** — Após executar, pergunte ao squad se o output ficou bom
- **Sugira melhorias** — Workflows devem evoluir com a prática

## Resolução de Problemas

- **Bloqueado em um passo?** Verifique se os inputs estão completos
- **Output não parece correto?** Compare com exemplos anteriores
- **Workflow desatualizado?** Abra um issue para atualização
- **Dúvida sobre qual workflow usar?** Pergunte ao Chief of Movement
