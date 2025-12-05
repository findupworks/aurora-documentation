---
title: Referência Completa de Campos
description: Documentação detalhada de todos os campos e opções na edição de agentes
---

# Referência Completa de Campos

Esta página documenta todos os campos disponíveis na edição de agentes, suas opções e como usá-los.

## Seção: Informações Básicas

<Card title="Campos Básicos" icon="info">
  Configure as informações fundamentais do agente, incluindo nome, descrição e modelo de IA.
</Card>

### Nome

<Accordion title="Campo: Nome">
  **Tipo**: Texto (obrigatório)  
  **Limite**: Máximo 100 caracteres  
  **Placeholder**: "Nomeie seu Agente"

    **Descrição**:
    Nome identificador do agente. Este nome será usado para identificar o agente em toda a plataforma, incluindo listas, dashboards e relatórios.

    **Exemplos**:

    - "Assistente de Suporte Técnico"
    - "Agente de Vendas"
    - "Consultor de Produto"

    **Dicas**:

    - Use nomes descritivos e específicos
    - Evite nomes genéricos como "Agente 1"
    - Considere incluir o propósito no nome

</Accordion>

### Descrição

<Accordion title="Campo: Descrição">
  **Tipo**: Texto (opcional)  
  **Limite**: Máximo 500 caracteres  
  **Placeholder**: "Adicione uma breve descrição sobre o que este Agente faz"

**Descrição**:  
 Descrição breve sobre o propósito e funcionalidade do agente. Esta descrição ajuda a entender rapidamente o que o agente faz e quando usá-lo.

**Exemplos**:

- "Assistente especializado em resolver problemas técnicos de software"
- "Agente de vendas focado em produtos empresariais"
- "Consultor que ajuda clientes a escolher o plano ideal"

**Dicas**:

- Seja específico sobre o propósito
- Mencione o público-alvo se relevante
- Mantenha conciso mas informativo

</Accordion>

### Provedor

<Accordion title="Campo: Provedor">
  **Tipo**: Seleção (opcional)  
  **Placeholder**: "Selecione um provedor"

**Descrição**:  
Selecione o provedor de LLM (Large Language Model) que será usado pelo agente. O provedor determina quais modelos estão disponíveis.

**Opções disponíveis**:

- Depende dos provedores configurados na sua organização
- Exemplos comuns: Google (Gemini), OpenAI, Anthropic

**Comportamento**:

- Ao selecionar um provedor, a lista de modelos é atualizada
- Se você mudar o provedor, o modelo selecionado será resetado
- Você pode deixar sem selecionar para usar o padrão do sistema

**Dicas**:

- Escolha baseado em custo, velocidade e qualidade desejada
- Considere os limites do seu plano

</Accordion>

### Modelo

<Accordion title="Campo: Modelo">
  **Tipo**: Seleção (opcional)  
  **Placeholder**: "Selecione um modelo" ou "Selecione um provedor primeiro"

**Descrição**:  
Selecione o modelo de LLM específico que será usado pelo agente. Os modelos disponíveis dependem do provedor selecionado.

**Comportamento**:

- Só fica habilitado após selecionar um provedor
- Cada modelo tem características diferentes de:
  - Capacidade de raciocínio
  - Velocidade de resposta
  - Custo por token
  - Tamanho máximo de contexto

**Dicas**:

- Modelos mais recentes geralmente têm melhor performance
- Modelos maiores são mais caros mas mais capazes
- Considere o caso de uso ao escolher

</Accordion>

## Seção: Persona (Personalidade)

<Card title="Configuração de Personalidade" icon="user">
  Defina como o agente se comporta, comunica e interage com os usuários.
</Card>

### Nome da Persona

<Accordion title="Campo: Nome da Persona">
  **Tipo**: Texto (opcional)  
  **Limite**: Máximo 100 caracteres  
  **Placeholder**: "Nome da Persona"

**Descrição**:  
Nome da personalidade do agente. Define como o agente se apresenta aos usuários. Este nome pode ser diferente do nome do agente.

**Exemplos**:

- "Aurora"
- "Assistente Virtual"
- "Consultor Especializado"

**Dicas**:

- Use um nome amigável e memorável
- Pode ser o mesmo nome do agente ou diferente
- Considere a identidade da marca

</Accordion>

### Tom de Comunicação

<Accordion title="Campo: Tom de Comunicação">
  **Tipo**: Seleção (opcional)

**Descrição**:  
Define o estilo de comunicação do agente. Escolha entre diferentes tons que refletem diferentes abordagens de interação.

**Opções disponíveis**:

<CardGroup cols={3}>
  <Card title="Casual" icon="smile">
    Linguagem descontraída e informal. Ideal para ambientes relaxados e conversas casuais.
  </Card>
  <Card title="Amigável" icon="heart">
    Tom acolhedor e caloroso. Perfeito para criar conexão e confiança com os usuários.
  </Card>
  <Card title="Profissional" icon="briefcase">
    Formal e direto. Adequado para contextos corporativos e técnicos.
  </Card>
</CardGroup>

**Quando usar cada opção**:

- **Casual**: Apps sociais, comunidades, conteúdo informal
- **Amigável**: Suporte ao cliente, onboarding, experiências do usuário
- **Profissional**: B2B, documentação técnica, ambientes corporativos

</Accordion>

### Formalidade

<Accordion title="Campo: Formalidade">
  **Tipo**: Seleção (opcional)

**Descrição**:  
Nível de formalidade na comunicação, de muito formal (corporativo) a muito casual (descontraído).

**Opções disponíveis**:

<Steps>
  <Step title="Muito Formal">
    Linguagem extremamente profissional e respeitosa. Uso de tratamento formal e estrutura corporativa.
    
    **Exemplo**: "Prezado(a) cliente, agradecemos por entrar em contato..."
  </Step>
  <Step title="Formal">
    Tom profissional padrão. Respeitoso mas não excessivamente cerimonioso.
    
    **Exemplo**: "Olá, como posso ajudá-lo hoje?"
  </Step>
  <Step title="Informal">
    Tom amigável mas ainda profissional. Menos rígido que o formal.
    
    **Exemplo**: "Oi! Em que posso ajudar?"
  </Step>
  <Step title="Casual">
    Conversação descontraída. Linguagem cotidiana e acessível.
    
    **Exemplo**: "E aí! Tudo bem? Como posso ajudar?"
  </Step>
  <Step title="Muito Casual">
    Extremamente descontraído. Linguagem muito informal e próxima.
    
    **Exemplo**: "Fala aí! Qual a boa?"
  </Step>
</Steps>

**Dicas**:

- Combine com o Tom de Comunicação para criar o estilo ideal
- Considere o público-alvo e contexto de uso
- Teste diferentes níveis para encontrar o equilíbrio certo

</Accordion>

### Tamanho das Respostas

<Accordion title="Campo: Tamanho das Respostas">
  **Tipo**: Seleção (opcional)

**Descrição**:  
Define o comprimento padrão das respostas do agente. Isso ajuda a controlar o nível de detalhamento.

**Opções disponíveis**:

<CardGroup cols={2}>
  <Card title="Concisa" icon="minimize">
    **1-2 frases**
    
    Respostas curtas e diretas ao ponto. Ideal para respostas rápidas e objetivas.
    
    **Quando usar**: FAQs, respostas rápidas, mobile, quando o usuário quer informação direta
  </Card>
  <Card title="Média" icon="align-center">
    **1 parágrafo**
    
    Respostas de tamanho médio com contexto adequado. Balance entre brevidade e informação.
    
    **Quando usar**: Maioria dos casos, suporte geral, explicações moderadas
  </Card>
  <Card title="Detalhada" icon="maximize">
    **Múltiplos parágrafos**
    
    Respostas completas e contextuais. Ideal para explicações profundas.
    
    **Quando usar**: Documentação técnica, tutoriais, explicações complexas
  </Card>
  <Card title="Explicativa" icon="book-open">
    **Com exemplos**
    
    Respostas detalhadas incluindo exemplos práticos e casos de uso.
    
    **Quando usar**: Ensino, onboarding, guias passo a passo
  </Card>
</CardGroup>

**Dicas**:

- Considere o contexto: mobile vs desktop
- Respostas muito longas podem cansar o usuário
- Respostas muito curtas podem não fornecer contexto suficiente

</Accordion>

### Nível de Interação

<Accordion title="Campo: Nível de Interação">
  **Tipo**: Seleção (opcional)

**Descrição**:  
Define como o agente interage com os usuários, de reativo (só responde) a muito proativo (antecipa necessidades).

**Opções disponíveis**:

<Steps>
  <Step title="Reativo (só responde)">
    O agente apenas responde às perguntas feitas, sem tomar iniciativa.
    
    **Ideal para**: FAQs, sistemas de busca, quando o usuário sabe o que quer
  </Step>
  <Step title="Moderado (faz perguntas)">
    O agente faz perguntas de acompanhamento para entender melhor as necessidades.
    
    **Ideal para**: Suporte técnico, vendas consultivas, diagnóstico de problemas
  </Step>
  <Step title="Proativo (sugere ações)">
    O agente sugere ações e próximos passos baseado no contexto.
    
    **Ideal para**: Onboarding, guias, recomendações
  </Step>
  <Step title="Muito Proativo (antecipa necessidades)">
    O agente antecipa necessidades e oferece soluções antes mesmo de serem solicitadas.
    
    **Ideal para**: Assistente pessoal, recomendações inteligentes, automação
  </Step>
</Steps>

**Dicas**:

- Níveis mais proativos podem ser intrusivos se não bem configurados
- Combine com o Prompt do Sistema para definir comportamento específico
- Teste com usuários reais para encontrar o equilíbrio

</Accordion>

### Emojis

<Accordion title="Campo: Emojis">
  **Tipo**: Switch (ligado/desligado)  
  **Padrão**: Desligado

**Descrição**:  
Permite que o agente use emojis nas respostas para tornar a comunicação mais expressiva e amigável.

**Quando usar**:

- ✅ Comunicação casual e amigável
- ✅ Público jovem ou informal
- ✅ Aplicações sociais ou de entretenimento
- ❌ Contextos muito formais ou corporativos
- ❌ Comunicação técnica ou profissional

**Dicas**:

- Emojis podem melhorar o engajamento em contextos apropriados
- Use com moderação mesmo quando ativado
- Considere o público-alvo antes de ativar

</Accordion>

### Prompt do Sistema

<Accordion title="Campo: Prompt do Sistema">
  **Tipo**: Textarea (opcional)  
  **Limite**: Máximo 5000 caracteres  
  **Placeholder**: "Você é a Aurora, assistente digital da FindUP..."

**Descrição**:  
Instruções principais que definem o papel, personalidade e comportamento do agente. Este prompt orienta todas as respostas do agente e é fundamental para o desempenho.

**Estrutura recomendada**:

```markdown
Você é [nome/role do agente], [descrição do propósito].

Seu objetivo é [objetivo principal].

Ao responder:

- [Regra 1]
- [Regra 2]
- [Regra 3]

Não faça:

- [Limitação 1]
- [Limitação 2]
```

**Exemplo completo**:

```markdown
Você é a Aurora, assistente digital da FindUP especializada em
suporte técnico de software.

Seu objetivo é ajudar usuários a resolver problemas técnicos de
forma clara e eficiente.

Ao responder:

- Seja sempre educado e profissional
- Faça perguntas claras para entender o problema
- Forneça soluções passo a passo
- Se não souber a resposta, seja honesto e ofereça alternativas

Não faça:

- Promessas que não pode cumprir
- Fornecer informações médicas ou legais
- Processar pagamentos diretamente
```

**Dicas**:

- Seja específico sobre o papel e objetivo
- Defina claramente o que fazer e não fazer
- Use exemplos quando útil
- Revise e refine baseado em testes
- Mantenha atualizado conforme o agente evolui

</Accordion>

### Regras Personalizadas

<Accordion title="Campo: Regras Personalizadas">
  **Tipo**: Textarea (opcional)  
  **Limite**: Máximo 5000 caracteres  
  **Placeholder**: "Digite uma regra por linha..."

**Descrição**:  
Regras específicas de comportamento que o agente deve seguir. Digite uma regra por linha. Use '-' para criar listas ou numere para criar sequências.

**Formato**:

```markdown
- Sempre cumprimente o usuário ao iniciar conversa
- Use o nome do usuário quando disponível
- Confirme entendimento antes de executar ações importantes

1. Primeiro, identifique o problema
2. Depois, ofereça soluções
3. Por fim, confirme se resolveu
```

**Exemplos de regras**:

- Comportamento específico: "Sempre ofereça um resumo ao final de explicações longas"
- Formato de resposta: "Use listas numeradas para passos sequenciais"
- Limitações: "Nunca faça promessas sobre prazos de entrega"
- Personalização: "Adapte o nível técnico da explicação ao conhecimento do usuário"

**Dicas**:

- Seja claro e específico
- Uma regra por linha facilita leitura
- Use formatação consistente
- Revise regularmente e ajuste conforme necessário

</Accordion>

## Seção: Placeholder de Input

<Card title="Placeholder de Input" icon="input">
  Configure o texto que aparece no campo de entrada antes do usuário digitar.
</Card>

### Placeholder

<Accordion title="Campo: Placeholder">
  **Tipo**: Texto (opcional)  
  **Limite**: Máximo 200 caracteres

**Descrição**:  
Texto de exemplo que aparece no campo de chat antes do usuário começar a digitar. Ajuda a orientar o usuário sobre o que pode perguntar.

**Exemplos**:

- "Digite sua pergunta aqui..."
- "Como posso ajudar você hoje?"
- "Pergunte qualquer coisa sobre nosso produto"
- "Descreva seu problema ou dúvida"
- "O que você gostaria de saber?"

**Dicas**:

- Seja claro e direto
- Use linguagem amigável
- Considere o contexto de uso
- Pode incluir exemplos: "Ex: Como funciona o produto?"

</Accordion>

## Seção: Iniciadores de Conversa

<Card title="Iniciadores de Conversa" icon="message-square">
  Adicione perguntas pré-definidas que os usuários podem clicar para começar a conversa.
</Card>

### Adicionar Iniciadores

<Steps>
  <Step title="Criar Novo Iniciador">
    Clique no botão **Adicionar Iniciador** ou no ícone **+** na seção de iniciadores.
  </Step>
  <Step title="Escrever o Texto">
    Digite a pergunta ou frase que aparecerá como botão. Seja claro e específico.
    
    **Exemplos**:
    - "Como funciona o produto?"
    - "Preciso de ajuda técnica"
    - "Quero saber sobre preços"
  </Step>
  <Step title="Escolher Ícone (Opcional)">
    Selecione um ícone para tornar o iniciador mais visualmente atraente e fácil de identificar.
    
    **Ícones disponíveis**: Dependem da biblioteca de ícones configurada
  </Step>
  <Step title="Salvar">
    O iniciador será salvo automaticamente e aparecerá na interface do chat.
  </Step>
</Steps>

**Limites e Recomendações**:

- **Máximo recomendado**: 4-6 iniciadores
- **Mínimo**: 0 (não obrigatório)
- **Ordem**: Os iniciadores aparecem na ordem em que foram adicionados

**Boas Práticas**:

- Use perguntas que os usuários realmente fazem
- Seja específico: "Como configurar integração?" é melhor que "Ajuda"
- Organize por categoria ou frequência
- Revise e atualize regularmente baseado em uso

## Seção: Base de Conhecimento

<Card title="Base de Conhecimento" icon="book">
  Conecte documentos e coleções RAG para enriquecer o conhecimento do agente.
</Card>

### Gerenciar Documentos

<Steps>
  <Step title="Abrir Gerenciador">
    Na seção "Base de Conhecimento", clique em **Gerenciar Documentos** ou **Adicionar Documento**.
  </Step>
  <Step title="Escolher Tipo">
    Você pode adicionar:
    
    - **Documentos individuais**: Selecione documentos específicos
    - **Coleções**: Selecione coleções inteiras de documentos
  </Step>
  <Step title="Buscar e Selecionar">
    Use a busca para encontrar documentos rapidamente. Selecione os documentos ou coleções desejados.
  </Step>
  <Step title="Confirmar">
    Clique em **Adicionar** ou **Salvar** para conectar os documentos ao agente.
  </Step>
</Steps>

**Comportamento**:

- Documentos conectados são processados automaticamente
- O conteúdo é indexado para busca RAG
- O agente pode acessar informações dos documentos nas respostas
- Alterações nos documentos são refletidas automaticamente

**Dicas**:

- Conecte documentos específicos e relevantes
- Organize em coleções para facilitar gerenciamento
- Revise regularmente para manter atualizado
- Teste se o agente está usando o conhecimento corretamente

## Seção: Ferramentas (Tools)

<Card title="Ferramentas e Integrações" icon="wrench">
  Adicione ferramentas que expandem as capacidades do agente.
</Card>

### Tipos de Ferramentas

<AccordionGroup>
  <Accordion title="APIs">
    Integrações com serviços externos através de APIs REST.
    
    **Exemplos**:
    - Consultar banco de dados
    - Buscar informações em sistemas externos
    - Executar ações em serviços terceiros
    </Accordion>
  <Accordion title="Webhooks">
    Chamadas HTTP para sistemas externos quando eventos ocorrem.
    
    **Exemplos**:
    - Notificar sistemas quando conversa inicia
    - Enviar dados para CRM
    - Atualizar sistemas externos
    </Accordion>
  <Accordion title="Bancos de Dados">
    Consultas diretas a bases de dados para informações em tempo real.
    
    **Exemplos**:
    - Consultar estoque
    - Verificar status de pedidos
    - Buscar informações de clientes
    </Accordion>
  <Accordion title="Ferramentas Customizadas">
    Ferramentas desenvolvidas especificamente para seu caso de uso.
    
    **Exemplos**:
    - Calculadoras específicas
    - Processadores de dados customizados
    - Integrações proprietárias
    </Accordion>
</AccordionGroup>

### Adicionar Ferramenta

<Steps>
  <Step title="Abrir Gerenciador">
    Clique em **Gerenciar Ferramentas** ou **Adicionar Ferramenta** na seção Tools.
  </Step>
  <Step title="Selecionar Tipo">
    Escolha o tipo de ferramenta que deseja adicionar da lista disponível.
  </Step>
  <Step title="Configurar Parâmetros">
    Preencha os campos necessários:
    
    - **Nome**: Nome descritivo da ferramenta
    - **Endpoint/URL**: URL ou endpoint da ferramenta
    - **Autenticação**: Credenciais se necessário
    - **Descrição**: O que a ferramenta faz
    - **Parâmetros**: Campos de entrada necessários
  </Step>
  <Step title="Testar">
    Use o botão de teste para verificar se a ferramenta está funcionando corretamente antes de salvar.
  </Step>
  <Step title="Salvar">
    Salve a ferramenta e ela estará disponível para o agente usar durante as conversas.
  </Step>
</Steps>

**Dicas**:

- Teste sempre antes de usar em produção
- Documente bem o propósito de cada ferramenta
- Monitore uso e performance
- Mantenha credenciais seguras



## Seção: Configurações Gerais

<Card title="Configurações Gerais" icon="settings">
  Ajuste configurações avançadas do agente relacionadas ao modelo de IA e comportamento.
</Card>

### Model Temperature (Temperatura do Modelo)

<Accordion title="Campo: Model Temperature">
  **Tipo**: Número  
  **Range**: 0 a 2  
  **Padrão**: 0  
  **Step**: 0.1

**Descrição**:  
Controla a criatividade e aleatoriedade das respostas do modelo de IA.

**Valores e Significado**:

<CardGroup cols={3}>
  <Card title="0.0 - 0.3" icon="target">
    **Muito Determinístico**
    
    Respostas muito consistentes e previsíveis. Ideal para casos onde precisão é crítica.
    
    **Use para**: FAQs, informações factuais, respostas padronizadas
  </Card>
  <Card title="0.4 - 0.7" icon="balance">
    **Balanceado**
    
    Balance entre consistência e criatividade. Bom para maioria dos casos.
    
    **Use para**: Suporte geral, conversas naturais, explicações
  </Card>
  <Card title="0.8 - 2.0" icon="sparkles">
    **Muito Criativo**
    
    Respostas mais variadas e criativas. Pode ser menos consistente.
    
    **Use para**: Conteúdo criativo, brainstorming, geração de ideias
  </Card>
</CardGroup>

**Recomendações**:

- **Suporte técnico**: 0.2 - 0.4
- **Vendas/Atendimento**: 0.5 - 0.7
- **Criativo/Conteúdo**: 0.7 - 1.0
- **Padrão**: 0.5 - 0.7

**Dicas**:

- Valores muito baixos podem tornar respostas robóticas
- Valores muito altos podem reduzir consistência
- Teste diferentes valores para encontrar o ideal
- Considere o caso de uso ao ajustar

</Accordion>

### Max Allowed Tokens

<Accordion title="Campo: Max Allowed Tokens">
  **Tipo**: Número  
  **Mínimo**: 1  
  **Padrão**: 0 (sem limite)

**Descrição**:  
Define o número máximo de tokens que o agente pode usar em uma resposta. Tokens são unidades de texto processadas pelo modelo.

**Conversão aproximada**:

- 1 token ≈ 0.75 palavras em inglês
- 1 token ≈ 0.5 palavras em português
- 100 tokens ≈ 75 palavras (inglês) ou 50 palavras (português)

**Valores Recomendados**:

<CardGroup cols={2}>
  <Card title="Respostas Curtas" icon="minimize">
    **500 - 1000 tokens**
    
    Aproximadamente 375-750 palavras (inglês) ou 250-500 palavras (português).
    
    Ideal para respostas rápidas e objetivas.
  </Card>
  <Card title="Respostas Médias" icon="align-center">
    **1000 - 2000 tokens**
    
    Aproximadamente 750-1500 palavras (inglês) ou 500-1000 palavras (português).
    
    Ideal para maioria dos casos de uso.
  </Card>
  <Card title="Respostas Longas" icon="maximize">
    **2000 - 4000 tokens**
    
    Aproximadamente 1500-3000 palavras (inglês) ou 1000-2000 palavras (português).
    
    Ideal para explicações detalhadas e tutoriais.
  </Card>
  <Card title="Sem Limite" icon="infinity">
    **0 (padrão)**
    
    O modelo usa quantos tokens forem necessários, respeitando apenas os limites do próprio modelo.
    
    Use quando não quiser restringir o tamanho das respostas.
  </Card>
</CardGroup>

**Dicas**:

- Limites menores reduzem custos
- Limites maiores permitem respostas mais completas
- Considere o contexto: mobile vs desktop
- Teste para encontrar o equilíbrio ideal

</Accordion>

### Timeout (ms)

<Accordion title="Campo: Timeout">
  **Tipo**: Número (milissegundos)  
  **Range**: 1000 a 300000 (1 segundo a 5 minutos)  
  **Padrão**: Não definido (usa padrão do sistema)

**Descrição**:  
Tempo máximo que o sistema aguarda por uma resposta do modelo antes de considerar timeout.

**Valores Recomendados**:

- **Rápido**: 5000-10000ms (5-10 segundos) - Para respostas simples
- **Padrão**: 15000-30000ms (15-30 segundos) - Para maioria dos casos
- **Longo**: 60000-120000ms (1-2 minutos) - Para processamento complexo
- **Muito Longo**: 180000-300000ms (3-5 minutos) - Para tarefas muito complexas

**Dicas**:

- Timeouts muito curtos podem causar erros desnecessários
- Timeouts muito longos podem deixar usuários esperando
- Considere a complexidade das tarefas do agente
- Ajuste baseado em feedback dos usuários

</Accordion>

### Max Simultaneous Chat

<Accordion title="Campo: Max Simultaneous Chat">
  **Tipo**: Número  
  **Range**: 1 a 100  
  **Padrão**: Não definido (sem limite)

**Descrição**:  
Número máximo de conversas simultâneas que o agente pode processar ao mesmo tempo.

**Quando usar**:

- **Sem limite (padrão)**: Para maioria dos casos, permite escalar conforme necessário
- **Limite definido**: Para controlar custos ou garantir qualidade em casos específicos

**Dicas**:

- Limites muito baixos podem causar filas de espera
- Considere seus recursos e custos
- Monitore uso para ajustar se necessário

</Accordion>

### Disable Response Cache

<Accordion title="Campo: Disable Response Cache">
  **Tipo**: Switch (ligado/desligado)  
  **Padrão**: Desligado (cache habilitado)

**Descrição**:  
Quando desabilitado (padrão), o sistema cacheia respostas para perguntas similares, melhorando velocidade e reduzindo custos. Quando habilitado, desativa o cache.

**Quando desabilitar cache**:

- ✅ Respostas precisam ser sempre atualizadas
- ✅ Dados dinâmicos que mudam frequentemente
- ✅ Quando personalização extrema é necessária

**Quando manter cache habilitado**:

- ✅ Perguntas frequentes (FAQs)
- ✅ Informações estáticas
- ✅ Para reduzir custos e melhorar velocidade

**Dicas**:

- Cache geralmente melhora performance e reduz custos
- Desabilite apenas quando realmente necessário
- Monitore impacto ao desabilitar

</Accordion>

### Citations

<Accordion title="Campo: Citations">
  **Tipo**: Switch (ligado/desligado)  
  **Padrão**: Desligado

**Descrição**:  
Quando habilitado, o agente mostra citações das fontes de conhecimento usadas nas respostas (documentos, coleções RAG).

**Quando usar**:

- ✅ Quando transparência sobre fontes é importante
- ✅ Para validação e verificação de informações
- ✅ Em contextos educacionais ou técnicos
- ❌ Quando citações podem poluir a interface
- ❌ Para conversas muito casuais

**Dicas**:

- Citações aumentam confiança do usuário
- Podem tornar respostas mais longas
- Úteis para conhecimento baseado em documentos

</Accordion>

### Show Steps

<Accordion title="Campo: Show Steps">
  **Tipo**: Switch (ligado/desligado)  
  **Padrão**: Desligado

**Descrição**:  
Quando habilitado, o agente mostra os passos de raciocínio ou processamento ao responder.

**Quando usar**:

- ✅ Para tarefas complexas que requerem múltiplos passos
- ✅ Quando transparência do processo é importante
- ✅ Para debugging e otimização
- ❌ Para respostas simples e diretas
- ❌ Quando pode confundir o usuário

**Dicas**:

- Útil para entender como o agente chegou à resposta
- Pode tornar respostas mais longas
- Bom para casos técnicos ou educacionais

</Accordion>

### Follow Up Questions

<Accordion title="Campo: Follow Up Questions">
  **Tipo**: Switch (ligado/desligado)  
  **Padrão**: Desligado

**Descrição**:  
Quando habilitado, o agente sugere perguntas de acompanhamento após responder, ajudando a continuar a conversa.

**Quando usar**:

- ✅ Para guiar usuários através de processos
- ✅ Para descobrir necessidades adicionais
- ✅ Para melhorar engajamento
- ❌ Quando usuários querem respostas diretas
- ❌ Para casos muito simples

**Dicas**:

- Melhora engajamento e descoberta de necessidades
- Pode ser intrusivo se mal configurado
- Combine com Nível de Interação apropriado

</Accordion>

### Timeout (ms)

<Accordion title="Campo: Timeout">
  **Tipo**: Número (milissegundos)  
  **Range**: 1000 a 300000 (1 segundo a 5 minutos)  
  **Padrão**: Não definido (usa padrão do sistema)

**Descrição**:  
Tempo máximo que o sistema aguarda por uma resposta do modelo antes de considerar timeout.

**Valores Recomendados**:

- **Rápido**: 5000-10000ms (5-10 segundos) - Para respostas simples
- **Padrão**: 15000-30000ms (15-30 segundos) - Para maioria dos casos
- **Longo**: 60000-120000ms (1-2 minutos) - Para processamento complexo
- **Muito Longo**: 180000-300000ms (3-5 minutos) - Para tarefas muito complexas

**Dicas**:

- Timeouts muito curtos podem causar erros desnecessários
- Timeouts muito longos podem deixar usuários esperando
- Considere a complexidade das tarefas do agente
- Ajuste baseado em feedback dos usuários

</Accordion>

### Max Simultaneous Chat

<Accordion title="Campo: Max Simultaneous Chat">
  **Tipo**: Número  
  **Range**: 1 a 100  
  **Padrão**: Não definido (sem limite)

**Descrição**:  
Número máximo de conversas simultâneas que o agente pode processar ao mesmo tempo.

**Quando usar**:

- **Sem limite (padrão)**: Para maioria dos casos, permite escalar conforme necessário
- **Limite definido**: Para controlar custos ou garantir qualidade em casos específicos

**Dicas**:

- Limites muito baixos podem causar filas de espera
- Considere seus recursos e custos
- Monitore uso para ajustar se necessário

</Accordion>

### Disable Response Cache

<Accordion title="Campo: Disable Response Cache">
  **Tipo**: Switch (ligado/desligado)  
  **Padrão**: Desligado (cache habilitado)

**Descrição**:  
Quando desabilitado (padrão), o sistema cacheia respostas para perguntas similares, melhorando velocidade e reduzindo custos. Quando habilitado, desativa o cache.

**Quando desabilitar cache**:

- ✅ Respostas precisam ser sempre atualizadas
- ✅ Dados dinâmicos que mudam frequentemente
- ✅ Quando personalização extrema é necessária

**Quando manter cache habilitado**:

- ✅ Perguntas frequentes (FAQs)
- ✅ Informações estáticas
- ✅ Para reduzir custos e melhorar velocidade

**Dicas**:

- Cache geralmente melhora performance e reduz custos
- Desabilite apenas quando realmente necessário
- Monitore impacto ao desabilitar

</Accordion>

### Citations

<Accordion title="Campo: Citations">
  **Tipo**: Switch (ligado/desligado)  
  **Padrão**: Desligado

**Descrição**:  
Quando habilitado, o agente mostra citações das fontes de conhecimento usadas nas respostas (documentos, coleções RAG).

**Quando usar**:

- ✅ Quando transparência sobre fontes é importante
- ✅ Para validação e verificação de informações
- ✅ Em contextos educacionais ou técnicos
- ❌ Quando citações podem poluir a interface
- ❌ Para conversas muito casuais

**Dicas**:

- Citações aumentam confiança do usuário
- Podem tornar respostas mais longas
- Úteis para conhecimento baseado em documentos

</Accordion>

### Show Steps

<Accordion title="Campo: Show Steps">
  **Tipo**: Switch (ligado/desligado)  
  **Padrão**: Desligado

**Descrição**:  
Quando habilitado, o agente mostra os passos de raciocínio ou processamento ao responder.

**Quando usar**:

- ✅ Para tarefas complexas que requerem múltiplos passos
- ✅ Quando transparência do processo é importante
- ✅ Para debugging e otimização
- ❌ Para respostas simples e diretas
- ❌ Quando pode confundir o usuário

**Dicas**:

- Útil para entender como o agente chegou à resposta
- Pode tornar respostas mais longas
- Bom para casos técnicos ou educacionais

</Accordion>

### Follow Up Questions

<Accordion title="Campo: Follow Up Questions">
  **Tipo**: Switch (ligado/desligado)  
  **Padrão**: Desligado

**Descrição**:  
Quando habilitado, o agente sugere perguntas de acompanhamento após responder, ajudando a continuar a conversa.

**Quando usar**:

- ✅ Para guiar usuários através de processos
- ✅ Para descobrir necessidades adicionais
- ✅ Para melhorar engajamento
- ❌ Quando usuários querem respostas diretas
- ❌ Para casos muito simples

**Dicas**:

- Melhora engajamento e descoberta de necessidades
- Pode ser intrusivo se mal configurado
- Combine com Nível de Interação apropriado

</Accordion>

## Seção: Acesso e Segurança

<Card title="Acesso e Segurança" icon="lock">
  Configure quem pode acessar e conversar com o agente.
</Card>

### Security Access

<Accordion title="Campo: Security Access">
  **Tipo**: Seleção (obrigatório)  
  **Padrão**: PRIVATE

**Descrição**:  
Define o nível de acesso ao agente. Controla quem pode ver e usar o agente.

**Opções disponíveis**:

<CardGroup cols={2}>
  <Card title="Privado" icon="lock">
    **PRIVATE**
    
    Apenas você pode acessar e usar o agente. Ideal para desenvolvimento e testes.
    
    **Quando usar**: Desenvolvimento, testes, agentes pessoais
  </Card>
  <Card title="Público" icon="globe">
    **PUBLIC**
    
    Qualquer pessoa pode acessar o agente, mesmo sem estar na organização.
    
    **Quando usar**: Agentes públicos, demos, casos de uso externos
  </Card>
  <Card title="Organização" icon="building">
    **ORGANIZATION**
    
    Todos os membros da organização podem acessar o agente.
    
    **Quando usar**: Agentes internos, uso geral da organização
  </Card>
  <Card title="Equipe" icon="users">
    **TEAM**
    
    Apenas membros de equipes específicas podem acessar. Você seleciona quais equipes.
    
    **Quando usar**: Agentes específicos de departamento ou projeto
  </Card>
  <Card title="Restrito" icon="shield">
    **RESTRICTED**
    
    Acesso restrito a equipes e/ou usuários específicos selecionados manualmente.
    
    **Quando usar**: Acesso muito granular, casos específicos de segurança
  </Card>
</CardGroup>

**Configurações Adicionais**:

Quando você seleciona **TEAM** ou **RESTRICTED**, campos adicionais aparecem:

#### Times com Acesso (TEAM e RESTRICTED)

- **Tipo**: Checkboxes múltiplos
- **Descrição**: Selecione quais equipes podem acessar o agente
- **Comportamento**:
  - Para TEAM: Pelo menos uma equipe deve ser selecionada
  - Para RESTRICTED: Opcional, pode combinar com usuários específicos

#### Usuários com Acesso (RESTRICTED apenas)

- **Tipo**: Checkboxes múltiplos
- **Descrição**: Selecione usuários específicos que podem acessar o agente
- **Comportamento**: Opcional, pode combinar com equipes

**Dicas**:

- Comece com PRIVATE durante desenvolvimento
- Use ORGANIZATION para agentes internos gerais
- Use TEAM para agentes específicos de departamento
- Use RESTRICTED para casos muito específicos
- Revise permissões regularmente por segurança

</Accordion>

## Salvando Alterações

<Card title="Sistema de Auto-Save" icon="save">
  Todas as alterações são salvas automaticamente enquanto você edita.
</Card>

**Indicador de Status**:

Você verá um indicador no canto superior direito mostrando:

- **Salvando...**: Quando há alterações sendo salvas
- **Salvo**: Quando todas as alterações foram salvas com sucesso
- **Erro**: Se houver algum problema ao salvar

**Comportamento**:

- Alterações são salvas automaticamente após alguns segundos de inatividade
- Você também pode clicar em **Salvar alterações** para salvar manualmente
- Não é necessário salvar antes de navegar para outras páginas

<Warning>
  Certifique-se de ter conexão com a internet para que as alterações sejam salvas corretamente.
</Warning>

## Próximos Passos

Após configurar todos os campos:

<CardGroup cols={2}>
  <Card title="Testar Agente" icon="play" href="/docs/agents/testing">
    Use o playground para testar o agente antes de publicar
  </Card>
  <Card title="Configurar Canais" icon="radio" href="/docs/agents/channels">
    Configure onde o agente estará disponível
  </Card>
  <Card title="Ver Analytics" icon="bar-chart" href="/docs/agents/analytics">
    Monitore performance e uso do agente
  </Card>
  <Card title="Gerenciar Conversas" icon="message-square" href="/docs/agents/conversations">
    Veja e gerencie conversas do agente
  </Card>
</CardGroup>
