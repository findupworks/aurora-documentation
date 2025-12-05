![Agent](/images/base-workflow.png)

# Introdução aos Workflows

**Workflows** são fluxos automatizados que combinam múltiplas ações e decisões para executar processos complexos de forma eficiente.

## O que são Workflows?

Workflows permitem que você:

- 🔄 **Automatize processos** repetitivos
- 🔀 **Orquestre múltiplas ações** em sequência
- ⚡ **Execute decisões condicionais** baseadas em dados
- 🔌 **Integre sistemas** externos através de webhooks
- 📊 **Monitore execuções** e métricas de performance

## Quando Usar Workflows?

Use workflows quando precisar:

- Processar múltiplas etapas em sequência
- Tomar decisões baseadas em condições
- Integrar com sistemas externos
- Automatizar tarefas que envolvem várias ferramentas
- Criar processos que se repetem regularmente

## Componentes de um Workflow

### Starter (Iniciador)

Define como o workflow é acionado:

- **Agendamento**: Executa em horários específicos
- **Evento**: Dispara quando algo acontece (email recebido, arquivo editado)
- **Webhook**: Acionado por requisição HTTP externa
- **Manual**: Executado manualmente pelo usuário

### Actions (Ações)

São os passos que o workflow executa:

- **Agentes de IA**: Perguntar a um agente ou usar habilidades de IA
- **Ferramentas**: Verificar condições, filtrar dados, enviar webhooks
- **Gmail**: Enviar emails, criar rascunhos
- **Decisões**: Lógica condicional (if/else)

### Steps (Passos)

Cada ação é um passo no workflow. Os passos são executados em ordem e podem depender uns dos outros.

## Criando seu Primeiro Workflow

<Steps>
  <Step title="Acessar o Builder de Workflows">
    
    
    1. No menu lateral, clique em **Builder**
    2. Selecione **Workflows**
    3. Clique em **Criar Novo Workflow**
  </Step>
  
  <Step title="Escolher um Starter">
    
    Selecione como o workflow será acionado:
    
    - **Quando recebo um email**: Dispara ao receber emails
    - **Em um agendamento**: Executa em horários definidos
    - **Quando sou mencionado**: Acionado por menções
    - **Quando um arquivo é editado**: Dispara em mudanças de arquivos
  </Step>
  
  <Step title="Adicionar Ações">
    
    
    Adicione os passos que o workflow deve executar:
    
    1. Clique em **Add step** ou na caixa vazia
    2. Escolha uma ação do menu lateral
    3. Configure os parâmetros da ação
    4. Repita para adicionar mais ações
  </Step>
  
  <Step title="Configurar Decisões">
    
    
    Use ações de decisão para criar lógica condicional:
    
    - **Decide**: Avalia uma condição
    - **Check if**: Verifica se uma condição é verdadeira
    - **Filter**: Filtra dados baseado em critérios
  </Step>
  
  <Step title="Testar o Workflow">
    
    
    Antes de ativar:
    
    1. Clique em **Test run** para executar um teste
    2. Verifique se todas as ações executam corretamente
    3. Revise os logs de execução
  </Step>
  
  <Step title="Ativar">
    
    
    Quando estiver pronto:
    
    1. Clique em **Turn on** para ativar o workflow
    2. O workflow começará a executar automaticamente conforme o starter configurado
  </Step>
</Steps>

## Exemplos de Workflows

### Workflow de Suporte por Email

1. **Starter**: Quando recebo um email
2. **Action**: Perguntar ao agente de suporte sobre o conteúdo
3. **Action**: Se a resposta for positiva, enviar email de confirmação
4. **Action**: Se a resposta for negativa, criar ticket no sistema

### Workflow de Relatório Semanal

1. **Starter**: Em um agendamento (toda segunda-feira às 9h)
2. **Action**: Extrair dados do dashboard
3. **Action**: Resumir dados com IA
4. **Action**: Enviar email com relatório

<Card title="Documentação Workflow" icon="arrow-progress" href="/agent/index">
Acesse a documentação geral do módulo de Workflow, para aprender mais.
</Card>

## Dicas

- 💡 Comece simples: Crie workflows básicos primeiro
- 🧪 Teste sempre: Use "Test run" antes de ativar
- 📝 Documente: Adicione descrições claras para cada passo
- 🔍 Monitore: Acompanhe métricas de execução regularmente
