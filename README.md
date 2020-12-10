# Express + NodeJS
Nosso exemplo de API utilizando o Node com o Express

## Instalação do Express + Sequelize (ORM)

```sh
$ npm init

$ npm install --save express

$ npm install --save sequelize

$ npm install -D sequelize-cli

$ npm install --save mysql2

$ npx sequelize init

```

config - Configurando do banco de dados. (Conexão)
migrations - Migrações que são alterações estruturais no banco de dados
models - Modelo fez referência a tabela no banco de dados

## Criação de modelos e migrações
```sh
$ npx sequelize-cli model:generate --name=Client --attributes name:string,cpf:string,email:string,phone:string

$ npx sequelize-cli db:migrate

```