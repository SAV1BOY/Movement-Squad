---
id: crisis-to-opportunity-pattern
name: "Padrão Crise → Catalisador → Fortalecimento"
squad: movement
type: pattern
category: lib/patterns
version: 1.0.0
tags: [crise, oportunidade, resiliência, catalisador, padrão-repetível]
---

# Padrão Crise → Catalisador → Fortalecimento

## Propósito

Padrão repetível para transformar crises (internas ou externas) em catalisadores que fortalecem o movimento. Crises são inevitáveis — o que define um movimento é como responde a elas.

## O Padrão

```
CRISE (ameaça) → CATALISADOR (resposta estratégica) → FORTALECIMENTO (movimento mais forte)
```

### Etapa 1: Diagnosticar a Crise

```yaml
crise:
  tipo: "" # reputacional | cisma interno | ataque externo | irrelevância | escândalo | fadiga
  gravidade: "" # leve | moderada | severa | existencial
  origem: "" # interna | externa | ambas
  velocidade: "" # lenta | rápida | instantânea
  visibilidade: "" # privada | semi-pública | pública | viral
  descrição: ""
  stakeholders_afetados: []
  janela_de_resposta: "" # horas | dias | semanas
```

**Tipos de crise por gravidade:**
| Tipo | Exemplo | Gravidade Típica |
|------|---------|-----------------|
| Fadiga de engajamento | Queda gradual de participação | Leve |
| Controvérsia externa | Mídia critica o movimento | Moderada |
| Cisma de liderança | Líderes discordam publicamente | Severa |
| Escândalo de fundador | Fundador age contra valores | Existencial |
| Cooptação | Grupo externo sequestra a narrativa | Severa |
| Irrelevância | O mundo mudou e o movimento não | Existencial |

### Etapa 2: Ativar o Catalisador

```yaml
catalisador:
  resposta_imediata:
    ação: "" # o que fazemos nas primeiras 24h
    porta_voz: "" # quem fala pelo movimento
    canal: "" # onde comunicamos
    tom: "" # transparência | firmeza | empatia | humildade
    mensagem_chave: "" # uma frase central

  resposta_estratégica:
    narrativa: "" # como enquadramos a crise
    ação_concreta: "" # o que mudamos de verdade
    sacrifício_visível: "" # o que abrimos mão para mostrar seriedade
    convite_à_comunidade: "" # como envolvemos membros na resposta
    prazo_de_resolução: ""

  comunicação:
    interna_primeiro: "" # mensagem para membros antes do público
    transparência: "" # o que revelamos e o que não
    frequência_de_updates: ""
    canal_de_escuta: "" # onde membros podem expressar preocupações
```

### Etapa 3: Fortalecer o Movimento

```yaml
fortalecimento:
  lição_documentada: "" # o que aprendemos
  mudança_estrutural: "" # o que mudamos para prevenir recorrência
  narrativa_pós_crise: "" # a história que contamos sobre como superamos
  novos_rituais: "" # rituais criados a partir da crise
  membros_que_permaneceram: "" # como reconhecemos lealdade
  novos_membros_atraídos: "" # quem veio por causa da resposta
  atualização_de_tese: "" # a crise mudou nossa tese?
```

## Playbook por Tipo de Crise

### Crise Reputacional
1. Reconhecer rapidamente — silêncio é confirmação
2. Separar fato de narrativa
3. Mostrar ação, não apenas palavras
4. Dar protagonismo a membros afetados

### Cisma Interno
1. Criar espaço seguro para divergência
2. Reafirmar valores comuns, não posições
3. Aceitar que alguma perda é inevitável
4. Documentar a decisão com transparência

### Irrelevância
1. Honrar o que foi, sem se apegar
2. Buscar novos sinais de tensão
3. Atualizar a tese mantendo a essência
4. Convidar novas vozes para reinventar

## Regras do Padrão

1. **Velocidade importa** — a primeira narrativa define a percepção
2. **Interno antes do externo** — membros devem saber antes da mídia
3. **Transparência > perfeição** — admitir o que não sabe é melhor que inventar
4. **Ação > discurso** — uma mudança real vale mais que mil comunicados
5. **Documentar para o arquivo** — crises viram lições em `failures-and-lessons`

## Checklist de Resposta

- [ ] A crise foi classificada por tipo e gravidade?
- [ ] A comunidade interna foi informada primeiro?
- [ ] Há porta-voz definido e preparado?
- [ ] A resposta inclui ação concreta, não apenas palavras?
- [ ] A lição será documentada no arquivo?

## Integração

- Decisões registradas em `archive/decisions/`
- Lições documentadas em `archive/failures-and-lessons/`
- Mudanças de tese registradas em `archive/deprecated-theses/`
- Padrão de decisão via `decision-logs` utility
