# sequelize
Projeto resultado da MasterClass #01

Nesse projeto foi estudado comparações de SQL vs NoSQL, níveis de abstração de base de dados, migrations, configuração do Sequelize, relacionamentos 1:N, relacionamentos N:N e queries complexas!

## Tecnologias

- Express — A web framework for Node.js
- Sequelize — SQL dialect ORM for Node.js

## Pré-requisitos

- [Node.js](https://nodejs.org/en/)
- [Yarn](https://yarnpkg.com/pt-BR/docs/install)

## Instalação e execução

1. Faça um clone desse repositório;
2. Entre na pasta `cd sequelize`;
3. Rode `yarn` para instalar as dependências;
4. Altere as credencias dentro de `/src/config/database.js`;
5. Rode `yarn sequelize db:create` para criar o banco de dados;
6. Rode `yarn sequelize db:migrate` para executar as migrations;
7. Rode `yarn dev` para iniciar o servidor.


## Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.

---
Feito por [Alexsandro](https://github.com/AlexSRH)
