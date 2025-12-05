---
title: Configurando Canais de Comunicação
description: Guia completo para configurar onde e como seu agente estará disponível
---

# Configurando Canais de Comunicação

Os **Canais** definem onde e como seus agentes estarão disponíveis para interação com usuários. Cada canal tem configurações específicas e casos de uso diferentes.

## Acessando Configuração de Canais

<Steps>
  <Step title="Abrir o Agente">
    Na lista de agentes, clique no agente que deseja configurar.
  </Step>
  <Step title="Navegar para Canais">
    Na página de detalhes do agente, clique na aba **Canais** ou **Channels**.
  </Step>
  <Step title="Visualizar Canais Disponíveis">
    Você verá uma lista de todos os canais disponíveis, mostrando quais estão ativos e quais podem ser ativados.
  </Step>
</Steps>

## Tipos de Canais

<CardGroup cols={2}>
  <Card title="Chat Web" icon="globe">
    Interface de chat integrada diretamente na plataforma Aurora AI
  </Card>
  <Card title="Chat Embed" icon="code">
    Widget para incorporar em sites e aplicações web
  </Card>
  <Card title="Slack" icon="slack">
    Integração com Slack para comunicação em canais e conversas
  </Card>
  <Card title="Telegram" icon="send">
    Integração com Telegram para comunicação via bot
  </Card>
</CardGroup>

## Canais Disponíveis

### Chat Web

<Card title="Chat Web" icon="globe">
  Interface de chat integrada diretamente na plataforma Aurora AI.
</Card>

**Características**:

- Disponível automaticamente para todos os agentes
- Interface nativa da plataforma
- Histórico persistente
- Integração completa com analytics

**Configuração**:

- Geralmente não requer configuração adicional
- Pode ser personalizado através das configurações gerais do agente

**Quando usar**:

- Testes e desenvolvimento
- Uso interno da organização
- Demonstrações e protótipos

### Chat Embed

<Card title="Chat Embed" icon="code">
  Widget para incorporar em sites e aplicações web.
</Card>

**Características**:

- Widget personalizável
- Responsivo (mobile e desktop)
- Fácil de integrar
- Estilo customizável

**Configuração**:

<Steps>
  <Step title="Ativar Canal">
    Clique em **Ativar** no canal Chat Embed.
  </Step>
  <Step title="Configurar Aparência">
    Personalize:
    
    - Cores e tema
    - Posição na página
    - Tamanho e estilo
    - Mensagem de boas-vindas
  </Step>
  <Step title="Gerar Código">
    Clique em **Gerar Código** para obter o código de incorporação.
  </Step>
  <Step title="Instalar no Site">
    Cole o código no seu site ou aplicação web.
  </Step>
</Steps>

**Campos de Configuração**:

<AccordionGroup>
  <Accordion title="Tema e Cores">
    - **Tema**: Claro, Escuro, Automático
    - **Cor Primária**: Cor principal do widget
    - **Cor de Texto**: Cor do texto
    - **Cor de Fundo**: Cor de fundo do widget
  </Accordion>
  <Accordion title="Posicionamento">
    - **Posição**: Canto inferior direito, esquerdo, ou customizado
    - **Distância das bordas**: Espaçamento da borda da tela
    - **Z-index**: Camada de sobreposição
  </Accordion>
  <Accordion title="Comportamento">
    - **Abrir automaticamente**: Abrir widget ao carregar página
    - **Mostrar badge**: Mostrar notificação de mensagens não lidas
    - **Som de notificação**: Tocar som quando receber mensagem
  </Accordion>
</AccordionGroup>

**Quando usar**:

- Sites corporativos
- Aplicações web
- Landing pages
- Portais de suporte

### Slack

<Card title="Slack" icon="slack">
  Integração com Slack para que seus agentes possam responder mensagens diretamente nos canais e conversas do Slack da sua equipe.
</Card>

**Características**:

- Comunicação através do Slack
- Respostas em canais públicos e privados
- Suporte a threads e menções
- Notificações nativas do Slack
- Integração com workspace do Slack

**Configuração**:

<Steps>
  <Step title="Ativar Canal">
    Clique em **Ativar** no canal Slack.
  </Step>
  <Step title="Preencher Credenciais">
    Você precisará fornecer:
    
    - **Token do Bot**: Token OAuth do Slack obtido ao criar o app
    - **Signing Secret**: Secret usado para verificar requisições do Slack
    - **Workspace**: Workspace do Slack onde o bot será instalado
  </Step>
  <Step title="Instalar App no Slack">
    Siga o link de instalação para adicionar o app ao seu workspace do Slack.
  </Step>
  <Step title="Verificar Conexão">
    O sistema verificará a conexão com a API do Slack.
  </Step>
  <Step title="Salvar">
    Salve as configurações. O canal estará ativo.
  </Step>
</Steps>

**Onde obter credenciais**:

- Acesse https://api.slack.com/apps
- Crie um novo app ou use um existente
- Vá para "OAuth & Permissions" e gere o token
- Copie o "Signing Secret" em "Basic Information"
- Configure as permissões necessárias (chat:write, channels:read, etc.)

**Quando usar**:

- Suporte interno da equipe
- Automação de respostas em canais
- Integração com workflows do Slack
- Notificações e alertas automatizados
- Assistente para equipes

### Telegram

<Card title="Telegram" icon="send">
  Integração com Telegram para comunicação via bot do Telegram.
</Card>

**Configuração**:

<Steps>
  <Step title="Criar Bot no Telegram">
    Use @BotFather no Telegram para criar um novo bot.
  </Step>
  <Step title="Obter Token">
    Copie o token fornecido pelo BotFather.
  </Step>
  <Step title="Ativar Canal">
    Clique em **Ativar** no canal Telegram.
  </Step>
  <Step title="Configurar">
    Preencha:
    
    - **Token do Bot**: Token obtido do BotFather
    - **Nome de Usuário**: @username do bot
  </Step>
  <Step title="Salvar">
    Salve as configurações. O bot estará ativo.
  </Step>
</Steps>

**Quando usar**:

- Comunidades no Telegram
- Suporte via Telegram
- Notificações e alertas
- Integração com grupos
- Bots públicos ou privados

## Gerenciando Canais Ativos

### Visualizar Canais Ativos

<Card title="Canais Ativos" icon="check-circle">
  Veja quais canais estão atualmente configurados e ativos para o agente.
</Card>

**Informações exibidas**:

- Nome do canal
- Status (Ativo/Inativo)
- Data de ativação
- Última atividade
- Ações disponíveis

### Editar Configuração

<Steps>
  <Step title="Localizar Canal">
    Encontre o canal na lista de canais ativos.
  </Step>
  <Step title="Abrir Configurações">
    Clique em **Editar** ou **Configurar** no canal desejado.
  </Step>
  <Step title="Modificar">
    Altere as configurações conforme necessário.
  </Step>
  <Step title="Salvar">
    Salve as alterações. O canal será atualizado.
  </Step>
</Steps>

### Desativar Canal

<Steps>
  <Step title="Abrir Canal">
    Abra o canal que deseja desativar.
  </Step>
  <Step title="Desativar">
    Clique em **Desativar** ou **Remover**.
  </Step>
  <Step title="Confirmar">
    Confirme a desativação. O canal não receberá mais mensagens.
  </Step>
</Steps>

<Warning>
  Desativar um canal interrompe a comunicação através dele. Certifique-se de que é isso que deseja fazer.
</Warning>

## Permissões e Segurança

### Restrições por Security Access

<Card title="Compatibilidade com Security Access" icon="shield">
  Alguns canais requerem configurações específicas de segurança do agente.
</Card>

**Canais que podem ter restrições**:

- Alguns canais públicos podem requerer `PUBLIC` ou `ORGANIZATION`
- Canais internos podem requerer `ORGANIZATION` ou `TEAM`
- Verifique as mensagens de aviso ao ativar canais

**Como resolver**:

1. Veja a mensagem de aviso ao tentar ativar
2. Ajuste o Security Access do agente se necessário
3. Tente ativar o canal novamente

## Testando Canais

<Card title="Testar Configuração" icon="play">
  Sempre teste os canais após configurá-los para garantir que estão funcionando corretamente.
</Card>

<Steps>
  <Step title="Configurar Canal">
    Complete a configuração do canal conforme instruções.
  </Step>
  <Step title="Usar Botão de Teste">
    Se disponível, use o botão **Testar** para verificar a conexão.
  </Step>
  <Step title="Testar Manualmente">
    Envie uma mensagem de teste através do canal:
    
    - Para Chat Web: Use a interface diretamente
    - Para Chat Embed: Abra o site com o widget
    - Para Slack: Envie mensagem em um canal ou conversa direta
    - Para Telegram: Envie mensagem para o bot configurado
  </Step>
  <Step title="Verificar Resposta">
    Confirme que o agente respondeu corretamente.
  </Step>
</Steps>

## Monitorando Canais

### Métricas por Canal

<Card title="Métricas de Canais" icon="bar-chart">
  Acompanhe performance de cada canal individualmente.
</Card>

**Métricas disponíveis**:

- Número de conversas por canal
- Volume de mensagens
- Taxa de resposta
- Tempo médio de resposta
- Satisfação do usuário

**Como acessar**:

- Vá para Analytics do agente
- Filtre por canal específico
- Veja métricas detalhadas

## Próximos Passos

<CardGroup cols={2}>
  <Card title="Ver Analytics" icon="bar-chart" href="/agent/pt-BR/analytics">
    Monitore performance dos canais
  </Card>
  <Card title="Gerenciar Conversas" icon="message-square" href="/agent/pt-BR/conversations">
    Veja conversas por canal
  </Card>
  <Card title="Personalizar Embed" icon="code" href="/geral/pt-BR/chat/embed">
    Personalize widget de chat embed
  </Card>
  <Card title="Configurar Chat Web" icon="message" href="/geral/pt-BR/chat/web">
    Configure a interface de chat web
  </Card>
</CardGroup>

## Dicas

<Tip>
  **Teste Sempre**: Sempre teste canais após configuração para garantir funcionamento.
</Tip>

<Tip>
  **Comece Simples**: Comece com Chat Web para testes, depois adicione outros canais.
</Tip>

<Tip>
  **Monitore Performance**: Acompanhe métricas de cada canal para otimizar.
</Tip>

<Tip>
  **Mantenha Credenciais Seguras**: Nunca compartilhe tokens ou credenciais de API.
</Tip>

<Tip>
  **Documente Configurações**: Mantenha registro das configurações para referência futura.
</Tip>

## Troubleshooting

<AccordionGroup>
  <Accordion title="Canal não está recebendo mensagens">
    Verifique:
    
    - Se o canal está ativo
    - Se as credenciais estão corretas
    - Se há erros na configuração
    - Se o bot está instalado corretamente (Slack/Telegram)
    - Se as permissões estão configuradas corretamente (Slack)
  </Accordion>
  <Accordion title="Mensagens não estão sendo respondidas">
    Verifique:
    
    - Se o agente está publicado
    - Se há erros nos logs
    - Se o modelo está configurado corretamente
    - Se há problemas de conectividade
  </Accordion>
  <Accordion title="Erro ao ativar canal">
    Verifique:
    
    - Se tem permissões necessárias
    - Se o Security Access do agente é compatível
    - Se as credenciais estão corretas
    - Se há limites do plano que impedem ativação
  </Accordion>
</AccordionGroup>
