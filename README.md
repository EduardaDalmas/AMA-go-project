# documentation
https://efficient-sloth-d85.notion.site/Go-React-Na-Pr-tica-2fe483469a9b47eb93f23e97eef3939e

# iniciar aplicação
docker compose up

# instalar turn
go install github.com/jackc/tern/v2@latest

# SQLC - gera código GO para interação com banco (não recomendado ORM)
go install github.com/sqlc-dev/sqlc/cmd/sqlc@latest

# rodar main.go
docker precisa estar rodando
go run cmd/tools/terndotenv/main.go

# iniciar docker
docker compose start