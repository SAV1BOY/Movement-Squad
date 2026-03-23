# Sentiment Analysis — Análise de Sentimento

## Visão Geral

Mede como as pessoas se sentem em relação ao movimento, suas mensagens
e ações. Sentimento é o termômetro emocional do movimento — indica se
estamos gerando conexão genuína ou apenas ruído.

## Por que Medir Sentimento

Métricas quantitativas (alcance, engajamento, crescimento) não dizem
COMO as pessoas se sentem. Um post com 1000 comentários pode ser
adorado ou odiado. Sentimento diferencia os dois cenários.

## Dimensões de Sentimento

### 1. Sentimento Geral
A percepção ampla sobre o movimento — positivo, neutro ou negativo.
```
Score Geral = (Menções positivas - Menções negativas) / Total
Escala: -1.0 a +1.0
Meta: > +0.5
```

### 2. Sentimento de Pertencimento
Os membros sentem que pertencem? Medido via pesquisa direta:
- "Eu me sinto parte deste movimento" (escala 1-10)
- "As pessoas aqui entendem meus desafios" (escala 1-10)
- Meta: Média > 7.5

### 3. Sentimento de Empoderamento
O movimento faz as pessoas se sentirem capazes de mudar algo?
- "Este movimento me dá ferramentas para agir" (escala 1-10)
- "Sinto que posso fazer diferença" (escala 1-10)
- Meta: Média > 7.0

### 4. Sentimento de Autenticidade
As pessoas percebem o movimento como genuíno?
- "Este movimento é autêntico, não é marketing disfarçado" (escala 1-10)
- Meta: Média > 8.0 (crucial para sobrevivência do movimento)

## Fontes de Dados

### Análise Automatizada
- Social listening com análise de sentimento por NLP
- Monitoramento de menções com classificação automática
- Análise de tom em comentários e threads
- **Limitação**: NLP erra contexto, ironia e nuance — sempre validar

### Pesquisa Direta
- Pesquisa mensal com membros da comunidade (4 dimensões acima)
- Perguntas abertas para capturar nuances
- NPS como proxy de sentimento geral

### Análise Qualitativa
- Leitura manual de comentários e DMs pelo Anthropologist
- Notas etnográficas sobre tom e emoção observados
- Entrevistas com foco em percepção emocional

## Thresholds e Alertas

| Score Geral  | Status    | Ação                                       |
|--------------|-----------|---------------------------------------------|
| > +0.7       | Excelente | Manter e escalar                             |
| +0.5 a +0.7  | Bom       | Monitorar e otimizar                         |
| +0.2 a +0.5  | Atenção   | Investigar causas de sentimento misto        |
| 0 a +0.2     | Alerta    | Revisar mensagem e contra-narrativas         |
| < 0          | Crise     | Ação imediata: parar, ouvir, recalibrar      |

## Triggers de Investigação

Investigar imediatamente quando:
- Score geral cair mais de 0.2 em uma semana
- Autenticidade cair abaixo de 7.0
- Surgir padrão de comentários negativos sobre o mesmo tema
- Champion reportar mudança de sentimento na comunidade

## Dashboard de Sentimento

```
─── SENTIMENTO — Semana [DD/MM] a [DD/MM] ────────────────
Score Geral:        [+X.XX]  (anterior: [+X.XX])  [↑/↓/→]
Pertencimento:      [X.X]/10
Empoderamento:      [X.X]/10
Autenticidade:      [X.X]/10
Menções positivas:  [XX%]
Menções neutras:    [XX%]
Menções negativas:  [XX%]
──────────────────────────────────────────────────────────
```

## Cadência

- **Análise automatizada**: Contínua, report semanal
- **Pesquisa direta**: Mensal
- **Análise qualitativa**: Quinzenal
- **Revisão profunda**: Trimestral

## Responsável

**Metrics Analyst** coleta dados quantitativos. **Anthropologist Agent**
faz análise qualitativa. **Chief of Movement** decide ações corretivas.
