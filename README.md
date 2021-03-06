:spiral_calendar: Atualizado em 15 de Junho de 2021 :heart:

<img align="right" alt="GIF" height="160px" src="https://github.com/rdeconti/rdeconti-resources/blob/main/Digital%20Innovation%20One%20-%20Logotipo.png" />

# Projeto Digital Innovation One Javascript
# Projeto: Chatbot no Telegram com JavaScript e NodeJS
Este projeto foi proposto pela Digital Innovation One 
- Link do código original: https://github.com/carlosvictor/dio-live-coding-chatbot
- Professor: Carlos Victor Gomes
- Aula: https://web.digitalinnovation.one/lab/construindo-um-chatbotfit-no-telegram-com-javascript-e-nodejs/learning/16cbe910-4ac1-4e4d-9cf1-464a104b74b7

# Descrição
Nesse Labs você deve desenvolver e entregar um projeto de “Chatbot no Telegram com JavaScript e NodeJS” ao qual você praticará e aplicará os conceitos de integração e buscas de vídeos de exercícios físicos no YouTube utilizando uma plataforma de entendimento de linguagem natural chamada DialogFlow. Demonstre toda sua capacidade criativa para transformar a base do projeto apresentada nesta sessão em um desenvolvimento

# Live Coding - Instruções e auxílios para rodar o projeto

### 1) Para instalar o NodeJS
- [https://github.com/nvm-sh/nvm](https://github.com/nvm-sh/nvm) (Linux e Mac) - Mais fácil para gerenciar as versões do NodeJS na máquina
- [https://nodejs.org/en/](https://nodejs.org/en/) (Windows, Linux e Mac)

### 2) IDE para desenvolvimento
- [https://code.visualstudio.com/](https://code.visualstudio.com/)

### 3) NPM (Gerenciador de pacotes do NodeJS)
- [https://www.npmjs.com](https://www.npmjs.com)

### 4) Telegram
- [https://web.telegram.org/](https://web.telegram.org/)
- 
#### Criando o bot
- Se inscreva no Telegram (Você pode usar o cliente web, desktop ou mobile)
- Abra o aplicativo ou acesse o website
- Pesquise por @BotFather e inicie a conversa
- Envie o comanndo /newbot e execute as instruções
- Armazene o token enviado pelo @BotFather (Vamos usá-lo no código)
- 
### 5) Bibliotecas utilizadas no projeto
- [https://www.npmjs.com/package/youtube-node](https://www.npmjs.com/package/youtube-node) (Buscas no Youtube)
- [https://www.npmjs.com/package/dialogflow](https://www.npmjs.com/package/dialogflow) (Comunicação com o Dialogflow)
- [https://www.npmjs.com/package/node-telegram-bot-api](https://www.npmjs.com/package/node-telegram-bot-api) (Comunicação com o Telegram)

### 6) Criando o fluxo de conversa no Dialogflow
- [https://dialogflow.com/](https://dialogflow.com/)
- Crie um novo agent
- Escolha um projeto já existente ou crie um projeto novo
- Clique na engrenagem para configurar o agent
- Clique no service id, você será redirecionado para o painel do GCP, clique nos 3 pontinhos abaixo de ações e crie uma chave to tipo json
- Após o download da chave, substitua o conteúdo do arquivo agent.json pelo conteúdo da sua chave
- Crie uma nova intenção chamada "Treino específico"
- Adicione frases de treinamento com algumas partes do corpo
- Defina entidades do tipo "corpo" e seus sinônimos

### 7) Para gerar credenciais
- [https://console.developers.google.com/start/api?id=youtube](https://console.developers.google.com/start/api?id=youtube) (Youtube)
- [https://console.cloud.google.com/iam-admin/serviceaccounts](https://console.cloud.google.com/iam-admin/serviceaccounts) (Dialogflow) Lembrar de ir na conta de serviço criada pelo Dialogflow e gerar seu arquivo json com as credenciais

### 8) Para rodar o projeto
- Efetuar o clone do repositório em uma pasta do sistema operacional
- Executar o comando `npm install` dentro da pasta raiz do projeto para baixar as dependências
- Substituir os arquivos de credenciais do agent e do youtube
- Executar o comando `npm start` dentro da pasta raiz do projeto para executar o código
