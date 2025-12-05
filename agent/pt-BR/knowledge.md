---
title: "Base de Conhecimento"
---

# Adicionando Conhecimento aos Agentes

O conhecimento é fundamental para que seus agentes forneçam respostas precisas e contextualizadas. Nesta seção, você aprenderá como adicionar e gerenciar conhecimento para seus agentes.

## Tipos de Conhecimento

### Documentos e Coleções RAG

- Conecte coleções de documentos ao agente
- O agente poderá acessar informações específicas dos documentos
- Ideal para conhecimento estruturado e atualizado

## Tipos de Documentos que Podem Ser Adicionados

Você pode adicionar três tipos principais de documentos à sua base de conhecimento:

### 1. Arquivo

Para fazer upload de um arquivo do seu computador:

**Formatos Aceitos:**

- **PDF**: Documentos técnicos, manuais, relatórios, formulários e contratos
- **DOCX**: Documentos do Microsoft Word
- **MD**: Arquivos Markdown para documentação técnica

**Limitações:**

- Tamanho máximo: **10MB** por arquivo
- Mantenha arquivos abaixo de 10MB para melhor performance de processamento

**Data de Expiração (Opcional):**

Você pode configurar uma data de expiração para documentos temporários ou com validade:

1. Marque a checkbox **"Documento com data de expiração"**
2. Uma mensagem será exibida: "O documento será expirado automaticamente na data selecionada"
3. Clique no campo **"Data de Expiração"**
4. Selecione uma data usando o calendário
5. O documento será automaticamente expirado na data selecionada

**Quando usar:**

- Documentos temporários (ex: promoções, campanhas)
- Informações com validade (ex: políticas que mudam periodicamente)
- Conteúdo que precisa ser revisado em datas específicas

### 2. Texto

Para adicionar conteúdo de texto diretamente:

- Digite ou cole o conteúdo textual na interface
- O texto será processado e indexado para busca
- Ideal para artigos, notas, documentação técnica, FAQs e bases de conhecimento

**Quando usar:**

- Conteúdo que você já tem em formato texto
- Informações que não precisam de formatação complexa
- Documentação rápida e direta

### 3. Perguntas

Para adicionar perguntas frequentes ou Q&A:

- Adicione perguntas e respostas estruturadas
- Essas perguntas podem ser usadas para treinar agentes ou criar bases de conhecimento
- Ideal para FAQs organizadas e respostas padronizadas

**Quando usar:**

- Perguntas frequentes de suporte
- Respostas padronizadas para situações comuns
- Base de conhecimento estruturada em formato Q&A

## Conectando Coleções ao Agente

<Steps>
  <Step title="Abrir o Agente">
    Abra o agente desejado que você deseja conectar à base de conhecimento.
  </Step>

  <Step title="Acessar Base de Conhecimento">
    Vá até a seção <strong>Base de Conhecimento</strong> ou <strong>Knowledge</strong> nas configurações do agente.
  </Step>

  <Step title="Selecionar Coleções">
    Selecione as coleções que deseja conectar ao agente. Você pode selecionar múltiplas coleções se necessário.
  </Step>

  <Step title="Escolher Documentos">
    Se necessário, escolha arquivos específicos dentro das coleções que deseja conectar.
  </Step>

  <Step title="Salvar Alterações">
    Clique em <strong>Salvar</strong> ou <strong>Aplicar</strong> para confirmar as alterações. O agente agora terá acesso aos documentos selecionados.
  </Step>
</Steps>

## Formatos de Documentos Suportados

### PDFs

- Documentos técnicos
- Manuais e guias
- Relatórios e análises
- Formulários e contratos

### Documentos de Texto

- **DOCX**: Documentos do Microsoft Word
- **MD**: Arquivos Markdown
- **TXT**: Arquivos de texto simples

## Boas Práticas

- ✅ **Use formatos adequados**: Use PDF para documentos finais, DOCX para edição, MD para documentação técnica
- ✅ **Configure expiração**: Use datas de expiração para documentos temporários ou com validade
- ✅ **Mantenha atualizado**: Revise e atualize documentos regularmente
- ✅ **Tamanho de arquivo**: Mantenha arquivos abaixo de 10MB para melhor performance
- ✅ **Seja específico**: Documentos específicos geram respostas melhores
- ✅ **Organize bem**: Use coleções para organizar por tema ou propósito

## Próximos Passos

<Columns cols={2}>

<Card
  title="Gerenciando Documentos"
  icon="file"
  href="/geral/pt-BR/documents/introduction">
Aprenda a fazer upload, organizar e gerenciar documentos que serão usados como base de conhecimento para seus agentes.
</Card>

<Card
  title="Criando Coleções"
  icon="folder"
  href="/geral/pt-BR/documents/collections">
Organize documentos em coleções RAG para facilitar o gerenciamento e melhorar a precisão das respostas dos agentes.
</Card>

</Columns>
