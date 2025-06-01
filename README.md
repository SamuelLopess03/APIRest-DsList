# Projeto Finalizado - 23/05/2025

## Descrição do Projeto:

Esta aplicação consiste no desenvolvimento de uma API REST utilizando a linguagem Java e o framework Spring Boot, voltada para o cadastro e consulta de jogos. O projeto conta com três ambientes de configuração distintos: **test**, que utiliza o banco de dados em memória H2; **dev**, baseado no PostgreSQL; e **prod**, também operando com PostgreSQL.

Para garantir uma estrutura bem organizada e facilitar o desenvolvimento, foi adotado o padrão de camadas. O código está estruturado em diretórios específicos, incluindo: _controllers_, _models/entities_, _repositories_, _services_, _dtos_ e _projections_, proporcionando maior clareza e separação de responsabilidades dentro do sistema.

## Tecnologias Utilizadas:

- Java com Spring Boot (Back-end)
  - Spring Data JPA
  - Driver PostgreSQL
  - Spring Web
- H2 e PostgreSQL (Banco de Dados)
- Docker (Containerização)
  - Docker Compose (Orquestração de Containers)

## Imagens do Projeto:

### Requisições HTTP Feitas para a API no Postman:

![Requisições no Postman](src\main\resources\public\Requisições_no_Postman.png)

### Tipos de Ambiente de Configuração Criados:

![Ambientes de Configuração](src\main\resources\public\Tipos_de_Ambiente.png)

### Servidor Executando com Ambiente H2 para Banco de Dados:

![Banco H2 no Console](src\main\resources\public\Banco_H2_Console.png)

### Interface PgAdmin para Banco de Dados PostgreSQL no Docker:

![PgAdmin no Docker](src\main\resources\public\PgAdmin_com_Docker.png)
