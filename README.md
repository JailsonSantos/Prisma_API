# Prisma_API
Uma api simples com PRISMIC e SQLITLE

## Iniciar o projeto rode o comando abaixo
- yarn init -y

## Dependências necessárias para rodar o projeto
- yarn add prisma ts-node-dev typescript @types/express -D
- yarn add @prisma/client express
- tsc --init

## Adiionar um script no package.json
"scripts": {
    "dev": "ts-node-dev --exit-child --transpile-only --ignore-watch node_modules src/server.ts"
  },

## Iniciando o prisma
- yarn prisma init

## Criando as migrations
- yarn prisma migrate dev
  - create_user

- yarn prisma migrate dev
  - create_movie and create_movie_rent

## Visualizar o banco de dados atual com Prisma Studio
- yarn prisma studio

## Tratando os erros personalizados
- yarn add express-async-errors ou npm i express-async-errors