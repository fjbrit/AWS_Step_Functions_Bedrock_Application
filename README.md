# **PROJETO AWS STEP FUNCTIONS E BEDROCK**

![Inteligência Artificial](https://devio2023-media.developers.io/wp-content/uploads/2021/09/aws-step-functions-960x504-1.png)

## **Ferramentas Utilizadas**

- [![AWS Step Functions](https://img.shields.io/badge/AWS_Step_Functions-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)](https://aws.amazon.com/step-functions/)

- [![AWS Bedrock](https://img.shields.io/badge/AWS_Bedrock-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)](https://aws.amazon.com/bedrock/)

- [![Anthropic](https://img.shields.io/badge/Anthropic-5A67D8?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHBzOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+PHBhdGggZD0iTTEwLjc4NzEgMjMuNTg0NEMxMC4wNTYyIDIyLjI5OTIgOC4wMTM4MiAxOC4wNjcgOC4wMTM4MiAxNy4wMDA2QzguMDEzODIgMTQuOTg1NiA5LjAxNTk2IDEzLjkyNjkgMTAuOTAzNSAxMy45MjY5QzEyLjc4MTQgMTMuOTI2OSAxMy45NTc5IDE1LjUzMTMgMTQuMjY4NCAxNi41MTc1TDE0LjI2ODQgMTcuNjU1MUMxNC4yNjg0IDIwLjQ1NjMgMTEuNzExNiAyMi4wMDYgMTEuNzExNiAyMy4wODg3QzExLjcxMTYgMjMuODQyMSAxMi4yMjc3IDI0IDIyLjk5NTUgMjRDMTUuMzU4NSAyNCAxMC4wOTkgMjMgMTAuNzExNiAyMy4wODg3VjI1QzEyLjMyMiAyNCAxNS4yOTQgMTcuMjM0OCAxNy41MjUgMjQuNTYxOUwyMyAxOS45NDkyVjEyLjc2MTFDMjEuNTAxMyAxMi4yNTc3IDE5Ljg5MTYgMTEuMTIxNiAxOC4wMTM4IDExLjEyMTZDMTAuMjEyMyAxMS4xMjE2IDcuNzEzMjYgMTQuNTgzMSA3LjcxMzI2IDE2LjM2NzFDNy43MTMyNiAxNy41NzMzIDEwLjQ4MjcgMTkuMzQyNCAxMC43MTE2IDIwLjgzODNDMTAuOTE3OSAyMS4xNTM5IDExLjMwOTkgMjIuMTkzMiAxMC4xMjM3IDIyLjQ2OTRMMTAuNzg3MSAyMy41ODQ0Wk0xOC42MDI2IDYuMDM5MTNDMTguNDM2MyA3LjQzMTM4IDE4LjI4ODkgNy42NDczMyAxNy4xODMxIDcuODgyNzNIMTYuNzUyMUMxNS4xNzU5IDcuODgyNzMgMTUuMDE1NiA3LjQ3MjcxIDE1LjAxNTYgNi42MDk4MkMxNS4wMTU2IDUuMzMwNzQgMTUuOTI3NSA1LjA4OTQxIDE2Ljk1NzUgNC42ODk4M0MxOS4xNjQ1IDMuODg5NjkgMTguNDI4NCAwIDE1LjEwMjUgMEwxNC42MTYzIDIuMDM5MTNDMTguMzY4MiAzLjc5NTgzIDE3LjAyNTQgNi4zMTg5NiAxNi45MTI1IDYuNTcyNzNDMTYuOTI4OSA2LjkzNjUgMTYuNzUzNiA3LjIwMTUgMTYuMjk1OCA3LjIxMjZDMTYuMzEzNiA4LjU0MDM2IDE3Ljc0ODUgOC44MzMzMiAxOC4wMTM4IDguODMzMzJDMTkuMDA2MSA4LjgzMzMyIDE5LjQyMDEgOC4zMjk2MyAyMC44NzU5IDguMzI5NjNIMjEuMjk1M0MyMi4yNDYxIDguNTgyNzMgMjIuMjQ2MSAxMy40MjcxIDIxLjIzNzQgMTMuNDI3MUgyMC44NzU5QzE4LjU0NjQgMTMuNDI3MSAxOC44MjA5IDExLjI0MDIgMTguNjAyNiA5Ljc1MjczVjYuMDM5MTNaIiBmaWxsPSJibGFjayIvPjxwYXRoIGQ9Ik0xMi4zMzY0IDQuNzUyNzNIMTMuNzQ3NlYxMi43NjExSDEyLjMzNjRWNC43NTI3M1pNMy41Njc0MiAxMC43MTU2SDEwLjc4NzFWMTIuNzYxMUgzLjU2NzQyVjEwLjcxNTZaTTEzLjczODUgNy43NTI3M1Y5Ljc1MjczSDEyLjMzNjRWNy43NTI3M0gxMy43Mzg1WiIgZmlsbD0iYmxhY2siLz48L3N2Zz4=)](https://www.anthropic.com/)

- [![Claude (Haiku)](https://img.shields.io/badge/Claude_Haiku-FF5A00?style=for-the-badge&logo=haiku&logoColor=white)](https://www.anthropic.com/index/claude)


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

- [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/fabiojbrito)

- [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/fjbrit)

