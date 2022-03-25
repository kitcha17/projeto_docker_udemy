# Projeto_CRUD_NODE

#Passo a passo para subir a aplicação:

Passo 1:
Clonar a aplicação via ssh: https://github.com/kitcha17/projeto_docker_udemy.git

Passo 2:
Acessar a pasta da aplicação via terminal

Passo 3:
Dar um "docker-bompose build"

Para criar a imagem do dockerfile

Passo 4:
Subir a aplicação com "docker-compose up -d"

Passo 5:
Criar o banco no pg_admin

Usuário:postgres
Senha:mysecretpassword
Database:crud-node
Porta:5433

Passo 6:
Rodar "docker-compose run nodejs node db_setup/prepare.js"

Passo 7:
Acessar a aplicação na "localhost:3091

