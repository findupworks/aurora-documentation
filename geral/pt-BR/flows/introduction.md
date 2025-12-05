# Introdução aos Flows

**Flows** são fluxos visuais simplificados que permitem criar automações de forma intuitiva, combinando starters e ações em uma interface visual clara.

## O que são Flows?

Flows são uma forma visual e simplificada de criar automações:

- 🎨 **Interface visual**: Construa fluxos arrastando e conectando elementos
- ⚡ **Rápido de criar**: Configure automações em minutos
- 🔄 **Fácil de entender**: Visualize o fluxo completo de uma vez
- 🎯 **Focado em simplicidade**: Ideal para automações diretas

## Diferença entre Workflows e Flows

| Workflows | Flows |
|-----------|-------|
| Mais complexos e poderosos | Mais simples e diretos |
| Múltiplas condições aninhadas | Lógica linear e clara |
| Para processos complexos | Para automações rápidas |
| Mais opções de configuração | Configuração simplificada |

## Componentes de um Flow

### Starter (Iniciador)

O evento que inicia o flow:

- **Quando recebo um email**: Dispara ao receber emails
- **Em um agendamento**: Executa em horários específicos
- **Quando sou mencionado**: Acionado por menções
- **Quando alguém entra em um espaço**: Dispara em novos membros

### Actions (Ações)

Os passos que o flow executa:

- **Agentes de IA**: Perguntar ao Gemini, usar habilidades de IA
- **AI Skills**: Recapitular emails, extrair dados, decidir, resumir
- **Tools**: Verificar condições, filtrar, enviar webhooks
- **Gmail**: Enviar emails, criar rascunhos

## Criando seu Primeiro Flow

### Passo 1: Acessar o Builder de Flows

1. No menu lateral, clique em **Builder**
2. Selecione **Flow**
3. Clique em **Criar Novo Flow**

### Passo 2: Escolher um Starter

1. Na seção **Starter**, clique na caixa vazia
2. Escolha um starter do menu lateral
3. O starter será adicionado ao flow

### Passo 3: Adicionar Ações

Para cada ação que deseja adicionar:

1. Clique em **Add step** na parte inferior
2. Uma caixa vazia será criada na seção **Actions**
3. Clique na caixa vazia
4. Escolha uma ação do menu lateral
5. A ação será adicionada ao flow

### Passo 4: Configurar Cada Passo

Clique em qualquer passo para editar:

- **Label**: Nome descritivo do passo
- **Configuração**: Parâmetros específicos da ação
- **Tipo**: Tipo de ação (não pode ser alterado após criação)

### Passo 5: Testar e Ativar

1. Clique em **Test run** para testar o flow
2. Revise os resultados
3. Clique em **Turn on** para ativar o flow

## Exemplo Prático: Flow de Resposta Automática

Vamos criar um flow que responde automaticamente a emails:

1. **Starter**: Quando recebo um email
2. **Action**: Perguntar ao Gemini sobre o conteúdo do email
3. **Action**: Se a resposta indicar urgência, enviar email de confirmação

### Passo a Passo

1. Crie um novo flow chamado "Resposta Automática"
2. Escolha o starter "Quando recebo um email"
3. Adicione a ação "Perguntar ao Gemini"
4. Configure o Gemini para analisar o email
5. Adicione a ação "Decidir" para verificar urgência
6. Adicione a ação "Enviar email" condicionalmente

## Boas Práticas

- ✅ **Nomeie claramente**: Use nomes descritivos para cada passo
- ✅ **Mantenha simples**: Evite lógica muito complexa
- ✅ **Teste sempre**: Use "Test run" antes de ativar
- ✅ **Documente**: Adicione descrições quando necessário
- ✅ **Monitore**: Acompanhe execuções para identificar melhorias

## Próximos Passos

- [Usando Starters Avançados](/docs/flows/starters)
- [Configurando Ações de IA](/docs/flows/ai-actions)
- [Integrando com Gmail](/docs/flows/gmail)
- [Monitorando Execuções](/docs/flows/monitoring)

## Dicas

- 💡 Comece com um starter simples
- 🎯 Foque em uma tarefa específica por flow
- 🔄 Reutilize flows bem-sucedidos como templates
- 📊 Use métricas para otimizar performance

