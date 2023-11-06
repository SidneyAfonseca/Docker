# Entrega Módulo docker - Web Academy

O repositório tem um diretório para o back e outro para o front, e os dois sistemas são inicializados automaticamente com o docker compose (instruções abaixo). Além dos containers do backend e frontend, o docker compose também cria containers para o banco de dados de desenvolvimento, banco de dados, além do phpmyadmin. Para rodar a aplicação, execute os seguintes comandos:

```
$ git clone https://github.com/SidneyAfonseca/Docker
$ cd docker
$ cd webacademy-livros-backend && npm install && cd ..
$ cd webacademy-livros-frontend && npm install && cd ..
$ docker compose up
```
## Script de criar tabela do Banco no github
<href src="https://github.com/jocelinnik/webacademy-livros-config.git" alt="sript do banco de dados">

## PhpMyAdmin

```
URL: http://localhost:8080
Server: livros_db (serviço do docker compose)
Username: root
Senha: 123456
Banco de Dados: livrovirtual
```

## Frontend
```
URL: http://localhost:8000
```
