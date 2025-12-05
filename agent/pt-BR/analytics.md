---
title: Analytics e Métricas do Agente
description: Acompanhe performance, uso e métricas detalhadas dos seus agentes
---

# Analytics e Métricas do Agente

A página de **Analytics** fornece insights detalhados sobre o desempenho e uso dos seus agentes, ajudando você a entender como os usuários interagem com eles e onde há oportunidades de melhoria.

## Acessando Analytics

<Steps>
  <Step title="Abrir o Agente">
    Na lista de agentes, clique no agente que deseja analisar.
  </Step>
  <Step title="Navegar para Analytics">
    Na página de detalhes do agente, clique na aba **Analytics** ou **Métricas**.
  </Step>
  <Step title="Selecionar Período">
    Use o seletor de período no topo para escolher o intervalo de análise.
  </Step>
</Steps>

## Selecionando Período

<Card title="Períodos Disponíveis" icon="calendar">
  Escolha o intervalo de tempo para análise das métricas.
</Card>

**Opções disponíveis**:

- **Últimos 7 dias**: Análise semanal recente
- **Últimos 30 dias**: Análise mensal (padrão)
- **Últimos 90 dias**: Análise trimestral
- **Personalizado**: Escolha datas específicas de início e fim

<Info>
  Períodos mais longos fornecem uma visão mais ampla, enquanto períodos mais curtos mostram tendências recentes.
</Info>

## Métricas Principais

A página de Analytics exibe várias métricas organizadas em cards. Vamos entender cada uma:

### Score Médio de Sentimento

<Card title="Score Médio de Sentimento" icon="smile">
  Mede a satisfação geral dos usuários com as interações do agente.
</Card>

**O que é**:  
Análise de sentimento das conversas para determinar se as interações foram positivas, neutras ou negativas.

**Valores**:
- **0-40**: Sentimento negativo (precisa atenção)
- **41-60**: Sentimento neutro
- **61-80**: Sentimento positivo
- **81-100**: Sentimento muito positivo

**Como melhorar**:
- Revise conversas com sentimento negativo
- Ajuste personalidade e tom de voz
- Melhore conhecimento e respostas
- Adicione mais contexto ao agente

### Lacunas de Conhecimento

<Card title="Lacunas de Conhecimento" icon="alert-circle">
  Identifica perguntas que o agente não conseguiu responder adequadamente.
</Card>

**O que é**:  
Total de perguntas ou situações onde o agente não tinha conhecimento suficiente para fornecer uma resposta adequada.

**Como usar**:
- Revise as lacunas identificadas
- Adicione documentos relevantes à base de conhecimento
- Atualize o Prompt do Sistema se necessário
- Crie regras personalizadas para casos específicos

**Dicas**:
- Lacunas frequentes indicam necessidade de mais conhecimento
- Use para priorizar quais documentos adicionar
- Monitore tendências ao longo do tempo

### Tempo Médio de Resposta

<Card title="Tempo Médio de Resposta" icon="clock">
  Tempo que o agente leva para responder às mensagens dos usuários.
</Card>

**O que é**:  
Tempo médio (em segundos) desde que o usuário envia uma mensagem até o agente responder.

**Interpretação**:
- **< 2 segundos**: Muito rápido (excelente)
- **2-5 segundos**: Rápido (bom)
- **5-10 segundos**: Aceitável
- **> 10 segundos**: Lento (pode melhorar)

**Como melhorar**:
- Otimize o Prompt do Sistema (mais direto)
- Reduza tamanho máximo de tokens se muito alto
- Use cache de respostas quando apropriado
- Considere modelo mais rápido se disponível

### Tempo Médio no Período

<Card title="Tempo Médio no Período" icon="clock">
  Tempo médio de resposta calculado especificamente para o período selecionado.
</Card>

**Diferença do Tempo Médio Geral**:  
Esta métrica mostra apenas o período selecionado, enquanto "Tempo Médio de Resposta" mostra a média histórica total.

**Uso**:  
Compare com o tempo médio geral para identificar se a performance melhorou ou piorou recentemente.

### Total de Conversas

<Card title="Total de Conversas" icon="bar-chart-3">
  Número total de conversas que o agente teve desde sua criação.
</Card>

**O que inclui**:
- Todas as conversas iniciadas
- Conversas ativas e finalizadas
- Diferentes canais e interfaces

**Como usar**:
- Acompanhe crescimento ao longo do tempo
- Compare com outros agentes
- Identifique tendências de uso

### Total de Mensagens

<Card title="Total de Mensagens" icon="message-square">
  Número total de mensagens trocadas em todas as conversas.
</Card>

**O que inclui**:
- Mensagens dos usuários
- Respostas do agente
- Mensagens do sistema (se aplicável)

**Relação com Conversas**:  
Divida mensagens por conversas para obter a média de mensagens por conversa, indicando engajamento.

### Conversas Mensais

<Card title="Conversas Mensais" icon="trending-up">
  Número de conversas no mês atual ou no período selecionado.
</Card>

**Uso**:  
Acompanhe atividade mensal para identificar:
- Crescimento ou declínio de uso
- Padrões sazonais
- Impacto de mudanças ou campanhas

### Mensagens Mensais

<Card title="Mensagens Mensais" icon="message-square">
  Número de mensagens no mês atual ou no período selecionado.
</Card>

**Uso**:  
Combine com conversas mensais para entender:
- Engajamento médio por conversa
- Profundidade das interações
- Tendências de uso

### Total de Créditos

<Card title="Total de Créditos" icon="coins">
  Total de créditos consumidos pelo agente desde sua criação.
</Card>

**O que são créditos**:  
Unidades de consumo que medem o uso de recursos do modelo de IA. Cada mensagem processada consome créditos.

**Como usar**:
- Monitore custos do agente
- Compare eficiência entre agentes
- Planeje orçamento baseado em uso

### Créditos Mensais

<Card title="Créditos Mensais" icon="coins">
  Créditos consumidos no mês atual ou no período selecionado.
</Card>

**Uso**:  
Acompanhe consumo mensal para:
- Gerenciar orçamento
- Identificar picos de uso
- Otimizar custos

### Usuários Ativos

<Card title="Usuários Ativos" icon="users">
  Número de usuários únicos que interagiram com o agente.
</Card>

**O que é**:  
Contagem de usuários distintos que iniciaram pelo menos uma conversa com o agente.

**Como usar**:
- Acompanhe crescimento da base de usuários
- Compare com total de conversas para entender frequência
- Identifique usuários recorrentes vs novos

### Mensagens por Conversa

<Card title="Mensagens por Conversa" icon="message-square">
  Média de mensagens trocadas por conversa.
</Card>

**O que indica**:
- **Baixo (1-3)**: Conversas rápidas, respostas diretas
- **Médio (4-8)**: Engajamento moderado
- **Alto (9+)**: Conversas profundas, alto engajamento

**Como usar**:
- Avalie qualidade das interações
- Identifique se usuários estão satisfeitos (conversas curtas podem indicar problemas resolvidos rapidamente ou frustração)
- Compare com outros agentes

## Gráficos e Visualizações

### Gráfico de Conversas Diárias

<Card title="Conversas ao Longo do Tempo" icon="line-chart">
  Visualize o número de conversas por dia no período selecionado.
</Card>

**O que mostra**:
- Tendências diárias de uso
- Picos e quedas de atividade
- Padrões semanais ou sazonais

**Como usar**:
- Identifique dias de maior atividade
- Compare períodos diferentes
- Identifique tendências de crescimento ou declínio

### Gráfico de Mensagens Diárias

<Card title="Mensagens ao Longo do Tempo" icon="activity">
  Visualize o número de mensagens por dia no período selecionado.
</Card>

**Uso**:  
Combine com gráfico de conversas para entender:
- Se conversas estão ficando mais longas ou curtas
- Padrões de engajamento
- Relação entre volume de conversas e mensagens

### Gráfico de Créditos Diários

<Card title="Consumo de Créditos" icon="trending-up">
  Visualize o consumo de créditos por dia.
</Card>

**Uso**:  
Monitore custos diários para:
- Identificar picos de consumo
- Planejar orçamento
- Otimizar uso de recursos

## Conversas Ativas

<Card title="Conversas Ativas" icon="message-circle">
  Número de conversas que estão em andamento no momento.
</Card>

**O que é**:  
Conversas que foram iniciadas mas ainda não foram finalizadas ou arquivadas.

**Uso**:  
Acompanhe carga atual do agente:
- Muitas conversas ativas podem indicar alta demanda
- Poucas conversas ativas podem indicar baixo engajamento ou problemas

## Interpretando as Métricas

### Indicadores de Saúde do Agente

<CardGroup cols={2}>
  <Card title="✅ Agente Saudável" icon="check-circle">
    - Score de sentimento > 70
    - Tempo de resposta < 5 segundos
    - Poucas lacunas de conhecimento
    - Crescimento consistente de conversas
    - Engajamento adequado (mensagens por conversa)
  </Card>
  <Card title="⚠️ Precisa Atenção" icon="alert-triangle">
    - Score de sentimento < 50
    - Tempo de resposta > 10 segundos
    - Muitas lacunas de conhecimento
    - Declínio de conversas
    - Engajamento muito baixo ou muito alto
  </Card>
</CardGroup>

### Análise Comparativa

Compare métricas entre períodos:

<Steps>
  <Step title="Selecionar Período Anterior">
    Anote as métricas do período anterior (ex: mês passado).
  </Step>
  <Step title="Selecionar Período Atual">
    Veja as métricas do período atual (ex: este mês).
  </Step>
  <Step title="Comparar">
    Compare as métricas para identificar:
    
    - Melhorias ou declínios
    - Impacto de mudanças feitas
    - Tendências de longo prazo
  </Step>
</Steps>

## Ações Baseadas em Métricas

### Se Score de Sentimento Está Baixo

<Steps>
  <Step title="Revisar Conversas">
    Abra conversas com sentimento negativo para entender o problema.
  </Step>
  <Step title="Identificar Padrões">
    Procure por padrões nas conversas problemáticas.
  </Step>
  <Step title="Ajustar Configurações">
    - Melhore o Prompt do Sistema
    - Ajuste tom de voz e formalidade
    - Adicione conhecimento relevante
  </Step>
  <Step title="Testar">
    Use o playground para testar melhorias antes de publicar.
  </Step>
</Steps>

### Se Há Muitas Lacunas de Conhecimento

<Steps>
  <Step title="Identificar Tópicos">
    Veja quais perguntas não foram respondidas adequadamente.
  </Step>
  <Step title="Adicionar Conhecimento">
    - Faça upload de documentos relevantes
    - Crie coleções específicas
    - Atualize informações desatualizadas
  </Step>
  <Step title="Melhorar Prompt">
    Adicione instruções específicas sobre como lidar com tópicos comuns.
  </Step>
</Steps>

### Se Tempo de Resposta Está Alto

<Steps>
  <Step title="Otimizar Prompt">
    Torne o Prompt do Sistema mais direto e eficiente.
  </Step>
  <Step title="Ajustar Configurações">
    - Reduza Max Allowed Tokens se muito alto
    - Habilite Response Cache se apropriado
    - Considere modelo mais rápido
  </Step>
  <Step title="Revisar Ferramentas">
    Verifique se ferramentas conectadas não estão causando lentidão.
  </Step>
</Steps>

## Exportando Dados

<Card title="Exportar Analytics" icon="download">
  Exporte métricas para análise externa ou relatórios.
</Card>

<Steps>
  <Step title="Acessar Opções de Exportação">
    Procure pelo botão de exportação na página de Analytics.
  </Step>
  <Step title="Escolher Formato">
    Selecione o formato desejado:
    
    - **CSV**: Para análise em planilhas
    - **PDF**: Para relatórios e apresentações
    - **JSON**: Para integração com outras ferramentas
  </Step>
  <Step title="Selecionar Dados">
    Escolha quais métricas e período incluir no export.
  </Step>
  <Step title="Baixar">
    O arquivo será gerado e baixado automaticamente.
  </Step>
</Steps>

## Próximos Passos

<CardGroup cols={2}>
  <Card title="Gerenciar Conversas" icon="message-square" href="/docs/agents/conversations">
    Veja e gerencie conversas individuais do agente
  </Card>
  <Card title="Configurar Canais" icon="radio" href="/docs/agents/channels">
    Configure onde o agente está disponível
  </Card>
  <Card title="Otimizar Agente" icon="settings" href="/docs/agents/creating-editing">
    Use métricas para melhorar o agente
  </Card>
  <Card title="Testar Mudanças" icon="play" href="/docs/agents/testing">
    Teste melhorias antes de publicar
  </Card>
</CardGroup>

## Dicas

<Tip>
  **Revise Analytics Regularmente**: Configure um lembrete para revisar métricas semanalmente ou mensalmente.
</Tip>

<Tip>
  **Compare Períodos**: Use períodos personalizados para comparar performance antes e depois de mudanças.
</Tip>

<Tip>
  **Foque em Tendências**: Uma única métrica pode não ser significativa, mas tendências ao longo do tempo são valiosas.
</Tip>

<Tip>
  **Aja Rapidamente**: Quando identificar problemas, aja rapidamente para melhorar a experiência do usuário.
</Tip>

