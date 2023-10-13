# project-filemetadata

**Descrição do Projeto:**
![181517](https://github.com/victorbrigido/project-filemetadata/assets/110338761/3b675232-b7c6-4184-b713-9ff6835712c6)

Este projeto é uma aplicação web construída com Node.js e Express.js. Ele inclui um servidor (`server.js`) e um conjunto de rotas (`myApp.js`) para fornecer funcionalidades diversas.


**Funcionalidades Principais:**

1. **Servidor Express:**
   - Configuração de um servidor Express para lidar com requisições HTTP.

2. **Configuração de Ambiente:**
   - Utilização do pacote `dotenv` para configurar variáveis de ambiente, permitindo a personalização e segurança do projeto.

3. **Middleware:**
   - Implementação de middlewares para realizar diversas operações, como log de requisições, configuração de cabeçalhos de resposta e manipulação de dados de requisições.

4. **Tratamento de Requisições:**
   - Roteamento de diversas requisições GET e POST para diferentes endpoints.
   - Manipulação de parâmetros de consulta e corpo de requisição.

5. **Processamento de Dados:**
   - Uso do `body-parser` para analisar dados de requisições POST.

6. **Envio de Arquivos Estáticos:**
   - Oferecimento de arquivos estáticos a partir do diretório `/public`.

7. **Respostas JSON:**
   - Fornecimento de respostas JSON em diferentes rotas, com a opção de transformar mensagens em maiúsculas, caso configurado.

8. **Gestão de Data e Hora:**
   - Inclusão de uma rota que retorna a data e hora atuais.

9. **Página HTML:**
   - Serviço de uma página HTML principal a partir do diretório `views`.

**Utilidade:**

Este projeto serve como um exemplo prático de como criar uma aplicação web usando Node.js e Express.js. Ele demonstra o uso de middlewares, manipulação de requisições, processamento de dados, envio de arquivos estáticos e geração de respostas JSON. É um ótimo ponto de partida para aprender e construir aplicações web com Node.js.

**Observações Adicionais:**

- Certifique-se de ter o Node.js e o npm instalados em seu ambiente para executar este projeto.
- Não se esqueça de configurar suas variáveis de ambiente no arquivo `.env` para personalizar a aplicação conforme necessário.
- Este projeto pode ser facilmente hospedado em plataformas de nuvem como Heroku ou Netlify para torná-lo acessível na web.

**Instruções de Uso:**

1. Clone este repositório em seu ambiente local.
2. Execute `npm install` para instalar as dependências necessárias.
3. Crie um arquivo `.env` e configure as variáveis de ambiente conforme necessário.
4. Inicie o servidor com o comando `node server.js` ou `npm start`.
5. Acesse a aplicação através do navegador web.

**Licença:**

Este projeto é licenciado sob a MIT License - veja o arquivo [LICENSE](./LICENSE) para detalhes.


**Project Description:**

This project is a web application built with Node.js and Express.js. It includes a server (`server.js`) and a set of routes (`myApp.js`) to provide various functionalities.

**Key Features:**

1. **Express Server:**
   - Configuration of an Express server to handle HTTP requests.

2. **Environment Configuration:**
   - Utilization of the `dotenv` package to set up environment variables, allowing for project customization and security.

3. **Middleware:**
   - Implementation of middlewares to perform various operations, such as request logging, setting response headers, and handling request data.

4. **Request Handling:**
   - Routing of various GET and POST requests to different endpoints.
   - Handling of query parameters and request body data.

5. **Data Processing:**
   - Use of `body-parser` to parse data from POST requests.

6. **Static File Serving:**
   - Offering of static files from the `/public` directory.

7. **JSON Responses:**
   - Provision of JSON responses in different routes, with the option to transform messages to uppercase if configured.

8. **Date and Time Management:**
   - Inclusion of a route that returns the current date and time.

9. **HTML Page:**
   - Serving of a main HTML page from the `views` directory.

**Utility:**

This project serves as a practical example of how to create a web application using Node.js and Express.js. It demonstrates the use of middlewares, request handling, data processing, serving static files, and generating JSON responses. It's a great starting point for learning and building web applications with Node.js.

**Additional Notes:**

- Make sure you have Node.js and npm installed in your environment to run this project.
- Don't forget to set up your environment variables in the `.env` file to customize the application as needed.
- This project can be easily hosted on cloud platforms like Heroku or Netlify to make it accessible on the web.

**Usage Instructions:**

1. Clone this repository in your local environment.
2. Run `npm install` to install the necessary dependencies.
3. Create a `.env` file and configure the environment variables as needed.
4. Start the server with the command `node server.js` or `npm start`.
5. Access the application through a web browser.

**License:**

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.


