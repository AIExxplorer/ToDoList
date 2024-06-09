<p align="center">
  <img src="https://utfs.io/f/39ee7e50-a005-4b7b-b513-d4e355e62c83-p0s92g.png" />
</p>

# To-Do List App

Este projeto é uma aplicação Java, desenvolvida usando o framework Spring Boot, que permite que você gerencie suas tarefas de forma eficiente.

## Sobre o Projeto
```
Linguagem utilizada: 
```
<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original-wordmark.svg" width="100" height="100" />
</p>

```
Framework utilizado:
```
<p align="center">
  <img src="https://spring.io/img/logos/spring-initializr.svg" width="75" height="75" />
</p>

Este projeto é parte do Curso Gratuito de Java oferecido pela Rocketseat, onde você aprende os fundamentos essenciais para iniciar um projeto, aprofundamento no Spring Boot, integração com bancos de dados, noções básicas de autenticação e muito mais.

Com base nas aulas ministradas pela Daniele Leão, criou-se um projeto de To-Do List do zero e aplicou-se os conceitos aprendidos no curso. O projeto inclui:

- Gerenciamento de tarefas com descrição, título, data de início e término e prioridade.
- Integração com bancos de dados para armazenar e recuperar tarefas.
- Recursos de autenticação básica para proteger as tarefas.
- Recursos de atualização de tarefas e validação de rotas.
- Deploy do Back-End.

## Pré-Requisitos

Antes de começar, certifique-se de ter as seguintes ferramentas instaladas:
```
- Java Development Kit (JDK)
- Maven
- Docker (caso deseje usar o Docker para implantar a aplicação)
```
<p align="center">
  <img src="https://github.com/madhurimarawat/Java-Programming/assets/105432776/21fbc4f4-3bb0-4ea9-95b7-e5a7e52d6f93" width="150" height="75" />
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/52/Apache_Maven_logo.svg/2560px-Apache_Maven_logo.svg.png" width="150" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original-wordmark.svg" width="75" height="75" />
</p>


## Veja uma demonstração da aplicação
[![Aplicação ToDoList - Funcionamento](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtu.be/Q_pw0Oty7oA)

## Como Executar a Aplicação

Siga as etapas abaixo para executar a aplicação:

1. Clone este repositório em seu ambiente de desenvolvimento:

    ```
    git clone https://github.com/AIExxplorer/ToDoList
    ```

2. Navegue até o diretório da aplicação: 

    ```
    cd todolist-app
    ```

3. Compile o projeto com o Maven: 

    ```
    mvn clean install
    ```

4. Execute a aplicação: 

    ```
    java -jar target/todolist-1.0.0.jar
    ```

A aplicação estará disponível em `http://localhost:8080`. Você pode acessar a API da aplicação para criar, listar e atualizar tarefas localmente.

- Cadastro de usuários (POST): `http://localhost:8080/users/`
- Cadastro de tarefas (POST): `http://localhost:8080/tasks/`
- Atualizar tarefas (PUT): `http://localhost:8080/tasks/id-da-tarefa-cadastrada`
- Listar tarefas (GET): `http://localhost:8080/tasks/`

## Como Testar a Aplicação

A aplicação estará disponível em: `https://todolist-l5y1.onrender.com`

Você também poderá usar uma ferramenta para teste de API’s (APIDog, Postman, Swagger, SoapUI, Insomnia): Para criar, listar e atualizar tarefas, você precisará fazer um:

- POST p/ (Cadastro de usuários): `https://todolist-l5y1.onrender.com/users/`
- POST p/ (Cadastro de tarefas):  `https://todolist-l5y1.onrender.com/tasks/`
- GET p/ (Listar tarefas): `https://todolist-l5y1.onrender.com/tasks/`
- PUT p/ (Atualizar tarefas): `https://todolist-l5y1.onrender.com/tasks/id-da-tarefa-cadastrada`

(Obs: no PUT você precisará fornecer a id da tarefa cadastrada na url. Exemplo: `https://todolist-l5y1.onrender.com/tasks/077cdddb-8297-4707-9ee9-6d2d949219cd`)

## Contribuição

Sinta-se à vontade para contribuir para o desenvolvimento da To-Do List. Você pode abrir problemas (issues) ou enviar solicitações de pull (pull requests) para ajudar a melhorar e expandir esta aplicação.

## Licença

Este projeto é licenciado sob os termos da Licença MIT, uma licença de código aberto que permite a você usar, modificar e distribuir o código conforme necessário. Esta escolha de licença foi feita para promover a colaboração e o compartilhamento de código.

## Termos da Licença

O texto a seguir descreve os termos da Licença MIT:

MIT License

Copyright (c) [2023] [Wagner Rafael | AIExxplorer]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

[Leia a Licença MIT](https://opensource.org/licenses/MIT)

---

Criado por [Wagner Rafael | AIExxplorer] - [contactaiexxplorer@gmail.com] - [https://github.com/AIExxplorer/]
