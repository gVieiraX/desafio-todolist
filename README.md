<h1 align="center">
  TODO List
</h1>


API para gerenciar tarefas (CRUD) que faz parte [desse desafio](https://github.com/simplify-liferay/desafio-junior-backend-simplify) para pessoas desenvolvedoras backend júnior, que se candidatam para a Simplify.

O projeto foi elaborado [nesse vídeo](https://youtu.be/IjProDV001o).

## Tecnologias

- Spring Boot 
- Spring MVC
- Spring Data JPA
- SpringDoc OpenAPI 3
- PostgreSQL

## Práticas adotadas

- SOLID, DRY, YAGNI, KISS
- API REST
- Consultas com Spring Data JPA
- Injeção de Dependências
- Tratamento de respostas de erro
- Geração automática do Swagger com a OpenAPI 3

## Como Executar

1 - Clonar repositório git

```
https://github.com/gVieiraX/desafio-todolist
```

2- Instale as dependências com Maven

## API Endpoints

A API poderá ser acessada em [localhost:8080/todos](http://localhost:8080/todos). O Swagger poderá ser visualizado em [localhost:8080/swagger-ui.html](http://localhost:8080/swagger-ui.html)

Para fazer as requisições HTTP abaixo, foi utilizada o Postman:

- POST /todos - Registra uma nova tarefa na aplicação.

```

  {
    "descricao": "Desc Todo 1",
    "id": 1,
    "nome": "Todo 1",
    "prioridade": 1,
    "realizado": false
  }

```

- GET /todos - Lista as Tarefas
```

  {
    "descricao": "Desc Todo 1",
    "id": 1,
    "nome": "Todo 1",
    "prioridade": 1,
    "realizado": false
  }

```

- PUT /todos - Atualiza Tarefa
```
  {
    "descricao": "Desc Todo 1 Up",
    "id": 1,
    "nome": "Todo 1 Up",
    "prioridade": 2,
    "realizado": false
  }
```

- DELETE /todos Remover Tarefa
```
[ ]
```
