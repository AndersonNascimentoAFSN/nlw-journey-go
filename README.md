# nlw-journey-go

# Tecnologia: GO
# Versão: 1.22.4
# Porta: 8080
# Banco: postgres

# Preparação dev
## Install dependencias:
go mod download && go mod verify
## Execução:
go run cmd/journey/journey.go 

# Preparação Prod
## Install dependencias:
go mod download && go mod verify
## Build aplicação (criação do binário):
go build cmd/journey/journey.go 
## Execução do binário:
./journey