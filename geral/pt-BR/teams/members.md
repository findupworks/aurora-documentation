---
title: "Equipes"
---

# Gerenciando Equipes

O **Gerenciamento de Equipes** permite que você organize usuários em grupos, configure permissões específicas e gerencie membros de forma eficiente no Aurora AI.

![Lista de Equipes](/images/admin-teams.png)

## Acessando Equipes

<Steps>
  <Step>No menu lateral, navegue até **ADMINISTRAÇÃO**</Step>
  <Step>Clique em **Equipes**</Step>
  <Step>Você verá a lista de todas as equipes da organização</Step>
</Steps>

## Lista de Equipes

A página principal de Equipes exibe:

- **Título**: "Equipes" com descrição "Gerencie as equipes da sua organização"
- **Barra de Busca**: Filtre equipes por nome
- **Botão Criar Equipe**: Crie novas equipes rapidamente
- **Tabela de Equipes**: Lista todas as equipes com informações e ações

### Buscar Equipes

Para encontrar uma equipe específica:

1. Use a barra de busca com o texto "Buscar por nome..."
2. Digite o nome da equipe
3. A lista será filtrada automaticamente conforme você digita
4. Limpe a busca para ver todas as equipes novamente

### Criar Nova Equipe

Para criar uma nova equipe:

1. Clique no botão **Criar Equipe** no canto superior direito
2. Preencha o nome da equipe
3. Adicione uma descrição (opcional)
4. Configure permissões iniciais (opcional)
5. Clique em **Criar**

### Informações da Tabela

A tabela de equipes exibe:

- **Nome**: Nome da equipe
- **Criado em**: Data de criação da equipe
- **Ações**: Ícones para gerenciar a equipe:
  - 👥 **Gerenciar Membros**: Visualizar e gerenciar membros
  - 🛡️ **Permissões**: Configurar permissões da equipe
  - ✏️ **Editar**: Editar informações da equipe
  - 🗑️ **Excluir**: Remover a equipe

## Visualizando Detalhes da Equipe

![Detalhes da Equipe](/images/admin-teams-detail.png)

Ao clicar em uma equipe ou usar a ação de gerenciar membros, você verá a página de detalhes da equipe.

### Abas da Equipe

A página de detalhes possui três abas principais:

1. **Membros**: Gerencie os membros da equipe
2. **Agentes**: Visualize agentes associados à equipe
3. **Permissões**: Configure permissões da equipe

### Aba Membros

Na aba **Membros**, você pode:

#### Visualizar Membros

A tabela de membros exibe:

- **Nome**: Nome completo do membro
- **Email**: Endereço de email do membro
- **Função**: Função do membro na equipe (ex: member)
- **Entrou em**: Data em que o membro se juntou à equipe
- **Ações**: Ícone de lixeira para remover o membro

#### Adicionar Membro

Para adicionar um novo membro à equipe:

1. Clique no botão **+ Adicionar Membro** no canto superior direito
2. Selecione um usuário da organização ou digite um email
3. Escolha a função do membro na equipe
4. Confirme a adição

#### Remover Membro

Para remover um membro da equipe:

1. Na tabela de membros, localize o membro desejado
2. Clique no ícone de lixeira na coluna **Ações**
3. Confirme a remoção
4. O membro será removido da equipe (mas não da organização)

### Aba Agentes

Na aba **Agentes**, você pode:

- Visualizar todos os agentes associados à equipe
- Ver permissões de cada agente
- Gerenciar acesso aos agentes

### Aba Permissões

![Permissões da Equipe](/images/admin-teams-detail-permission.png)

Na aba **Permissões**, você configura quais permissões os membros da equipe podem ter.

#### Configurando Permissões

A seção "Permissões da Equipe" permite selecionar as permissões que os membros desta equipe podem ter:

1. **Construtor de agentes**

   - Descrição: "Pode criar e gerenciar agentes dentro da organização."
   - Permite que membros criem, editem e gerenciem agentes

2. **Construtor de workflows**

   - Descrição: "Pode criar e gerenciar workflows dentro da organização."
   - Permite que membros criem e gerenciem workflows

3. **Usuário de chat**

   - Descrição: "Pode utilizar os chats da organização dentro dos limites configurados."
   - Permite que membros usem os recursos de chat

4. **Administrador da organização**
   - Descrição: "Acesso completo às funcionalidades da organização, incluindo chat, agentes e workflows."
   - Fornece acesso administrativo completo

#### Selecionando Permissões

Para configurar permissões:

1. Na aba **Permissões**, revise cada tipo de permissão
2. Marque as permissões que deseja conceder à equipe
3. As permissões selecionadas se aplicam a todos os membros da equipe
4. Salve as alterações

## Gerenciando Equipes

### Editar Equipe

Para editar informações da equipe:

1. Na lista de equipes, clique no ícone de editar (✏️)
2. Modifique o nome ou descrição
3. Salve as alterações

### Excluir Equipe

Para excluir uma equipe:

1. Na lista de equipes, clique no ícone de excluir (🗑️)
2. Confirme a exclusão
3. A equipe será removida permanentemente
4. **Atenção**: Membros não serão removidos da organização, apenas da equipe

## Boas Práticas

- ✅ **Organize por função**: Crie equipes baseadas em funções ou departamentos
- ✅ **Use nomes descritivos**: Escolha nomes que indiquem claramente o propósito da equipe
- ✅ **Configure permissões adequadas**: Dê apenas as permissões necessárias para cada equipe
- ✅ **Revise regularmente**: Mantenha a lista de membros atualizada
- ✅ **Documente estrutura**: Mantenha registro da estrutura organizacional
- ✅ **Teste permissões**: Verifique se as permissões estão funcionando corretamente

## Próximos Passos

<Columns cols={2}>

<Card
  title="Configurando Permissões"
  icon="shield"
  href="/geral/pt-BR/teams/permissions">
Aprenda mais sobre como configurar permissões detalhadas para equipes.
</Card>

<Card
  title="Gerenciando Usuários"
  icon="users"
  href="/geral/pt-BR/admin/users">
Veja como gerenciar usuários da organização.
</Card>

<Card
  title="Enviando Convites"
  icon="mail"
  href="/geral/pt-BR/admin/invitations">
Aprenda como convidar novos membros para a organização.
</Card>

<Card
  title="Dashboard"
  icon="grid"
  href="/geral/pt-BR/admin/dashboard">
Volte ao dashboard para ver métricas e análises.
</Card>

</Columns>

## Dicas

- 🔒 **Princípio do menor privilégio**: Dê apenas as permissões necessárias
- 📊 **Monitore uso**: Acompanhe quais equipes estão mais ativas
- 🔄 **Atualize regularmente**: Revise membros e permissões periodicamente
- 🎯 **Seja específico**: Use nomes claros que indiquem o propósito de cada equipe
- 📝 **Documente mudanças**: Mantenha registro de alterações em equipes
