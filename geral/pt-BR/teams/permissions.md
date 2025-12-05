---
title: "Permissões"
---

# Configurando Permissões de Equipe

Configure permissões granulares para controlar o acesso de membros da equipe aos recursos da organização no Aurora AI.

![Permissões da Equipe](/images/admin-teams-detail-permission.png)

## Acessando Permissões

<Steps>
  <Step>No menu lateral, navegue até **ADMINISTRAÇÃO** > **Equipes**</Step>
  <Step>Clique na equipe desejada ou use a ação de permissões (🛡️)</Step>
  <Step>Na página de detalhes da equipe, clique na aba **Permissões**</Step>
</Steps>

## Visão Geral

A seção de Permissões permite que você:

- Selecione quais permissões os membros da equipe podem ter
- Configure acesso granular a diferentes funcionalidades
- Gerencie o que cada membro da equipe pode fazer na organização

## Tipos de Permissões

### Construtor de Agentes

**Descrição**: "Pode criar e gerenciar agentes dentro da organização."

**O que permite**:
- Criar novos agentes
- Editar agentes existentes
- Configurar parâmetros de agentes
- Publicar e despublicar agentes
- Gerenciar configurações de agentes

**Quando usar**:
- Equipes de desenvolvimento de agentes
- Equipes que precisam criar soluções com IA
- Membros que trabalham com criação de assistentes virtuais

### Construtor de Workflows

**Descrição**: "Pode criar e gerenciar workflows dentro da organização."

**O que permite**:
- Criar novos workflows
- Editar workflows existentes
- Configurar triggers e ações
- Executar e testar workflows
- Gerenciar conexões entre blocos

**Quando usar**:
- Equipes de automação
- Equipes que criam processos automatizados
- Membros que trabalham com integrações

### Usuário de Chat

**Descrição**: "Pode utilizar os chats da organização dentro dos limites configurados."

**O que permite**:
- Usar os chats da organização
- Conversar com agentes disponíveis
- Acessar histórico de conversas (se permitido)
- Usar recursos de chat dentro dos limites do plano

**Limitações**:
- Sujeito aos limites configurados no plano
- Pode ter restrições de uso por período
- Acesso apenas a chats permitidos pela organização

**Quando usar**:
- Equipes que precisam usar os agentes
- Membros que interagem com clientes via chat
- Usuários finais que consomem os serviços de IA

### Administrador da Organização

**Descrição**: "Acesso completo às funcionalidades da organização, incluindo chat, agentes e workflows."

**O que permite**:
- Todas as permissões anteriores
- Gerenciar configurações da organização
- Acessar todas as funcionalidades sem restrições
- Configurar limites e políticas
- Gerenciar outros membros e equipes

**Quando usar**:
- Proprietários da organização
- Administradores principais
- Membros que precisam de acesso total

**⚠️ Atenção**: Use com cuidado, pois concede acesso completo.

## Configurando Permissões

### Selecionar Permissões

Para configurar permissões de uma equipe:

1. Acesse a equipe desejada
2. Vá até a aba **Permissões**
3. Revise cada tipo de permissão disponível
4. Marque as permissões que deseja conceder à equipe
5. As permissões selecionadas se aplicam a **todos os membros** da equipe
6. Salve as alterações

### Combinando Permissões

Você pode selecionar múltiplas permissões:

- **Construtor de Agentes + Usuário de Chat**: Membros podem criar agentes e usá-los
- **Construtor de Workflows + Usuário de Chat**: Membros podem criar workflows e usar chats
- **Todas as permissões**: Para equipes que precisam de acesso amplo

### Remover Permissões

Para remover uma permissão:

1. Acesse a aba **Permissões** da equipe
2. Desmarque a permissão desejada
3. Salve as alterações
4. Os membros perderão acesso imediatamente

## Estratégias de Permissões

### Por Função

Configure equipes baseadas em funções:

- **Equipe de Desenvolvimento**: Construtor de Agentes + Construtor de Workflows
- **Equipe de Suporte**: Usuário de Chat
- **Equipe de Administração**: Administrador da Organização

### Por Projeto

Organize por projetos específicos:

- **Projeto Alpha**: Construtor de Agentes
- **Projeto Beta**: Construtor de Workflows
- **Projeto Gamma**: Usuário de Chat

### Por Nível de Acesso

Use níveis hierárquicos:

- **Nível 1**: Usuário de Chat (acesso básico)
- **Nível 2**: Construtor de Agentes ou Workflows (acesso intermediário)
- **Nível 3**: Administrador da Organização (acesso completo)

## Boas Práticas

- ✅ **Princípio do menor privilégio**: Dê apenas as permissões necessárias
- ✅ **Revise regularmente**: Verifique se as permissões ainda são apropriadas
- ✅ **Documente decisões**: Mantenha registro de por que certas permissões foram concedidas
- ✅ **Teste permissões**: Verifique se os membros têm acesso correto
- ✅ **Seja específico**: Evite dar "Administrador" quando não é necessário
- ✅ **Monitore uso**: Acompanhe como as permissões estão sendo utilizadas

## Troubleshooting

### Membros não têm acesso esperado

1. Verifique se a permissão está marcada na equipe
2. Confirme que o membro está na equipe correta
3. Verifique se as alterações foram salvas
4. Peça ao membro para fazer logout e login novamente

### Permissões não estão funcionando

1. Verifique se há conflitos com permissões de organização
2. Confirme que o plano da organização suporta as funcionalidades
3. Verifique logs de acesso para identificar problemas
4. Entre em contato com o suporte se o problema persistir

## Próximos Passos

<Columns cols={2}>

<Card
  title="Gerenciando Equipes"
  icon="user-group"
  href="/geral/pt-BR/teams/members">
  Aprenda como gerenciar equipes e membros.
</Card>

<Card
  title="Gerenciando Usuários"
  icon="users"
  href="/geral/pt-BR/admin/users">
  Veja como gerenciar usuários da organização.
</Card>

<Card
  title="Introdução às Equipes"
  icon="book"
  href="/geral/pt-BR/teams/introduction">
  Entenda os conceitos básicos de equipes e organizações.
</Card>

<Card
  title="Melhores Práticas"
  icon="star"
  href="/geral/pt-BR/teams/best-practices">
  Aprenda as melhores práticas para gerenciar equipes.
</Card>

</Columns>

## Dicas

- 🔒 **Segurança primeiro**: Sempre comece com permissões mínimas
- 📋 **Documente**: Mantenha uma lista de quem tem quais permissões
- 🔄 **Revise periodicamente**: Faça auditorias regulares de permissões
- 🎯 **Seja específico**: Evite dar permissões amplas quando específicas são suficientes
- 👥 **Comunique**: Informe membros sobre mudanças de permissões
- 📊 **Monitore**: Acompanhe o uso de permissões para otimizar
