---
title: "Prompts"
---

![Gerenciamento de Prompts](/images/admin-prompts.png)

# Gerenciando Prompts

A seção **Prompts** permite que você gerencie os prompts disponíveis na organização no Aurora AI. Os prompts são templates de instruções que podem ser reutilizados em múltiplos agentes e workflows, garantindo consistência e facilitando manutenção.

## Acessando Prompts

<Steps>
  <Step>No menu lateral, navegue até **BUSINESS HUB**</Step>
  <Step>Clique em **Prompts**</Step>
  <Step>Você verá a página de Prompts com a lista de prompts da organização</Step>
</Steps>

## Visão Geral

A página de Prompts exibe:

- **Lista de Prompts**: Todos os prompts criados na organização
- **Busca**: Campo para buscar prompts por nome ou conteúdo
- **Ações Rápidas**: Botão para criar novo prompt e atualizar a lista
- **Estado Vazio**: Quando não há prompts, uma mensagem informativa é exibida

## Estado Vazio

Quando não há prompts criados, você verá:

- **Título da Seção**: "Lista de Prompts"
- **Mensagem**: "Nenhum prompt encontrado"
- **Ação Principal**: Botão grande **"Criar primeiro prompt"** para começar a criar prompts

## Buscando Prompts

Para encontrar um prompt específico:

1. Clique no campo de busca com o texto "Buscar prompts..."
2. Digite parte do nome ou conteúdo do prompt
3. A lista será filtrada automaticamente conforme você digita
4. Limpe a busca para ver todos os prompts novamente

## Atualizando a Lista

Para atualizar a lista de prompts:

1. Clique no botão **Atualizar** ao lado do campo de busca
2. A lista será atualizada com as informações mais recentes
3. Novos prompts criados serão exibidos

## Criar Novo Prompt

![Criar Prompt](/images/admin-prompts-add.png)

Para criar um novo prompt para a organização:

<Steps>
  <Step>Clique no botão **Criar Prompt** no canto superior direito (ou **Criar primeiro prompt** se a lista estiver vazia)</Step>
  <Step>O modal "Criar Prompt" será exibido</Step>
  <Step>Preencha todas as informações necessárias</Step>
  <Step>Clique em **Criar** para salvar o prompt</Step>
</Steps>

### Campos do Formulário

O modal de criação contém os seguintes campos:

#### 1. Nome

O nome do prompt é obrigatório e identifica o prompt na lista:

- **Campo**: Texto com placeholder "Nome do prompt"
- **Ícones**:
  - **Cadeado**: Indica configurações de privacidade ou segurança
  - **Informação (i)**: Fornece informações adicionais sobre o campo
- **Dica**: Use nomes descritivos que facilitem a identificação do propósito do prompt

**Exemplos de nomes:**

- "Assistente de Suporte Técnico"
- "Consultor de Vendas"
- "Especialista em Documentação"

#### 2. Tipo

O tipo categoriza o prompt e pode afetar como ele é usado:

- **Campo**: Dropdown com placeholder "Selecione o tipo"
- **Opções**: Diferentes categorias de prompts disponíveis
- **Importante**: Escolha o tipo apropriado para facilitar organização e busca

**Tipos comuns podem incluir:**

- Suporte ao Cliente
- Vendas
- Técnico
- Educacional
- Documentação

#### 3. Texto do Prompt

Este é o conteúdo principal do prompt - as instruções que serão usadas pelos agentes:

- **Campo**: Área de texto grande (multilinha)
- **Placeholder**: "Digite o texto do prompt..."
- **Ícone de Código (`<>`)**: Permite visualizar ou editar o prompt em formato de código/markup
- **Dica**: Seja claro e específico nas instruções

**Exemplo de texto de prompt:**

```
Você é um assistente de suporte técnico especializado em produtos de software.
Seu objetivo é ajudar usuários a resolver problemas técnicos de forma clara e eficiente.

Regras:
- Seja sempre educado e profissional
- Faça perguntas claras para entender o problema
- Forneça soluções passo a passo
- Se não souber a resposta, seja honesto e ofereça alternativas
```

#### 4. Ícone (Opcional)

Um ícone visual para identificar o prompt na lista:

- **Campo**: Texto com placeholder "Selecione um ícone"
- **Opcional**: Este campo não é obrigatório
- **Uso**: Facilita identificação visual rápida do prompt

### Finalizando a Criação

Após preencher todas as informações:

1. Revise os dados inseridos
2. Verifique se o texto do prompt está correto
3. Clique em **Criar** para confirmar e salvar
4. Ou clique em **Cancelar** para descartar as alterações
5. O prompt será criado e estará disponível na lista

## Visualizando Prompts

Quando há prompts criados, você verá uma lista exibindo:

- **Nome do Prompt**: Título identificador
- **Tipo**: Categoria do prompt
- **Ícone**: Identificador visual (se configurado)
- **Ações**: Opções para editar, duplicar ou excluir

## Gerenciando Prompts

### Editar Prompt Existente

Para modificar um prompt existente:

1. Localize o prompt na lista
2. Clique nas ações do prompt
3. Selecione **Editar**
4. O modal será aberto com os dados atuais
5. Faça as alterações necessárias
6. Salve as alterações

### Duplicar Prompt

Para criar uma cópia de um prompt existente:

1. Localize o prompt na lista
2. Clique nas ações do prompt
3. Selecione **Duplicar**
4. Um novo prompt será criado com os mesmos dados
5. Edite conforme necessário

### Excluir Prompt

Para remover um prompt:

1. Localize o prompt na lista
2. Clique nas ações do prompt
3. Selecione **Excluir**
4. Confirme a ação
5. O prompt será removido permanentemente

**Atenção**: Verifique se o prompt não está sendo usado em agentes ou workflows antes de excluir.

## Usando Prompts

### Em Agentes

Para usar um prompt em um agente:

1. Abra o agente desejado
2. Vá até **Personality** ou **Instructions**
3. Selecione um prompt da lista de prompts da organização
4. O prompt será aplicado ao agente
5. Personalize se necessário

## Em chats

1. Acesse Chat
2. Abra a opção prompts
3. Escolha um prompt
4. Ele será carregado na caixa de texto

## Boas Práticas

- ✅ **Seja específico**: Defina claramente o papel e objetivo do prompt
- ✅ **Use nomes descritivos**: Facilite a identificação do propósito
- ✅ **Escolha o tipo correto**: Categorize adequadamente para organização
- ✅ **Texto claro**: Escreva instruções claras e objetivas
- ✅ **Teste sempre**: Teste prompts antes de usar em produção
- ✅ **Documente**: Mantenha documentação sobre cada prompt
- ✅ **Revise regularmente**: Atualize prompts baseado em feedback
- ✅ **Use ícones**: Adicione ícones para facilitar identificação visual

## Próximos Passos

<Columns cols={2}>

<Card
  title="Gerenciando Arquivos"
  icon="paperclip"
  href="/geral/pt-BR/admin/files">
Veja como gerenciar arquivos e documentos da organização.
</Card>

<Card
  title="Gerenciando Usuários"
  icon="users"
  href="/geral/pt-BR/admin/users">
Veja como gerenciar usuários da organização e suas permissões.
</Card>

<Card
  title="Criando Agentes"
  icon="globe"
  href="/geral/pt-BR/builders/agent">
Aprenda a criar e configurar agentes usando prompts.
</Card>

<Card
  title="Dashboard"
  icon="grid"
  href="/geral/pt-BR/admin/dashboard">
Volte ao dashboard para ver métricas e análises da sua organização.
</Card>

</Columns>

## Dicas

- 📝 **Comece simples**: Crie prompts básicos primeiro e adicione complexidade gradualmente
- 🔄 **Reutilize**: Use prompts bem-sucedidos como base para novos
- 🧪 **Teste variações**: Experimente diferentes versões para encontrar a melhor
- 📊 **Monitore performance**: Acompanhe como os prompts estão funcionando em uso
- 💡 **Colete feedback**: Use feedback de usuários para melhorar prompts
- 🔍 **Use a busca**: Utilize o campo de busca para encontrar prompts rapidamente
- 🎯 **Seja específico**: Quanto mais específico o prompt, melhor o resultado
- 📋 **Organize por tipo**: Use tipos consistentes para facilitar organização
