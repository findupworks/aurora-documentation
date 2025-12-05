---
title: Personalidade
---

# Configurando a Personalidade do Agente

A personalidade do seu agente define como ele interage com os usuários. Uma personalidade bem configurada cria experiências mais naturais e engajadoras.

## Elementos da Personalidade

### Tom de Voz

O tom de voz define o estilo de comunicação:

- **Formal**: Linguagem profissional e respeitosa
- **Casual**: Conversação descontraída e amigável
- **Técnico**: Foco em precisão e detalhes técnicos
- **Criativo**: Linguagem expressiva e envolvente

### Estilo de Resposta

Configure como o agente estrutura suas respostas:

- **Direto**: Respostas curtas e objetivas
- **Detalhado**: Explicações completas e contextuais
- **Conversacional**: Diálogo natural e interativo
- **Estruturado**: Informações organizadas em listas e seções

### Comportamento

Defina regras de comportamento:

- **Empatia**: Nível de compreensão emocional
- **Assertividade**: Capacidade de tomar decisões
- **Criatividade**: Uso de soluções inovadoras
- **Precisão**: Foco em exatidão e fatos

## Configurando no Aurora AI

<Steps>
  <Step title="Acessar Configurações de Personalidade">
    <p>
      Abra o agente que deseja configurar, navegue até a aba{" "}
      <strong>Personalidade</strong>.
    </p>
  </Step>

  <Step title="Definir Tom de Voz">
    <p>Selecione o tom de voz principal ou crie um customizado:</p>
    <p>
      <p>Exemplo de tom formal:</p>
      <div className="bg-primary rounded-3xl rounded-bl-none p-3 text-white inline-block">
      "Bom dia. Como posso ajudá-lo hoje?"
      </div>
      <p>Exemplo de tom casual:</p>
      <div className="bg-primary rounded-3xl rounded-bl-none p-3 text-white inline-block">
      "Oi! Tudo bem? Em que posso ajudar?"
      </div>
    </p>
  </Step>

  <Step title="Configurar Estilo">
    <p>Escolha como o agente deve estruturar respostas:</p>
    <ul>
      <li>Prefere listas ou parágrafos?</li>
      <li>Deve fazer perguntas de acompanhamento?</li>
      <li>Qual o tamanho ideal das respostas?</li>
    </ul>
  </Step>

  <Step title="Definir Limitações">
    <p>Estabeleça o que o agente <strong>não deve</strong> fazer:</p>
    <ul>
      <li>Não deve fazer promessas específicas</li>
      <li>Não deve fornecer informações médicas</li>
      <li>Não deve processar pagamentos diretamente</li>
      <li>etc.</li>
    </ul>
  </Step>

  <Step title="Testar">
    <p>Use o playground para testar diferentes cenários:</p>
    <ol>
      <li>Digite perguntas típicas dos usuários</li>
      <li>Observe como o agente responde</li>
      <li>Ajuste a personalidade conforme necessário</li>
    </ol>
  </Step>
</Steps>

## Exemplos de Personalidades

### Agente de Suporte Técnico

- **Tom**: Profissional e empático
- **Estilo**: Direto com detalhes técnicos quando necessário
- **Comportamento**: Foco em resolver problemas rapidamente

### Agente de Vendas

- **Tom**: Amigável e persuasivo
- **Estilo**: Conversacional com perguntas estratégicas
- **Comportamento**: Identifica necessidades e oferece soluções

### Agente Educacional

- **Tom**: Didático e encorajador
- **Estilo**: Detalhado com exemplos práticos
- **Comportamento**: Adapta explicações ao nível do usuário

## Boas Práticas

- ✅ Seja consistente: Mantenha a personalidade em todas as interações
- ✅ Alinhe com a marca: A personalidade deve refletir os valores da sua organização
- ✅ Considere o público: Adapte o tom ao público-alvo
- ✅ Teste regularmente: Personalidades podem precisar de ajustes ao longo do tempo

## Próximos Passos

<Columns cols={2}>

<Card
  title="Adicionando Conhecimento aos Agentes"
  icon="book"
  href="/agent/pt-BR/knowledge">
Conecte documentos, coleções RAG e bases de dados ao seu agente para fornecer respostas mais precisas e contextualizadas.
</Card>

<Card
  title="Configurando Canais de Comunicação"
  icon="message"
  href="/agent/pt-BR/channels">
Configure onde seu agente estará disponível: chat web, email, webhooks, embed e outros canais de comunicação.
</Card>

<Card
  title="Testando e Otimizando Agentes"
  icon="flask"
  href="/agent/pt-BR/testing">
Use o playground para testar respostas, identificar problemas e otimizar o desempenho do seu agente antes de publicar.
</Card>

</Columns>
