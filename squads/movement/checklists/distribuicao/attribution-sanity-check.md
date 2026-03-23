---
id: attribution-sanity-check
name: "Verificação de Sanidade de Atribuição"
squad: movement
type: checklist
category: distribuicao
agent: distribution-agent
version: "1.0"
tags: [atribuição, tracking, UTM, dados, distribuição]
---

# Verificação de Sanidade de Atribuição

## Objetivo

Garantir que a atribuição de resultados por canal de distribuição é confiável
e reflete a realidade. Atribuição errada leva a investir mais onde funciona
menos e cortar o que realmente funciona.

## Checklist

### Infraestrutura de Tracking

- [ ] UTM parameters estão padronizados e documentados (source, medium, campaign, content)
- [ ] Todos os links externos têm UTM implementado sem exceção
- [ ] Google Analytics ou equivalente está configurado corretamente com conversões definidas
- [ ] Pixels de plataformas de ads estão instalados e verificados (Meta, Google, TikTok)
- [ ] Eventos de conversão customizados estão configurados para ações-chave do movimento

### Modelo de Atribuição

- [ ] Modelo de atribuição está escolhido e documentado com justificativa
- [ ] Limitações do modelo escolhido são conhecidas pela equipe (first click supervaloriza discovery, last click supervaloriza conversão)
- [ ] Janela de atribuição está definida (7 dias, 30 dias) e é consistente entre canais
- [ ] Dark social (compartilhamento por WhatsApp, DM) é estimado e contabilizado
- [ ] Atribuição de canais offline (eventos, indicação boca a boca) tem proxy definido

### Verificação de Dados

- [ ] Números de cada plataforma são cruzados com fonte central (discrepâncias < 15%)
- [ ] "Direct/none" no analytics está em proporção aceitável (< 30% do tráfego total)
- [ ] Botfiltro está ativo para remover tráfego não-humano das métricas
- [ ] Duplicação de conversões entre plataformas é identificada e tratada
- [ ] Dados de atribuição são auditados mensalmente por pessoa diferente de quem configura

### Uso de Dados de Atribuição

- [ ] Decisões de investimento por canal são baseadas em dados de atribuição (não intuição)
- [ ] Report mensal compara performance por canal usando mesma metodologia de atribuição
- [ ] Anomalias de atribuição são investigadas antes de mudar investimento
- [ ] Equipe entende limitações dos dados e não trata números como verdade absoluta
- [ ] Pesquisa qualitativa ("como você nos descobriu?") complementa dados quantitativos

## Critérios de Aprovação

- Todos os itens de "Infraestrutura" devem estar completos
- Todos os itens de "Modelo de Atribuição" devem estar completos
- Pelo menos 4 de 5 itens de "Verificação de Dados" devem estar completos
- Todos os itens de "Uso de Dados" devem estar completos

## Ação se Falhar

1. Implementar UTM padronizado em todos os links em sprint de 1 semana
2. Verificar instalação de pixels e eventos de conversão em todas as plataformas
3. Escolher e documentar modelo de atribuição padrão para o movimento
4. Adicionar pergunta "como nos descobriu?" em formulário de entrada da comunidade
5. Criar dashboard de atribuição por canal acessível à equipe de distribuição
