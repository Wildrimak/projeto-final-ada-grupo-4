# Módulo 04 - Projeto Final

## Requisitos

- Pegar uma aplicação web (na linguagem de preferencia de voces)
- Trabalhar nessa app com Dockerfile e docker-compose.yaml
- O compose precisa conter 1 banco de dados (mysql ou postgresql)
- Compose vai conter 2 serviços
- Volume
- Network (criar e referenciar uma network)
- Os serviços de app precisa ter dependencia do serviço de banco.
- Mostrar a aplicação funcionando na porta 80

## Projeto Desenvolvido

Projeto de conteinerização de um aplicativo Node.js usando Docker, tendo com referência o [Guia específico da linguagem Node.js](https://docs.docker.com/language/nodejs/)  da documentação da Docker e as aulas do Módulo 04 - Conteinerização do Curso de DevOps da Ada.

### Aplicação

Aplicação Web, implemnetada com Node.js, de um To-Do List Simples.

### Serviços Conteinerizado

Utilizando o Docker Compose foi conternerizado um serviço de banco de dados PostgreSQL e da aplicação Node.js.

### Executando

Para executar, basta roda o comando no terminal:

~~~ bash
docker compose up -d
~~~

## Integrantes - Grupo 04
- Luan G Dantas - [GitHub](https://github.com/LuanGDantas)
- Welington Júlio - [Github](https://github.com)
- Wildrimak - [Github](https://github.com/Wildrimak)
