---
title: Gerenciando Conversas do Agente
description: Visualize, gerencie e analise todas as conversas do seu agente
---

# Gerenciando Conversas do Agente

A página de **Conversas** permite visualizar, gerenciar e analisar todas as interações que os usuários tiveram com seu agente.

## Acessando Conversas

<Steps>
  <Step title="Abrir o Agente">
    Na lista de agentes, clique no agente desejado.
  </Step>
  <Step title="Navegar para Conversas">
    Na página de detalhes do agente, clique na aba **Conversas**.
  </Step>
  <Step title="Visualizar Lista">
    Você verá uma lista de todas as conversas do agente, ordenadas por data (mais recentes primeiro).
  </Step>
</Steps>

## Visualizando Conversas

### Lista de Conversas

<Card title="Estrutura da Lista" icon="list">
  Cada conversa na lista mostra informações importantes.
</Card>

**Informações exibidas**:

- **Usuário**: Nome ou identificador do usuário que iniciou a conversa
- **Data/Hora**: Quando a conversa foi iniciada
- **Status**: Ativa, Finalizada, Arquivada
- **Mensagens**: Número de mensagens na conversa
- **Canal**: Onde a conversa ocorreu (Chat Web, Embed, etc.)
- **Preview**: Prévia da primeira mensagem ou última mensagem

### Filtrar Conversas

<Card title="Filtros Disponíveis" icon="filter">
  Use filtros para encontrar conversas específicas rapidamente.
</Card>

**Filtros disponíveis**:

<AccordionGroup>
  <Accordion title="Por Status">
    Filtre por status da conversa:
    
    - **Todas**: Mostra todas as conversas
    - **Ativas**: Apenas conversas em andamento
    - **Finalizadas**: Conversas concluídas
    - **Arquivadas**: Conversas arquivadas
  </Accordion>
  <Accordion title="Por Período">
    Filtre por data:
    
    - **Hoje**: Conversas de hoje
    - **Últimos 7 dias**: Última semana
    - **Últimos 30 dias**: Último mês
    - **Personalizado**: Escolha datas específicas
  </Accordion>
  <Accordion title="Por Canal">
    Filtre por onde a conversa ocorreu:
    
    - **Chat Web**: Interface integrada
    - **Chat Embed**: Widget incorporado
    - **Outros canais**: Conforme configurados
  </Accordion>
  <Accordion title="Por Usuário">
    Digite o nome ou email do usuário para filtrar conversas específicas.
  </Accordion>
</AccordionGroup>

### Buscar Conversas

<Card title="Busca de Conversas" icon="search">
  Use a barra de busca para encontrar conversas específicas.
</Card>

**O que você pode buscar**:
- Texto das mensagens
- Nome do usuário
- Tópicos discutidos
- Palavras-chave específicas

**Como usar**:
1. Digite o termo de busca na barra de busca
2. Os resultados são filtrados em tempo real
3. Clique em uma conversa para abrir e ver detalhes

## Abrindo uma Conversa

<Steps>
  <Step title="Clicar na Conversa">
    Clique em qualquer conversa da lista para abri-la.
  </Step>
  <Step title="Visualizar Detalhes">
    A conversa será aberta mostrando:
    
    - Todas as mensagens em ordem cronológica
    - Informações do usuário
    - Metadados da conversa
    - Ações disponíveis
  </Step>
</Steps>

### Visualização da Conversa

<Card title="Interface da Conversa" icon="message-square">
  A visualização mostra o histórico completo da conversa.
</Card>

**Elementos da interface**:

- **Cabeçalho**: Informações do usuário e metadados
- **Mensagens**: Histórico completo em ordem cronológica
  - Mensagens do usuário aparecem à direita
  - Respostas do agente aparecem à esquerda
  - Timestamp de cada mensagem
- **Barra de ações**: Botões para ações na conversa
- **Campo de mensagem**: Para adicionar notas ou comentários (se disponível)

## Gerenciando Conversas

### Arquivar Conversa

<Card title="Arquivar Conversa" icon="archive">
  Move a conversa para arquivo, mantendo-a acessível mas removendo da lista principal.
</Card>

<Steps>
  <Step title="Abrir a Conversa">
    Clique na conversa que deseja arquivar.
  </Step>
  <Step title="Clicar em Arquivar">
    Procure pelo botão **Arquivar** ou menu de ações.
  </Step>
  <Step title="Confirmar">
    A conversa será movida para arquivo e não aparecerá mais na lista principal.
  </Step>
</Steps>

**Quando arquivar**:
- Conversas resolvidas que não precisam mais de atenção
- Conversas antigas para organização
- Limpar lista principal mantendo histórico

**Acessar arquivadas**:
- Use o filtro "Arquivadas" para ver conversas arquivadas
- Você pode desarquivar a qualquer momento

### Desarquivar Conversa

<Steps>
  <Step title="Filtrar Arquivadas">
    Use o filtro de status para mostrar apenas conversas arquivadas.
  </Step>
  <Step title="Abrir Conversa">
    Clique na conversa arquivada desejada.
  </Step>
  <Step title="Desarquivar">
    Clique em **Desarquivar** para mover de volta à lista principal.
  </Step>
</Steps>

### Excluir Conversa

<Card title="Excluir Conversa" icon="trash">
  Remove permanentemente a conversa do sistema.
</Card>

<Warning>
  **Atenção**: Esta ação não pode ser desfeita! A conversa será removida permanentemente.
</Warning>

<Steps>
  <Step title="Abrir a Conversa">
    Clique na conversa que deseja excluir.
  </Step>
  <Step title="Abrir Menu de Ações">
    Procure pelo menu de ações ou botão de opções.
  </Step>
  <Step title="Selecionar Excluir">
    Clique em **Excluir** ou **Remover**.
  </Step>
  <Step title="Confirmar">
    Confirme a exclusão. A conversa será removida permanentemente.
  </Step>
</Steps>

**Quando excluir**:
- Conversas de teste
- Conversas com informações sensíveis que precisam ser removidas
- Limpeza de dados antigos

### Adicionar Notas

<Card title="Adicionar Notas" icon="sticky-note">
  Adicione notas internas sobre a conversa para referência futura.
</Card>

**Uso**:
- Marcar conversas importantes
- Anotar ações tomadas
- Documentar problemas ou soluções
- Referências para a equipe

<Steps>
  <Step title="Abrir Conversa">
    Abra a conversa onde deseja adicionar nota.
  </Step>
  <Step title="Adicionar Nota">
    Procure pela opção **Adicionar Nota** ou campo de notas.
  </Step>
  <Step title="Escrever e Salvar">
    Digite sua nota e salve. A nota ficará associada à conversa.
  </Step>
</Steps>

## Analisando Conversas

### Métricas da Conversa

<Card title="Métricas Individuais" icon="bar-chart">
  Cada conversa pode mostrar métricas específicas.
</Card>

**Métricas disponíveis**:

- **Duração**: Quanto tempo durou a conversa
- **Número de mensagens**: Total de mensagens trocadas
- **Tempo médio de resposta**: Tempo que o agente levou para responder
- **Sentimento**: Análise de sentimento da conversa
- **Resolvida**: Se o problema foi resolvido (se aplicável)

### Identificar Padrões

<Card title="Análise de Padrões" icon="trending-up">
  Analise múltiplas conversas para identificar padrões.
</Card>

**O que procurar**:

- **Perguntas frequentes**: Quais perguntas aparecem mais
- **Problemas comuns**: Tópicos que causam dificuldades
- **Pontos de abandono**: Onde usuários param de conversar
- **Tópicos bem resolvidos**: O que o agente faz bem
- **Lacunas de conhecimento**: O que o agente não sabe responder

**Como analisar**:

<Steps>
  <Step title="Revisar Múltiplas Conversas">
    Abra várias conversas e revise o conteúdo.
  </Step>
  <Step title="Identificar Padrões">
    Procure por temas, perguntas ou problemas recorrentes.
  </Step>
  <Step title="Documentar Descobertas">
    Anote padrões identificados para ação futura.
  </Step>
  <Step title="Tomar Ação">
    Use os insights para melhorar o agente:
    
    - Adicionar conhecimento sobre tópicos frequentes
    - Melhorar respostas para problemas comuns
    - Ajustar personalidade se necessário
  </Step>
</Steps>

## Exportando Conversas

<Card title="Exportar Conversas" icon="download">
  Exporte conversas para análise externa ou backup.
</Card>

### Exportar Conversa Individual

<Steps>
  <Step title="Abrir Conversa">
    Abra a conversa que deseja exportar.
  </Step>
  <Step title="Clicar em Exportar">
    Procure pelo botão **Exportar** ou opção no menu.
  </Step>
  <Step title="Escolher Formato">
    Selecione o formato:
    
    - **TXT**: Texto simples
    - **PDF**: Documento formatado
    - **JSON**: Dados estruturados
    - **Markdown**: Formato markdown
  </Step>
  <Step title="Baixar">
    O arquivo será gerado e baixado automaticamente.
  </Step>
</Steps>

### Exportar Múltiplas Conversas

<Steps>
  <Step title="Selecionar Conversas">
    Na lista de conversas, selecione as conversas desejadas usando checkboxes.
  </Step>
  <Step title="Abrir Menu de Ações em Lote">
    Procure pelo botão de ações em lote ou menu de exportação.
  </Step>
  <Step title="Escolher Formato">
    Selecione o formato de exportação desejado.
  </Step>
  <Step title="Exportar">
    Todas as conversas selecionadas serão exportadas em um único arquivo.
  </Step>
</Steps>

## Compartilhando Conversas

<Card title="Compartilhar Conversas" icon="share">
  Compartilhe conversas com sua equipe para colaboração.
</Card>

<Steps>
  <Step title="Abrir Conversa">
    Abra a conversa que deseja compartilhar.
  </Step>
  <Step title="Clicar em Compartilhar">
    Procure pelo botão **Compartilhar** ou opção no menu.
  </Step>
  <Step title="Escolher Método">
    Selecione como compartilhar:
    
    - **Link**: Copiar link compartilhável
    - **Email**: Enviar por email
    - **Equipe**: Compartilhar com membros específicos
  </Step>
  <Step title="Completar Ação">
    Complete o compartilhamento conforme o método escolhido.
  </Step>
</Steps>

## Usando Conversas para Melhorar o Agente

### Identificar Problemas

<Card title="Sinais de Problemas" icon="alert-circle">
  Use conversas para identificar quando o agente precisa de melhorias.
</Card>

**Sinais de alerta**:

- Conversas muito curtas (usuário desiste rápido)
- Múltiplas tentativas da mesma pergunta
- Sentimento negativo consistente
- Usuários pedindo para falar com humano
- Perguntas não respondidas adequadamente

### Ações Corretivas

<Steps>
  <Step title="Identificar Problema">
    Revise conversas para identificar problemas específicos.
  </Step>
  <Step title="Analisar Causa">
    Entenda por que o problema está ocorrendo:
    
    - Falta de conhecimento?
    - Personalidade inadequada?
    - Configurações incorretas?
  </Step>
  <Step title="Implementar Correção">
    Faça as alterações necessárias:
    
    - Adicione conhecimento relevante
    - Ajuste personalidade
    - Corrija configurações
  </Step>
  <Step title="Monitorar">
    Acompanhe novas conversas para verificar se o problema foi resolvido.
  </Step>
</Steps>

## Próximos Passos

<CardGroup cols={2}>
  <Card title="Ver Analytics" icon="bar-chart" href="/docs/agents/analytics">
    Analise métricas agregadas do agente
  </Card>
  <Card title="Configurar Canais" icon="radio" href="/docs/agents/channels">
    Configure onde o agente está disponível
  </Card>
  <Card title="Otimizar Agente" icon="settings" href="/docs/agents/creating-editing">
    Use insights das conversas para melhorar
  </Card>
  <Card title="Testar Melhorias" icon="play" href="/docs/agents/testing">
    Teste mudanças antes de publicar
  </Card>
</CardGroup>

## Dicas

<Tip>
  **Revise Regularmente**: Configure tempo semanal para revisar conversas e identificar padrões.
</Tip>

<Tip>
  **Foque em Conversas Problemáticas**: Priorize análise de conversas com sentimento negativo ou problemas.
</Tip>

<Tip>
  **Documente Insights**: Mantenha registro de descobertas para referência futura.
</Tip>

<Tip>
  **Aja Rapidamente**: Quando identificar problemas, corrija rapidamente para melhorar experiência.
</Tip>

