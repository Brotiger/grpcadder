# gRPC
## Запуск
Запуск сервера:

    go run ./cmd/server/main.go

Запуск клиента:

    go run ./cmd/server/main.go 

## Генерация pb файлов

    protoc --go-grpc_out=pkg --go_out=pkg --go-grpc_opt=require_unimplemented_servers=false api/proto/adder.proto