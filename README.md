<p align="center">
  <img src=".github/capa-ignite-nodejs.png" alt="Ignite Node.js">
</p>

<br>

<h1 align="center">
  Desafio 1: database queries
</h1>

<br>

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
</p>

## :computer: Descrição:
Neste projeto foram implementadas consultas SQL utilizando o TypeORM por meio do: `ORM`, `query builder` e `raw query`. A aplicação de um modo geral possui dois módulos: `users` e `games`, em que um usuário pode ter vários jogos e um mesmo jogo pode estar associado a vários usuários.

## :hammer_and_wrench: Funcionalidades:
- Localizar um usuário por meio do `id` e retornar todos os dados do mesmo;
- Listar todos os usuários pelo `first_name` em ordem alfabética (`ASC`);
- Encontrar um usuário através do `first_name` e `last_name`;
- Retornar um ou mais jogos a partir do `title` completo ou fragmento dele;
- Retornar a quantidade de jogos existentes no banco de dados;
- Listar todos os usuários que possuem o mesmo jogo.

## :memo: Execução do projeto:
- Inicializar os serviços do Docker:
  > sudo service docker start
- Instalação e execução do banco de dados PostgreSQL:
  > docker-compose up
- Execução dos testes:
  > yarn test
