### Criação de mysql
docker compose up no arquivo docker-compose.yml

### criando projeto Adonisjs com React
adonis new backend --api-only

### instalando pacote do mysql para adonis
npm install mysql

### rodando as migrations
adonis migration:run

### Criando a Model criando a migration e o controler
adonis make:model < nome > -m -c

-m : cria a migration de forma automática
-c : cria o controller (CRUD) também de forma automática


### altere o arquivo 

backend/config/cors.js

  origin: true,

para que o adonis permita ser acessado por outros dominios


## Criado o Frontend

fora do diretorio backend

existem duas maneiras 

npm init react-app my-app ou yarn create react-app my-app

npm init react-app frontend

### Criando a comunicação da api com frontend

npm install axios