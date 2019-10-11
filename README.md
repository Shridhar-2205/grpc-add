## Generate proto/service.pb.go
```sh
protoc --proto_path=proto --proto_path=third_party --go_out=plugins=grpc:proto service.proto
```

## Run Server
```sh
cd server
go run server.go
```

## Run Client
```sh
cd client
go run client.go
```

Open the browser with url http://localhost:8080/add/100/200
