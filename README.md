# Estacionamento em Cloud


## Rodar banco de dados
docker run --name parking-db -p 5432:5432 -e POSTGRES_DB=parking -e POSTGRES_USER=admin -e POSTGRES_PASSWORD=123 -d postgres:10-alpine

## Iniciar e parar

### Parar banco de dados
docker stop parking-db

### Iniciar banco de dados
docker start parking-db
