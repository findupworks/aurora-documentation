---
title: Criando e Editando Agentes
description: Guia completo passo a passo para criar e editar agentes no Aurora AI
---

# Criando e Editando Agentes

Os **Agentes** são assistentes de IA personalizados que podem conversar com usuários, executar tarefas e automatizar processos. Este guia mostra como criar e editar agentes no Aurora AI.

<CardGroup cols={2}>
  <Card title="Agente Básico" icon="robot">
    Agente conversacional padrão com personalidade e conhecimento configuráveis
  </Card>
  <Card title="Agente Workflow" icon="workflow">
    Agente integrado com workflows para automações complexas
  </Card>
</CardGroup>

## Visão Geral

Um agente no Aurora AI é composto por várias seções configuráveis:

- **Informações Básicas**: Nome, descrição e status
- **Personalidade**: Tom de voz, estilo e comportamento
- **Conhecimento**: Documentos e coleções RAG
- **Canais**: Onde o agente estará disponível
- **Ferramentas**: Integrações e capacidades adicionais

## Criando um Novo Agente

<Steps>
  <Step title="Acessar o Builder de Agentes">
    No menu lateral, clique em **Builder** e selecione **Agentes**. Você verá a lista de agentes existentes.
  </Step>
  <Step title="Escolher o Tipo de Agente">
    Clique em **Criar Novo Agente** e escolha o tipo:
    
    - **Agente Básico**: Para conversas e interações diretas
    - **Agente Workflow**: Para integração com workflows automatizados
  </Step>
  <Step title="Preencher Informações Básicas">
    No diálogo de criação, preencha:
    
    - **Nome**: Um nome descritivo para seu agente (ex: "Assistente de Suporte")
    - **Descrição**: Explique o propósito do agente (opcional)
    
    Clique em **Criar** para continuar.
  </Step>
  <Step title="Ser Redirecionado para Edição">
    Após criar, você será redirecionado automaticamente para a página de edição do agente, onde poderá configurar todas as opções.
  </Step>
</Steps>

## Editando um Agente Existente

Para editar um agente existente:

<Steps>
  <Step title="Localizar o Agente">
    Na lista de agentes, encontre o agente que deseja editar. Use a busca ou filtros se necessário.
  </Step>
  <Step title="Abrir o Agente">
    Clique no card do agente ou no nome para abrir a página de detalhes.
  </Step>
  <Step title="Navegar para Edição">
    Na página de detalhes, você verá várias abas. A aba **Básico** contém as configurações principais do agente.
  </Step>
</Steps>

## Seções de Configuração

A página de edição do agente está organizada em seções. Vamos explorar cada uma:

### 1. Informações Básicas

<Card title="Campos Básicos" icon="info">
  Configure as informações fundamentais do agente.
</Card>

**Campos disponíveis:**

- **Nome**: Nome do agente (obrigatório)
- **Descrição**: Descrição do propósito e função do agente
- **Status**: Escolha entre:
  - `Rascunho`: Agente não está publicado
  - `Publicado`: Agente está ativo e disponível

<Warning>
  Apenas agentes com status "Publicado" estarão disponíveis nos canais configurados.
</Warning>

### 2. Personalidade (Persona)

<Card title="Configurar Personalidade" icon="user">
  Defina como o agente se comporta e responde aos usuários.
</Card>

A seção de personalidade permite configurar:

<AccordionGroup>
  <Accordion title="Tom de Voz">
    Escolha o estilo de comunicação:
    
    - **Formal**: Linguagem profissional e respeitosa
    - **Casual**: Conversação descontraída e amigável
    - **Técnico**: Foco em precisão e detalhes técnicos
    - **Criativo**: Linguagem expressiva e envolvente
    
    Você também pode escrever instruções customizadas para definir um tom específico.
  </Accordion>
  <Accordion title="Estilo de Resposta">
    Configure como o agente estrutura suas respostas:
    
    - **Direto**: Respostas curtas e objetivas
    - **Detalhado**: Explicações completas e contextuais
    - **Conversacional**: Diálogo natural e interativo
    - **Estruturado**: Informações organizadas em listas e seções
  </Accordion>
  <Accordion title="Comportamento">
    Defina regras de comportamento:
    
    - **Empatia**: Nível de compreensão emocional
    - **Assertividade**: Capacidade de tomar decisões
    - **Criatividade**: Uso de soluções inovadoras
    - **Precisão**: Foco em exatidão e fatos
  </Accordion>
</AccordionGroup>

<Info>
  A personalidade é fundamental para criar uma experiência consistente. Teste diferentes configurações no playground antes de publicar.
</Info>

### 3. Placeholder de Input

<Card title="Placeholder de Input" icon="input">
  Configure o texto que aparece no campo de entrada antes do usuário digitar.
</Card>

Este campo define o texto de exemplo que aparece no campo de chat antes do usuário começar a digitar. Exemplos:

- "Digite sua pergunta aqui..."
- "Como posso ajudar você hoje?"
- "Pergunte qualquer coisa sobre nosso produto"

### 4. Iniciadores de Conversa

<Card title="Iniciadores de Conversa" icon="message-square">
  Adicione perguntas pré-definidas que os usuários podem clicar para começar.
</Card>

Os iniciadores de conversa são perguntas ou frases que aparecem como botões no início da conversa, facilitando o início da interação.

<Steps>
  <Step title="Adicionar Iniciador">
    Clique no botão **Adicionar Iniciador** ou **+** na seção de iniciadores.
  </Step>
  <Step title="Escrever o Texto">
    Digite a pergunta ou frase que aparecerá como botão (ex: "Como funciona o produto?").
  </Step>
  <Step title="Escolher Ícone (Opcional)">
    Selecione um ícone para o iniciador para torná-lo mais visualmente atraente.
  </Step>
  <Step title="Salvar">
    O iniciador será salvo automaticamente e aparecerá na interface do chat.
  </Step>
</Steps>

<Warning>
  Limite de iniciadores: Recomendamos no máximo 4-6 iniciadores para não sobrecarregar a interface.
</Warning>

### 5. Base de Conhecimento

<Card title="Base de Conhecimento" icon="book">
  Conecte documentos e coleções RAG para enriquecer o conhecimento do agente.
</Card>

A base de conhecimento permite que o agente acesse informações específicas dos seus documentos através do sistema RAG (Retrieval Augmented Generation).

<Steps>
  <Step title="Visualizar Documentos Conectados">
    Na seção "Base de Conhecimento", você verá uma lista de documentos e coleções já conectados ao agente.
  </Step>
  <Step title="Adicionar Documentos">
    Clique em **Adicionar Documento** ou **Gerenciar Documentos** para abrir o diálogo de seleção.
  </Step>
  <Step title="Selecionar Documentos ou Coleções">
    Escolha entre:
    
    - **Documentos individuais**: Selecione documentos específicos
    - **Coleções**: Selecione coleções inteiras de documentos
    
    Use a busca para encontrar documentos rapidamente.
  </Step>
  <Step title="Confirmar Seleção">
    Clique em **Adicionar** ou **Salvar** para conectar os documentos ao agente.
  </Step>
</Steps>

<Info>
  Documentos conectados são processados automaticamente e indexados para busca. Quanto mais específico e relevante o conteúdo, melhor o desempenho do agente.
</Info>

### 6. Ferramentas (Tools)

<Card title="Ferramentas e Integrações" icon="wrench">
  Adicione ferramentas e integrações que o agente pode usar durante as conversas.
</Card>

As ferramentas expandem as capacidades do agente, permitindo que ele execute ações além de apenas conversar.

<AccordionGroup>
  <Accordion title="Tipos de Ferramentas Disponíveis">
    - **APIs**: Integrações com serviços externos
    - **Webhooks**: Chamadas HTTP para sistemas externos
    - **Bancos de Dados**: Consultas a bases de dados
    - **Ferramentas Customizadas**: Ferramentas desenvolvidas especificamente para seu caso de uso
  </Accordion>
  <Accordion title="Adicionar Ferramenta">
    <Steps>
      <Step title="Abrir Gerenciador de Ferramentas">
        Clique em **Gerenciar Ferramentas** ou **Adicionar Ferramenta** na seção Tools.
      </Step>
      <Step title="Selecionar Tipo">
        Escolha o tipo de ferramenta que deseja adicionar.
      </Step>
      <Step title="Configurar">
        Preencha os parâmetros necessários:
        
        - Nome da ferramenta
        - Endpoint ou configuração
        - Parâmetros de autenticação (se necessário)
        - Descrição do que a ferramenta faz
      </Step>
      <Step title="Testar">
        Use o botão de teste para verificar se a ferramenta está funcionando corretamente.
      </Step>
      <Step title="Salvar">
        Salve a ferramenta e ela estará disponível para o agente usar.
      </Step>
    </Steps>
  </Accordion>
</AccordionGroup>

### 7. Configurações Gerais

<Card title="Configurações Gerais" icon="settings">
  Ajuste configurações avançadas do agente.
</Card>

<AccordionGroup>
  <Accordion title="Modelo de IA">
    Escolha qual modelo de IA o agente usará:
    
    - **Gemini**: Modelo padrão do Google
    - **Outros modelos**: Conforme disponibilidade
    
    Cada modelo tem características diferentes de custo, velocidade e capacidade.
  </Accordion>
  <Accordion title="Temperatura">
    Ajuste a criatividade das respostas:
    
    - **Baixa (0.1-0.3)**: Respostas mais determinísticas e consistentes
    - **Média (0.5-0.7)**: Balance entre consistência e criatividade
    - **Alta (0.8-1.0)**: Respostas mais criativas e variadas
  </Accordion>
  <Accordion title="Limite de Tokens">
    Defina o tamanho máximo das respostas:
    
    - Respostas curtas: 500-1000 tokens
    - Respostas médias: 1000-2000 tokens
    - Respostas longas: 2000+ tokens
  </Accordion>
</AccordionGroup>

### 8. Acesso e Segurança

<Card title="Acesso e Segurança" icon="lock">
  Configure quem pode acessar e usar o agente.
</Card>

<Steps>
  <Step title="Configurar Visibilidade">
    Escolha quem pode ver e usar o agente:
    
    - **Público**: Todos os membros da organização
    - **Equipe**: Apenas membros de equipes específicas
    - **Privado**: Apenas você
  </Step>
  <Step title="Definir Permissões">
    Configure permissões de uso:
    
    - Quem pode conversar com o agente
    - Quem pode editar o agente
    - Quem pode ver métricas e analytics
  </Step>
  <Step title="Configurar Autenticação">
    Se necessário, configure autenticação adicional para acesso ao agente.
  </Step>
</Steps>

## Salvando Alterações

<Card title="Salvar Alterações" icon="save">
  Todas as alterações são salvas automaticamente enquanto você edita.
</Card>

O Aurora AI salva automaticamente suas alterações enquanto você trabalha. Você verá um indicador de status no canto superior direito mostrando:

- **Salvando...**: Quando há alterações sendo salvas
- **Salvo**: Quando todas as alterações foram salvas com sucesso
- **Erro**: Se houver algum problema ao salvar

<Warning>
  Certifique-se de ter conexão com a internet para que as alterações sejam salvas corretamente.
</Warning>

## Testando o Agente

Antes de publicar, é essencial testar o agente:

<Steps>
  <Step title="Acessar o Playground">
    Na página de edição do agente, encontre a aba **Playground** ou **Testar**.
  </Step>
  <Step title="Fazer Perguntas de Teste">
    Digite perguntas típicas que os usuários fariam:
    
    - Perguntas sobre o conhecimento conectado
    - Solicitações que usam ferramentas
    - Cenários de uso comum
  </Step>
  <Step title="Avaliar Respostas">
    Verifique se as respostas são:
    
    - Precisas e relevantes
    - No tom de voz correto
    - Completas e úteis
  </Step>
  <Step title="Ajustar Configurações">
    Com base nos testes, ajuste:
    
    - Personalidade
    - Base de conhecimento
    - Configurações gerais
  </Step>
</Steps>

## Publicando o Agente

Quando estiver satisfeito com a configuração:

<Steps>
  <Step title="Revisar Todas as Configurações">
    Navegue por todas as seções e verifique se está tudo configurado corretamente.
  </Step>
  <Step title="Alterar Status para Publicado">
    Na seção de Informações Básicas, altere o status de **Rascunho** para **Publicado**.
  </Step>
  <Step title="Salvar Alterações">
    Clique em **Salvar alterações** se ainda não salvou automaticamente.
  </Step>
  <Step title="Verificar Disponibilidade">
    O agente estará disponível nos canais configurados imediatamente após a publicação.
  </Step>
</Steps>

<Success>
  Parabéns! Seu agente está publicado e pronto para uso. Você pode monitorar seu desempenho através do dashboard.
</Success>

## Referência Completa de Campos

Para documentação detalhada de cada campo e todas as opções disponíveis, consulte:

<Card title="Referência Completa de Campos" icon="book" href="/docs/agents/fields-reference">
  Documentação completa de todos os campos, opções e configurações disponíveis na edição de agentes.
</Card>

## Próximos Passos

Agora que você criou seu agente, explore estas funcionalidades:

<CardGroup cols={2}>
  <Card title="Referência de Campos" icon="book" href="/docs/agents/fields-reference">
    Veja documentação completa de todos os campos
  </Card>
  <Card title="Configurar Canais" icon="radio" href="/docs/agents/channels-detailed">
    Configure onde seu agente estará disponível
  </Card>
  <Card title="Ver Analytics" icon="bar-chart" href="/docs/agents/analytics">
    Monitore performance e métricas do agente
  </Card>
  <Card title="Gerenciar Conversas" icon="message-square" href="/docs/agents/conversations">
    Veja e gerencie conversas do agente
  </Card>
  <Card title="Adicionar Conhecimento" icon="book-open" href="/docs/agents/knowledge">
    Enriqueça a base de conhecimento do agente
  </Card>
  <Card title="Personalizar Personalidade" icon="user" href="/docs/agents/personality">
    Ajuste o tom e estilo do agente
  </Card>
  <Card title="Testar Agente" icon="play" href="/docs/agents/testing">
    Use o playground para testar o agente
  </Card>
</CardGroup>

## Dicas e Boas Práticas

<Tip>
  **Comece simples**: Crie um agente básico primeiro e adicione complexidade gradualmente conforme você aprende o que funciona melhor.
</Tip>

<Tip>
  **Teste frequentemente**: Use o playground regularmente durante o desenvolvimento para identificar problemas cedo.
</Tip>

<Tip>
  **Documentos específicos**: Quanto mais específico e relevante o conhecimento conectado, melhor o desempenho do agente.
</Tip>

<Tip>
  **Itere e melhore**: Monitore métricas e feedback dos usuários para continuamente melhorar o agente.
</Tip>

## Troubleshooting

<AccordionGroup>
  <Accordion title="Agente não está respondendo corretamente">
    Verifique:
    
    - Se a base de conhecimento está conectada corretamente
    - Se a personalidade está configurada adequadamente
    - Se há documentos relevantes na base de conhecimento
    - Se o modelo de IA escolhido é adequado
  </Accordion>
  <Accordion title="Alterações não estão sendo salvas">
    Verifique:
    
    - Sua conexão com a internet
    - Se há erros de validação nos campos
    - Se você tem permissões para editar o agente
    - Tente recarregar a página
  </Accordion>
  <Accordion title="Agente publicado não aparece nos canais">
    Verifique:
    
    - Se o status está como "Publicado"
    - Se os canais estão configurados corretamente
    - Se você tem permissões para acessar os canais
    - Aguarde alguns minutos para propagação
  </Accordion>
</AccordionGroup>
