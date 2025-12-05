---
title: "Arquivos"
---

![Gerenciamento de Arquivos](/images/admin-files.png)

# Gerenciando Arquivos

A seção **Arquivos** permite que você gerencie as coleções de documentos da sua organização no Aurora AI de forma centralizada.

## Acessando Arquivos

<Steps>
  <Step>No menu lateral, navegue até **BUSINESS HUB**</Step>
  <Step>Clique em **Arquivos**</Step>
  <Step>Você verá a página de Arquivos com as abas "Coleções" e "Documentos"</Step>
</Steps>

## Visão Geral

A página de Arquivos exibe:

- **Abas de Navegação**: Alternar entre **Coleções** e **Documentos**
- **Lista de Coleções**: Todas as coleções de documentos da organização
- **Busca**: Campo para buscar coleções por nome
- **Ações Rápidas**: Botão para criar nova coleção e atualizar a lista

## Navegando entre Coleções e Documentos

A interface possui duas abas principais:

### Aba Coleções

Mostra todas as coleções de documentos criadas na organização. Cada coleção pode conter múltiplos documentos e é identificada por:

- **Ícone**: Identificador visual da coleção
- **Nome**: Título da coleção
- **Descrição**: Breve descrição do propósito da coleção
- **Indicador de Usuários**: Ícone mostrando quantos usuários/agentes estão associados

### Aba Documentos

Mostra todos os documentos individuais da organização, independente da coleção.

## Buscando Coleções

Para encontrar uma coleção específica:

1. Clique no campo de busca com o texto "Buscar por nome..."
2. Digite parte do nome da coleção
3. A lista será filtrada automaticamente conforme você digita
4. Limpe a busca para ver todas as coleções novamente

## Atualizando a Lista

Para atualizar a lista de coleções e documentos:

1. Clique no botão **Atualizar** ao lado do campo de busca
2. A lista será atualizada com as informações mais recentes
3. Novas coleções e documentos serão exibidos

## Criando Nova Coleção

Para criar uma nova coleção de documentos:

1. Clique no botão **Criar Coleção** no canto superior direito
2. Preencha as informações da coleção:
   - Nome da coleção
   - Descrição (opcional)
   - Icone
   - Cor
3. Salve a coleção
4. A coleção estará disponível para adicionar documentos

## Criar Novo Documento

![Criar Documento](/images/admin-files-create.png)

Para adicionar um novo documento a uma coleção:

<Steps>
  <Step>Navegue até a coleção onde deseja adicionar o documento</Step>
  <Step>Clique no botão para adicionar documento (geralmente um botão "+" ou "Adicionar Documento")</Step>
  <Step>O modal "Adicionar Documento" será exibido</Step>
  <Step>Escolha o tipo de documento que deseja adicionar</Step>
</Steps>

### Tipos de Documento

O modal oferece três tipos de documentos:

#### 1. Arquivo

Para fazer upload de um arquivo do seu computador:

1. Selecione a opção **Arquivo** (primeira opção)
2. Clique em **Choose File** ou **Escolher Arquivo**
3. Selecione o arquivo do seu computador
4. O nome do arquivo será exibido após a seleção

**Formatos Aceitos:**

- **PDF**: Documentos em formato PDF
- **DOCX**: Documentos do Microsoft Word
- **MD**: Arquivos Markdown

**Limitações:**

- Tamanho máximo: **10MB** por arquivo

**Data de Expiração (Opcional):**

Você pode configurar uma data de expiração para o documento:

1. Marque a checkbox **"Documento com data de expiração"**
2. Uma mensagem será exibida: "O documento será expirado automaticamente na data selecionada"
3. Clique no campo **"Data de Expiração"**
4. Selecione uma data usando o calendário
5. O documento será automaticamente expirado na data selecionada

#### 2. Texto

Para adicionar conteúdo de texto diretamente:

1. Selecione a opção **Texto**
2. Digite ou cole o conteúdo textual
3. O texto será processado e indexado para busca

#### 3. Perguntas

Para adicionar perguntas frequentes ou Q&A:

1. Selecione a opção **Perguntas**
2. Adicione perguntas e respostas
3. Essas perguntas podem ser usadas para treinar agentes ou criar bases de conhecimento

### Finalizando a Criação

Após preencher todas as informações:

1. Revise os dados inseridos
2. Clique em **Criar Documento** para confirmar
3. Ou clique em **Cancelar** para descartar as alterações
4. O documento será processado e adicionado à coleção

## Visualizando Coleções

Quando há coleções criadas, você verá cards exibindo:

- **Ícone da Coleção**: Identificador visual (geralmente em roxo)
- **Nome da Coleção**: Título principal
- **Descrição**: Breve descrição do propósito
- **Indicadores**: Ícones mostrando informações adicionais (como número de usuários associados)
- **Contador**: Informação sobre quantos documentos estão na coleção

### Exemplo de Coleção

Uma coleção pode aparecer assim:

- **Nome**: "Service Desk"
- **Descrição**: "Procedimentos de suporte"
- **Ícone**: Pasta/documento roxo
- **Indicador**: Ícone de usuários mostrando associações

## Gerenciando Documentos em uma Coleção

### Visualizar Documentos de uma Coleção

1. Clique na coleção desejada
2. Você verá todos os documentos dessa coleção
3. Informações como "documentos nesta coleção" serão exibidas

## Boas Práticas

- ✅ **Organize por propósito**: Crie coleções temáticas para facilitar a organização
- ✅ **Use descrições claras**: Descreva bem cada coleção para facilitar identificação
- ✅ **Mantenha atualizado**: Revise e atualize documentos regularmente
- ✅ **Configure expiração**: Use datas de expiração para documentos temporários
- ✅ **Formatos adequados**: Use PDF para documentos finais, DOCX para edição, MD para documentação técnica
- ✅ **Tamanho de arquivo**: Mantenha arquivos abaixo de 10MB para melhor performance

## Próximos Passos

<Columns cols={2}>

<Card
  title="Gerenciando Usuários"
  icon="users"
  href="/geral/pt-BR/admin/users">
Veja como gerenciar usuários da organização e suas permissões.
</Card>

<Card
  title="Enviando Convites"
  icon="mail"
  href="/geral/pt-BR/admin/invitations">
Aprenda como convidar novos membros para sua organização.
</Card>

<Card
  title="Gerenciando Prompts"
  icon="lightbulb"
  href="/geral/pt-BR/admin/prompts">
Configure e gerencie prompts personalizados para sua organização.
</Card>

<Card
  title="Dashboard"
  icon="grid"
  href="/geral/pt-BR/admin/dashboard">
Volte ao dashboard para ver métricas e análises da sua organização.
</Card>

</Columns>

## Dicas

- 📁 **Organize bem**: Crie coleções lógicas e bem nomeadas para facilitar a busca
- 🔍 **Use a busca**: Utilize o campo de busca para encontrar coleções rapidamente
- 📄 **Formatos corretos**: Certifique-se de usar formatos suportados (PDF, DOCX, MD)
- ⏰ **Datas de expiração**: Configure expiração para documentos temporários ou com validade
- 🔄 **Atualize regularmente**: Use o botão "Atualizar" para sincronizar a lista
- 📊 **Monitore tamanhos**: Mantenha arquivos abaixo de 10MB para melhor performance
- 🏷️ **Descrições claras**: Use descrições descritivas nas coleções para facilitar identificação
