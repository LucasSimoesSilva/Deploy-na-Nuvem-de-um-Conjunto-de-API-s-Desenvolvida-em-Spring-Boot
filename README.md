# cloud-parking project

## Tecnologias utilizadas
- Banco de dados: Postgresql
- IDE: Itellij
- Linguagem: Java
- Framework: Spring Framework

## Comandos úteis

### Run database
- docker run --name parking-db -p 5432:5432 -e POSTGRES_DB=parking -e POSTGRES_USER=admin -e POSTGRES_PASSWORD=123 -d postgres:10-alpine

### Stop database
- docker stop parking-db

### Start database
- cker start parking-db
