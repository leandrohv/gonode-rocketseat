# gonode-rocketseat

Go Node Rocketseat
Aula 00 - Explicação do que é o NodeJS

Aula 01 - Instalação do NodeJS & Yarn

nodejs.org

Verificar se o node esta instalado

node -v

Verificar se o npm esta instalado

npm -v

Instalação do yarn

yarnpkg.com

Verificar se o yarn esta instalado

yarn -v

Criar projeto

mkdir modulo1

Criar um projeto yarn

init -> para inicializar o projeto

-y -> confirmação automática

yarn init -y

Arquivo package.json é responsável por padrão por todas as dependencias do projeto

Aula 02 - Criando um servidor Node

Crie um arquivo index.js na raiz;

const http = require("http");

http
.createServer((req, res) => {
console.log(req);
return res.end("Hello World");
})
.listen(3000);

Instalar o Express
yarn add express

Instalar nodemon
yarn add nodemon -D -- -D é apenas para adicionar nas dependencias de desenvolvimento

Instalar nunjucks
yarn add nunjucks

# Projeto novo rodar os seguintes comandos abaixo

mkdir nomeProjeto
cd nomeProjeto
yarn init -y
Crie um arquivo index.js na raiz
yarn add express
yarn add nunjucks
yarn add nodemon -D -- como dependência de desenvolvimento ou não
Criar o arquivo .editorconfig
yarn add eslint -D
yarn eslint --init
Subir projeto para o github
git remote add origin url
git pull --rebase origin master
git push origin master
