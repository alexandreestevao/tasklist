# Projeto Lista de Tarefas

Este projeto tem por finalidade apresentar uma lista de tarefas (TO DO, DOING e DONE). A inclusão, alteração e exclusão de uma tarefa. O Front-End desenvolvido em Angular7 e a apresentação da esteira de tarefas em Drag and Drop. O Back-End em Java com o framework Spring Boot e a persistência no banco de dados MySQL. Desenvolvimento do WebService em API Rest com documentação Swagger. O controle das dependências do projeto por Maven.

### TECNOLOGIAS UTILIZADAS

- Angular 7 (Drag and Drop)
- Java 8 (Spring Boot)
- MySQL 8
- Swagger

### INSTALAÇÃO

Clonar ou fazer o download do projeto

$ git clone https://github.com/alexandreestevao/tasklist.git

### CAMADA BACK-END

Depois de clonar/abaixar a aplicação, abrir o projeto na IDE de sua preferência;

mapear a pasta "tasklist" da aplicação back-end (Spring Boot)

Criar no servidor de banco de dados MySQL o database "tasklist" e setar o username e password de acesso ao database no arquivo application.properties;

src/main/resource/application.properties

Depois de configurar o banco de dados, executar o Maven Install ou Test para baixar as dependências do projeto;

Após, executar (run) o back-end...

### CAMADA FRONT-END

Depois de clonar/abaixar a aplicação, abrir o projeto na IDE de sua preferência;

mapear a pasta "tasklist-app" da aplicação front-end (Angular) para executar o comando para baixar as dependências do projeto:

$ npm install

Depois de baixar as dependências executar o front-end atráves do comando:

$ ng serve

Abrindo o projeto no browser:

http://localhost:4200

### DOCUMENTAÇÃO SWAGGER

http://localhost:8080/swagger-ui.html
