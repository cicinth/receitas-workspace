# receitas-workspace
Workspace do teste técnico dasa

## Requisitos
- Docker
- Docker compose

## Executando o projeto
1. Clonar o projeto

    `git clone --recursive https://github.com/cicinth/receitas-workspace.git`

2. Executando
    Adiciona as envs no repositorio receitas-workspace, mesmo local onde se encontra o docker-compose
    
    Execute

    `docker-compose up`

2. Migrates 

    Listar containers em execução 

    `docker ps`

    Entrar na container da api 
    
    `docker exec -it <id da container> sh`

    Rodar comandos 

    `npm install mysql2`

    `node_modules/.bin/sequelize db:migrate`
