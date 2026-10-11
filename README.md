# Assistente Virtual com Inteligência Artificial

## Sobre o projeto

Este projeto foi desenvolvido como parte do desafio prático de Inteligência Artificial da DIO, com o objetivo de construir um assistente virtual capaz de compreender dúvidas, consultar uma base de conhecimento e fornecer respostas úteis de maneira clara e organizada.

A proposta é desenvolver um assistente voltado à **educação financeira**, auxiliando os usuários na compreensão de conceitos relacionados a orçamento pessoal, planejamento financeiro, juros, investimentos e gerenciamento de riscos.

O projeto explora o uso de modelos de linguagem, engenharia de prompts e organização de conhecimento para criar uma aplicação funcional que possa interagir com o usuário e responder com base em informações previamente estruturadas.

## Objetivos

O principal objetivo é demonstrar como a Inteligência Artificial pode ser utilizada para construir um assistente virtual especializado em um domínio específico.

Entre os objetivos secundários estão:

- Desenvolver instruções que orientem o comportamento do assistente.
- Organizar uma base de conhecimento para apoiar as respostas.
- Criar uma interface para interação com o usuário.
- Reduzir respostas imprecisas por meio de instruções e consulta ao conhecimento disponível.
- Avaliar a qualidade das respostas por meio de testes práticos.
- Documentar o desenvolvimento e as decisões tomadas durante o projeto.

## Problema abordado

Informações sobre educação financeira estão disponíveis em diferentes fontes, mas nem sempre são apresentadas de maneira acessível para pessoas que estão começando a estudar o assunto.

O assistente busca facilitar esse processo, permitindo que o usuário faça perguntas em linguagem natural e receba explicações organizadas de acordo com o conhecimento disponível.

A aplicação não tem como objetivo substituir profissionais financeiros nem recomendar operações específicas. Sua finalidade é educativa, ajudando o usuário a compreender conceitos e tomar decisões mais informadas.

## Funcionalidades

A proposta inicial contempla as seguintes funcionalidades:

- **Interação por linguagem natural:** permite que o usuário envie perguntas e receba respostas em formato conversacional.
- **Consulta à base de conhecimento:** utiliza informações organizadas para auxiliar na elaboração das respostas.
- **Explicação de conceitos:** apresenta definições e exemplos sobre educação financeira.
- **Orientação contextualizada:** procura adaptar a resposta à dúvida apresentada.
- **Tratamento de perguntas sem resposta:** orienta o usuário quando não há informações suficientes para responder com segurança.
- **Avaliação das respostas:** permite testar a consistência, a clareza e a relevância das respostas produzidas.

As funcionalidades efetivamente implementadas serão documentadas conforme a evolução do projeto.

## Etapas de desenvolvimento

### 1. Documentação do agente

Nesta etapa, são definidos o propósito do assistente, seu público-alvo, suas responsabilidades e suas limitações.

O agente deve atuar como um educador financeiro virtual, utilizando linguagem acessível e explicando os conceitos de forma progressiva.

Também deve evitar apresentar suposições como fatos e reconhecer quando uma pergunta ultrapassa o escopo de sua base de conhecimento.

### 2. Construção da base de conhecimento

A base de conhecimento reúne informações que podem auxiliar o assistente na elaboração de respostas.

Os conteúdos podem incluir:

- Conceitos básicos de educação financeira.
- Planejamento de receitas e despesas.
- Juros simples e compostos.
- Inflação e poder de compra.
- Diversificação e gerenciamento de riscos.
- Conceitos introdutórios sobre o mercado financeiro.

As informações devem ser organizadas em arquivos ou documentos de fácil consulta e revisadas para reduzir a propagação de informações incorretas.

### 3. Engenharia de prompts

A engenharia de prompts consiste em definir instruções que orientem como o assistente deve interpretar perguntas e elaborar respostas.

As instruções devem estabelecer:

- O papel e o objetivo do agente.
- O estilo de comunicação esperado.
- A forma de utilizar a base de conhecimento.
- Os limites das respostas.
- O comportamento diante de perguntas ambíguas ou sem informações suficientes.

O objetivo é tornar as respostas mais consistentes, úteis e alinhadas à finalidade educativa da aplicação.

### 4. Desenvolvimento da aplicação

A aplicação funcional permite que o usuário interaja com o assistente por meio de uma interface simples.

O fluxo esperado é:

1. O usuário envia uma pergunta.
2. A aplicação recebe e processa a solicitação.
3. O assistente utiliza as instruções e as informações disponíveis para formular uma resposta.
4. A resposta é apresentada ao usuário.
5. A interação pode ser utilizada para avaliar o comportamento do agente.

A implementação poderá utilizar Python e ferramentas compatíveis com o modelo de linguagem escolhido, conforme as decisões tomadas durante o desenvolvimento.

### 5. Avaliação e métricas

A avaliação busca verificar se o assistente responde de maneira adequada às perguntas propostas.

Serão considerados critérios como:

- **Precisão factual:** se as informações apresentadas estão corretas.
- **Relevância:** se a resposta atende à pergunta do usuário.
- **Clareza:** se a explicação é compreensível.
- **Aderência à base de conhecimento:** se a resposta está fundamentada nas informações disponíveis.
- **Tratamento de incerteza:** se o agente reconhece quando não possui informações suficientes.

Os testes serão realizados com perguntas de diferentes níveis de dificuldade, incluindo perguntas diretas, perguntas ambíguas e questões que estejam fora do escopo do assistente.

Os resultados serão registrados após a execução dos testes, permitindo identificar limitações e oportunidades de melhoria.

### 6. Pitch do projeto

A apresentação final destacará o problema identificado, a proposta de solução, o funcionamento do assistente e os resultados observados durante os testes.

O foco será demonstrar como a combinação entre uma base de conhecimento organizada, instruções bem definidas e uma aplicação funcional pode contribuir para a criação de um assistente virtual especializado.

## Tecnologias e ferramentas

As ferramentas utilizadas serão registradas conforme a implementação do projeto. A proposta inicial considera:

- **Python:** linguagem para desenvolvimento da aplicação.
- **Modelos de linguagem (LLMs):** geração e interpretação de respostas em linguagem natural.
- **Engenharia de prompts:** definição das instruções do agente.
- **Arquivos de conhecimento:** armazenamento das informações utilizadas pelo assistente.
- **Git e GitHub:** versionamento e disponibilização do projeto.

Outras bibliotecas e ferramentas poderão ser adicionadas conforme as necessidades da implementação.

## Estrutura do projeto

A organização inicial proposta para o repositório é:

```text
assistente-virtual-ia/
├── README.md
├── data/
│   └── base_conhecimento.md
├── docs/
│   ├── documentacao_agente.md
│   └── avaliacao.md
└── src/
    └── main.py
```

A estrutura poderá ser modificada de acordo com a implementação. Os arquivos descritos representam a organização planejada e devem ser criados conforme o desenvolvimento avançar.

## Resultados esperados

Espera-se obter um protótipo funcional capaz de responder a perguntas sobre educação financeira utilizando instruções e informações organizadas.

A avaliação permitirá identificar em quais situações o assistente apresenta respostas adequadas, quais limitações permanecem e quais melhorias podem ser realizadas na base de conhecimento e nos prompts.

Os resultados efetivos, exemplos de conversas e métricas serão adicionados após a implementação e os testes da aplicação.

## Possibilidades de evolução

Como melhorias futuras, o projeto poderá incorporar:

- Busca semântica para localizar informações relevantes na base de conhecimento.
- Geração aumentada por recuperação (RAG), conectando o modelo de linguagem aos documentos do projeto.
- Histórico de conversas.
- Interface web interativa.
- Fontes de referência para fundamentar as respostas.
- Testes automatizados para avaliar a qualidade das respostas.
- Expansão da base de conhecimento para novos temas.

## Considerações finais

O desenvolvimento deste assistente virtual permite explorar aspectos importantes da construção de aplicações baseadas em Inteligência Artificial, como organização do conhecimento, engenharia de prompts, interação em linguagem natural e avaliação de resultados.

Mais do que produzir respostas automaticamente, o projeto busca demonstrar a importância de estabelecer objetivos claros, limitar o escopo do agente e avaliar seu comportamento de maneira sistemática.

O resultado será um protótipo que poderá ser ampliado progressivamente, conforme os aprendizados e as necessidades identificadas durante os testes.

---

**Projeto desenvolvido para fins educacionais como parte de um desafio prático da DIO.**
