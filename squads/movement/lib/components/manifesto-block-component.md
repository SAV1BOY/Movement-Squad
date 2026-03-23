---
id: manifesto-block-component
name: "Componente de Bloco de Manifesto"
squad: movement
type: component
category: lib/components
version: 1.0.0
tags: [manifesto, narrativa, persuasão, CTA, componente-reutilizável]
---

# Componente de Bloco de Manifesto

## Propósito

Bloco reutilizável para construir manifestos modulares. Cada manifesto é composto por blocos de abertura, contraste e chamada à ação que podem ser combinados e reordenados.

## Estrutura dos Blocos

### Bloco 1: Abertura (O Mundo Atual)

```yaml
abertura:
  gancho_emocional: "" # primeira frase que captura atenção
  descrição_do_status_quo: "" # como o mundo é hoje
  dor_universal: "" # a frustração que todos sentem
  tom: "" # indignação | urgência | esperança | provocação
  extensão: "" # 2-4 parágrafos
```

**Padrões de abertura eficazes:**
- Declaração chocante: "X está quebrado e todos sabem."
- Pergunta retórica: "Até quando vamos aceitar que...?"
- Visão do futuro: "Imagine um mundo onde..."
- Confissão: "Por anos, fizemos parte do problema."

### Bloco 2: Contraste (O Conflito)

```yaml
contraste:
  inimigo_sistêmico: "" # o sistema/prática que combatemos
  consequências_da_inação: "" # o que acontece se nada mudar
  falácia_desmascarada: "" # a mentira que sustenta o status quo
  virada_narrativa: "" # o momento de "mas nós acreditamos que..."
  tom: "" # confronto | revelação | desafio
  extensão: "" # 2-3 parágrafos
```

**Padrões de contraste eficazes:**
- Antes vs. Depois: "Eles dizem X. Nós dizemos Y."
- Desmascaramento: "A verdade que ninguém conta é..."
- Inversão: "E se o problema não fosse X, mas sim Y?"

### Bloco 3: Visão (O Mundo Possível)

```yaml
visão:
  mundo_desejado: "" # descrição vívida do futuro que queremos
  beneficiários: "" # quem ganha com essa mudança
  prova_de_possibilidade: "" # evidência de que é possível
  tom: "" # inspiração | convicção | convite
  extensão: "" # 2-3 parágrafos
```

### Bloco 4: Chamada à Ação (O Convite)

```yaml
cta:
  ação_imediata: "" # o que o leitor pode fazer agora
  ação_de_compromisso: "" # o próximo passo mais profundo
  frase_de_fechamento: "" # a frase final memorável
  mecanismo_de_adesão: "" # como a pessoa se junta
  tom: "" # convite | desafio | urgência
  extensão: "" # 1-2 parágrafos
```

## Regras de Composição

1. **Abertura deve provocar emoção** em menos de 10 segundos de leitura
2. **Contraste deve nomear o inimigo** sem atacar pessoas
3. **Visão deve ser concreta**, não abstrata — descreva cenas, não conceitos
4. **CTA deve ter fricção mínima** — a primeira ação deve levar menos de 2 minutos
5. **O manifesto completo não deve exceder 800 palavras**

## Fórmulas de Composição

| Fórmula | Ordem dos Blocos | Melhor Para |
|---------|-----------------|-------------|
| Clássica | Abertura → Contraste → Visão → CTA | Movimentos novos |
| Provocativa | Contraste → Abertura → Visão → CTA | Públicos céticos |
| Inspiracional | Visão → Abertura → Contraste → CTA | Públicos esperançosos |
| Urgente | CTA → Abertura → Contraste → Visão | Momentos de crise |

## Checklist de Qualidade

- [ ] O manifesto pode ser lido em voz alta em menos de 4 minutos?
- [ ] Provoca pelo menos uma emoção forte (raiva, esperança, pertencimento)?
- [ ] O inimigo é claro mas não é uma pessoa específica?
- [ ] A visão é memorável o suficiente para ser parafraseada?
- [ ] O CTA é executável imediatamente?

## Teste de Eficácia

| Métrica | Meta |
|---------|------|
| Taxa de leitura completa | > 60% |
| Taxa de compartilhamento | > 5% |
| Taxa de ação no CTA | > 10% |
| Citações espontâneas | > 3 frases citadas |

## Integração

- Alimentado pelo `thesis-component` (inimigo, sonho, mecanismo)
- Usa linguagem do `identity-code-component`
- Avaliado pelo `manifesto-scoring-rubric`
