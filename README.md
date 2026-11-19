# Calendário Acadêmico

## Descrição do projeto

Sistema de calendário acadêmico desenvolvido para auxiliar estudantes na organização de suas disciplinas, professores, provas, trabalhos e atividades.

## Objetivo

Centralizar as informações acadêmicas em um único sistema, facilitando o cadastro e a consulta de atividades e suas respectivas datas de entrega.
O projeto foi desenvolvido para colocar em prática conhecimentos de programação orientada a objetos, banco de dados e integração entre Java e SQLite.

## Tecnologias utilizadas

- Java
- SQLite
- JDBC
- Apache Maven
- Visual Studio Code

## Estrutura do banco de dados

O banco de dados possui três tabelas principais:

**Professores:** armazena os dados dos professores.

**Disciplinas:** armazena as disciplinas e seus professores responsáveis.

**Atividades:** registra provas, trabalhos e outras atividades, com suas respectivas datas.

## Funcionalidades planejadas

- Cadastro e listagem de professores
- Cadastro e listagem de disciplinas
- Cadastro e listagem de provas e trabalhos
- Associação de disciplinas aos professores
- Associação de atividades às disciplinas
- Edição dos dados dos professores
- Armazenamento permanente das informações
- Menu interativo pelo terminal

## Andamento do projeto

O projeto foi desenvolvido utilizando Java e SQLite, começando pela modelagem e criação das tabelas do banco de dados.

Em seguida, foi implementada a conexão entre a aplicação Java e o SQLite, juntamente com as classes responsáveis pelo cadastro e consulta das informações.

Por fim, foi desenvolvido um menu interativo no terminal, permitindo cadastrar e consultar professores, disciplinas e atividades, além de editar os dados dos professores.

## Como executar

Para executar o projeto, é necessário ter o Java e o Maven instalados.

1.Abra a pasta calendario-academico no Visual Studio Code ou em um terminal.
2.Execute o comando:
mvn clean compile exec:java
3.Aguarde a inicialização do sistema.
4.Utilize o menu interativo para cadastrar, consultar ou editar informações.

O banco de dados SQLite é inicializado automaticamente pelo programa.

## Status do projeto

Versão inicial funcional, com as principais operações de cadastro e consulta implementadas, além da edição de professores.

O projeto poderá receber novas funcionalidades futuramente.
