#  App de Finanças Pessoais com Vibe Coding

PDR refinado no Copilot Web:

````
# PRD - Agente Financeiro Conversacional

## Visão do Produto
Criar um aplicativo de finanças pessoais que permita aos usuários registrar, consultar e analisar sua vida financeira através de conversas em linguagem natural.
O aplicativo deve eliminar a necessidade de formulários complexos, categorizando automaticamente as informações fornecidas pelo usuário e oferecendo recomendações financeiras personalizadas.

### Proposta de Valor
Gerenciar finanças deve ser tão simples quanto conversar com um amigo.
Em vez de preencher planilhas ou navegar por múltiplas telas, o usuário apenas conversa com o aplicativo.

Exemplos:
- "Gastei R$ 45 no almoço."
- "Recebi meu salário de R$ 4.500."
- "Quanto gastei com transporte este mês?"
- "Quero economizar R$ 2.000 para minhas férias."
---

## Problema
Muitas pessoas abandonam o controle financeiro porque:
- Registrar gastos exige muito esforço manual.
- A categorização das despesas é trabalhosa.
- Os relatórios são difíceis de compreender.
- Os aplicativos focam em usuários avançados.
- Falta orientação prática para melhorar hábitos financeiros.

Como consequência, os usuários não mantêm consistência no acompanhamento das finanças e acabam perdendo visibilidade sobre seus gastos.
---

## Objetivo
Permitir que qualquer pessoa organize suas finanças através de conversas simples, aumentando a frequência de uso e reduzindo o esforço necessário para registrar receitas e despesas.
---

## Público-Alvo

### Primário
Pessoas iniciantes em educação financeira que:
- Nunca utilizaram aplicativos financeiros.
- Consideram planilhas complicadas.
- Desejam entender para onde seu dinheiro está indo.

### Secundário
Usuários que já usam apps financeiros, mas buscam uma experiência mais rápida e intuitiva.
---

## Princípios do Produto

### Simplicidade
Toda interação deve ser simples, direta e compreensível para iniciantes.

### Educação Financeira
O produto deve ajudar o usuário a desenvolver hábitos financeiros melhores ao longo do tempo.

### Design Universal
O produto deve seguir os princípios de Design Universal, garantindo que o maior número possível de pessoas consiga utilizá-lo de forma eficiente, confortável e independente, independentemente de idade, familiaridade com tecnologia ou condições físicas, cognitivas e sensoriais.

A experiência deve ser inclusiva por padrão, sem necessidade de versões separadas para diferentes perfis de usuários.
---

## MVP
O MVP deve validar se usuários conseguem registrar e consultar informações financeiras utilizando apenas linguagem natural.

### Hipótese Principal
Se o registro financeiro ocorrer por conversa, os usuários registrarão mais transações do que fariam em aplicativos tradicionais.
---

## Funcionalidades Principais

### 1. Registro Conversacional

O sistema deve compreender mensagens como:

- "Gastei R$ 80 no supermercado."
- "Paguei R$ 120 de energia."
- "Recebi R$ 5.000 de salário."

Campos extraídos automaticamente:

- Valor
- Tipo (receita ou despesa)
- Categoria
- Data
- Descrição
---

### 2. Categorização Automática

O sistema deve sugerir categorias automaticamente.

Categorias iniciais:

- Alimentação
- Transporte
- Moradia
- Saúde
- Educação
- Lazer
- Compras
- Contas
- Investimentos
- Outros

O usuário poderá corrigir a categoria quando desejar.

---

### 3. Metas Financeiras

Permitir a criação de metas.

Exemplos:

- Economizar R$ 5.000 para uma viagem.
- Juntar R$ 20.000 para entrada de um imóvel.
- Construir uma reserva de emergência.

Recursos:

- Meta alvo
- Prazo
- Acompanhamento de progresso
- Percentual atingido

---

### 4. Agente Financeiro Inteligente

Assistente virtual que analisa o comportamento financeiro.

Exemplos de recomendações:

- "Você gastou 25% mais com delivery neste mês."
- "Sua categoria de transporte aumentou nos últimos 30 dias."
- "Você está economizando R$ 300 por mês. Nesse ritmo alcançará sua meta em 8 meses."

---

### 5. Dashboard Simplificado

Visualizações simples para iniciantes.

Indicadores:

- Receitas do mês
- Despesas do mês
- Saldo atual
- Categoria com maior gasto
- Evolução mensal

Visualizações:

- Distribuição de gastos por categoria
- Evolução mensal de receitas e despesas
- Evolução das metas financeiras

---

## Diretrizes de Design Universal

### Uso Simples e Intuitivo

- Linguagem simples e acessível.
- Evitar jargões financeiros.
- Navegação previsível.
- Fluxos guiados para novos usuários.

### Múltiplas Formas de Interação

Suporte para:

- Digitação por texto.
- Comandos por voz.
- Navegação por teclado.
- Compatibilidade com leitores de tela.

### Baixa Carga Cognitiva

- Mostrar apenas informações relevantes.
- Destacar ações principais.
- Organizar informações em etapas simples.

### Acessibilidade Visual

- Alto contraste.
- Fontes escaláveis.
- Modo claro e escuro.
- Não depender apenas de cores para transmitir informações.

### Tolerância a Erros

- Permitir editar transações.
- Confirmar exclusões importantes.
- Sugerir correções para informações ambíguas.

Exemplo:

Usuário: "Gastei R$ 5000 no almoço."

Sistema: "Você quis registrar R$ 50,00 ou R$ 5.000,00?"

### Mobile First

A experiência deve ser otimizada inicialmente para smartphones e adaptada para tablets e desktops.

---

## Fluxo Principal do Usuário

### Primeiro Acesso

1. Criar conta.
2. Informar renda mensal aproximada.
3. Definir primeira meta financeira.
4. Conhecer o Agente Financeiro.

### Uso Diário

1. Usuário envia mensagem.
2. Sistema interpreta a mensagem.
3. Transação é criada automaticamente.
4. Categoria é sugerida.
5. Usuário confirma ou corrige.

### Consulta Financeira

Exemplos:

- "Quanto gastei este mês?"
- "Quanto economizei?"
- "Qual foi minha maior despesa?"
- "Quanto falta para atingir minha meta?"

O sistema responde em linguagem natural e apresenta indicadores visuais.

---

## Principais Telas

### Tela Inicial

- Resumo financeiro.
- Saldo atual.
- Metas em andamento.

### Tela de Chat

- Conversa com o Agente Financeiro.
- Registro de receitas e despesas.

### Tela de Histórico

- Lista de transações.
- Filtros por período e categoria.

### Tela de Metas

- Criação de metas.
- Acompanhamento de progresso.

### Tela de Relatórios

- Indicadores financeiros.
- Insights automáticos.
- Evolução de receitas e despesas.

---

## Critérios de Sucesso do MVP

### Ativação

- 70% dos usuários registram pelo menos uma transação no primeiro dia.

### Engajamento

- 50% dos usuários retornam em até 7 dias.

### Retenção

- 30% dos usuários continuam usando após 30 dias.

### Precisão

- 85% das categorias são classificadas corretamente sem edição manual.

### Usabilidade

- 90% dos usuários registram uma despesa em menos de 60 segundos.
- 80% concluem tarefas básicas sem consultar ajuda.
- Nenhuma funcionalidade crítica depende exclusivamente de visão, audição ou uso de mouse.

---

## Requisitos Não Funcionais

### Usabilidade

- Interface simples e amigável.
- Linguagem acessível.
- Fluxo com poucos passos.
- Consistência visual em toda a aplicação.

### Performance

- Respostas do agente em até 3 segundos.

### Segurança

- Dados criptografados.
- Conformidade com LGPD.
- Consentimento explícito para armazenamento de dados.

### Escalabilidade

- Arquitetura preparada para expansão futura.
- Suporte para novos agentes, categorias e funcionalidades financeiras.

````

## Interações com o Loveble
- Crie um APP de Finanças Pessoais com base no seguinte PRD (Product Requirements Document): {PDR}
- Corrigir erros {Reply "continuar" and I'll fix these errors, build the missing pages (dashboard, chat, history, goals, reports and settings)}

Resultado final no Loveble: https://trilha-das-finan.lovable.app
<img width="1887" height="852" alt="image" src="https://github.com/user-attachments/assets/12b814ce-0d26-42da-a8c6-cc066b3a4586" />


## Funcionalidades do App Conta Comigo:

# Conta Comigo

Aplicativo de finanças pessoais com foco em simplicidade, acessibilidade e educação financeira. O principal diferencial é a interação por meio de linguagem natural, permitindo que o usuário registre e consulte informações financeiras como se estivesse conversando com um assistente pessoal.

## Visão Geral

O Conta Comigo foi criado para ajudar pessoas a organizarem suas finanças sem depender de planilhas complexas ou processos manuais demorados.

A experiência é centrada em conversação, permitindo registrar receitas, despesas e acompanhar objetivos financeiros de forma intuitiva e acessível.

---

## Principais Funcionalidades

### Dashboard Financeiro

O painel inicial apresenta um resumo da situação financeira do usuário em tempo real.

Indicadores disponíveis:

- Saldo atual
- Total recebido no mês
- Total gasto no mês
- Categoria com maior gasto
- Resumo financeiro consolidado

Benefícios:

- Visão rápida da saúde financeira
- Acompanhamento contínuo dos resultados
- Redução da necessidade de análises complexas

---

### Registro Conversacional

O usuário pode registrar movimentações financeiras através de linguagem natural.

Exemplos:

```text
Gastei R$ 50 no almoço.
Recebi R$ 500 de um trabalho.
Paguei R$ 120 de energia.
```

O sistema interpreta automaticamente:

- Valor
- Tipo da transação (receita ou despesa)
- Categoria
- Data
- Descrição

Objetivo:

Eliminar formulários extensos e tornar o registro financeiro mais rápido e natural.

---

### Categorização Automática

As movimentações são classificadas automaticamente em categorias como:

- Alimentação
- Transporte
- Moradia
- Saúde
- Educação
- Lazer
- Compras
- Contas
- Investimentos
- Outros

Benefícios:

- Menos trabalho manual
- Melhor organização financeira
- Relatórios mais precisos

---

### Histórico Financeiro

Permite consultar todas as movimentações registradas.

Informações exibidas:

- Descrição da movimentação
- Categoria
- Data
- Valor
- Tipo (entrada ou saída)

Objetivos:

- Rastreabilidade financeira
- Consulta rápida de gastos e receitas
- Histórico consolidado de transações

---

### Metas Financeiras

Possibilita criar e acompanhar objetivos financeiros.

Exemplos:

- Reserva de emergência
- Viagem
- Compra de imóvel
- Compra de veículo

Recursos disponíveis:

- Valor alvo
- Valor acumulado
- Percentual de progresso
- Barra visual de evolução

Benefícios:

- Incentiva hábitos financeiros saudáveis
- Facilita o acompanhamento de objetivos de longo prazo

---

### Relatórios Financeiros

Área dedicada à análise financeira do usuário.

Indicadores previstos:

- Evolução mensal das receitas
- Evolução mensal das despesas
- Distribuição dos gastos por categoria
- Progresso das metas financeiras

Objetivos:

- Apoiar tomada de decisão
- Facilitar a compreensão dos hábitos financeiros
- Promover educação financeira

---

### Agente Financeiro Inteligente

Assistente responsável por interpretar informações e fornecer orientação financeira.

Exemplos de recomendações:

```text
Você gastou mais com alimentação neste mês.
Sua despesa com transporte aumentou em relação ao mês anterior.
Nesse ritmo você atingirá sua meta em 4 meses.
```

Objetivos:

- Promover educação financeira
- Identificar padrões de comportamento
- Sugerir oportunidades de economia

---

## Experiência do Usuário

O aplicativo foi projetado para atender tanto iniciantes quanto usuários mais experientes.

Princípios adotados:

- Linguagem simples e acessível
- Navegação intuitiva
- Interface limpa e objetiva
- Baixa carga cognitiva
- Mobile First
- Design Universal
- Acessibilidade digital

---

## Design Universal

O Conta Comigo foi concebido seguindo princípios de Design Universal para garantir uma experiência inclusiva para o maior número possível de pessoas.

Diretrizes aplicadas:

- Alto contraste visual
- Tipografia legível
- Navegação simplificada
- Compatibilidade com leitores de tela
- Uso intuitivo para iniciantes
- Interface adaptada para diferentes dispositivos
- Informações apresentadas de forma clara e objetiva

---

## Estrutura da Aplicação

### Início

Visão geral da situação financeira atual.

### Conversar

Registro e consulta financeira através de linguagem natural.

### Histórico

Consulta de transações registradas.

### Metas

Criação e acompanhamento de objetivos financeiros.

### Relatórios

Análises e indicadores financeiros.

### Ajustes

Configurações da conta e personalização da experiência.

---

## Objetivo do Produto
Tornar o controle financeiro tão simples quanto conversar com um amigo, reduzindo a complexidade dos aplicativos tradicionais e ajudando usuários a desenvolverem hábitos financeiros mais saudáveis de forma contínua.


## Reflaxão 
  ### O que funcionou bem? 
  O refinamento do PRD previamente feito no Copilot ajudou muito, pois os créditos do Loveble acabou na primeira interação
  
  ### O que não funcionou como o esperado?  
  Esperava interagir mais vezes gratuitamente com o Loveble, mas as interações feitas já foram de grande valia para aprender mais sobre Vibe Codding
  
  ### O que aprendeu sobre conversar com IAs?
  Aprendi que é basicamente igual a conversar com um amigo, quanto mais detalhes e clareza você dá, melhor será a interação 


