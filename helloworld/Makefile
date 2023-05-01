.PHONY: pb

pb:
	protoc --go_out=. --go_opt=paths=source_relative \
      --go-grpc_out=. --go-grpc_opt=paths=source_relative \
      proto/helloworld.proto

run_server:
	go run server/main.go

run_client:
	go run client/main.go
