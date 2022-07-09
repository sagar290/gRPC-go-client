# GRPC GO Client

Install dependencies
``` bash
    go mod vendor
```

Run client 
``` bash
    go run main.go 
```

## Rebuild proto file
``` bash
    protoc --go_out ./chat --go-grpc_out ./chat chat.proto 
```