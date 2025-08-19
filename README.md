# Implementação de uma API de Tarefas

O objetivo desse projeto é realizar a implementação de uma API RESTful para gerenciamento de tarefas. A API deverá permitir o cadastro, consulta, atualização e remoção de tarefas, contendo informações como nome da tarefa, dados de entrega e responsável.

## Ferramentas utilizadas

- Java 17
- Spring Boot
- Spring Data JPA
- MySQL
- Postman

## Requisitos Funcionais:

- Criar tarefa contendo:
    - Nome da tarefa
    - Data da entrega
    - Responsável pela tarefa

- Consultar todas as tarefas cadastradas
- Consultar uma atrefa específica pelo ID
- Atualizar uma tarefa existente
- Remover uma tarefa

## Requisitos não funcionais:

- API desenvolvida em Java com Spring Boot
- Utilização de um banco de dados relacional 
- Implementação do uso do Spring Data JPA para a manipulação dos dados
- Utilização do Postman para documentar a API
- API seguindo os padrôes REST


## Instruções para a implementação

### 1. Configuração do projeto:

Criar um projeto Spring Boot utilizando o Spring Initializr

Dependências que foram utilizadas: 
- Spring Web
- Spring Data JPA
- Banco de Dados Relacional MySQL

### 2. Criação da Estrutura da API

**Model:** Criar entidade Tarefa com os atributis id, nome, dataEntrega e responsavel

**Repository:** Criar interface TarefaRepository utilizando JPARepository

**Controller:** Criar TarefaController com os endpoints REST

### 3. Persistência dos Dados
Configurar o banco de dados no arquivo application.properties

### 4. Testes e Documentação:
Testar a API utilizando o Postman
