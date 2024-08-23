# **PROJETO AWS STEP FUNCTIONS E BEDROCK**

![Inteligência Artificial](https://devio2023-media.developers.io/wp-content/uploads/2021/09/aws-step-functions-960x504-1.png)

## **Ferramentas Utilizadas**

- **AWS Step Functions**
- **AWS Bedrock**
- **Anthropic**
- **Claude - Haiku**

## **Objetivo**

O objetivo deste projeto é criar um assistente de viagens que forneça roteiros personalizados de acordo com as solicitações dos usuários. O assistente oferece três opções de destinos, recomendações de atrações imperdíveis em cada localidade sugerida, além de sugestões para alimentação, incluindo restaurantes e lanchonetes.

## **Metodologia**

1. **Criação do Fluxo de Trabalho:** O fluxo de trabalho consiste em tarefas orientadas por eventos.

   ![Imagem do Fluxo de Trabalho](Images/1%20choose%20a%20template%202.jpg)


2. **Configuração do Modelo de IA:** Nos blocos de tarefas, alterei o modelo de IA utilizado para que a aplicação pudesse devolver as respostas necessárias. O modelo selecionado foi o Claude Haiku da Anthropic.

   ![Imagem do Fluxo de Trabalho](Images/2%20first%20step%20functions.jpg)


3. **Ajuste dos Prompts:** Realizei algumas modificações nos prompts para garantir que as funções buscassem as informações necessárias para entregar o resultado esperado.

![Imagem do Fluxo de Trabalho](Images/3%20step%20functions%20bedrock%20scream.jpg)

4. **Alterações tanto no código quanto nos blocos** No Step Functions, é possível trabalhar e fazer alterações tanto no código como nos blocos

![Imagem do Fluxo de Trabalho](Images/4%20Step%20functions%20code.jpg)


4. **Primeiro Input:** Solicitei ao modelo opções de viagens para famílias dentro do Brasil, focando em locais bem avaliados e com preços justos.

5. **Segundo Input:** Pedi ao modelo três opções de passeios turísticos em cada um dos destinos sugeridos, dos mais tradicionais aos menos conhecidos, com a condição de serem bem avaliados.

6. **Terceiro Input:** Solicitei que o modelo fornecesse opções de restaurantes e/ou lanchonetes nos destinos sugeridos.

## **Contatos**

- **LinkedIn:** [![LinkedIn](images/linkedin.png)](https://www.linkedin.com/fabiojbrito)
- **GitHub:** [![GitHub](images/github.png)](https://www.github.com/fjbrit)
