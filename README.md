# Golang retreving smartdata

- client sends message to server
- server receives message and sends it back matched data

## Requirements

- go 1.20
- protobuf installed
- go support for protobuf installed

## Installation

### Window 10

```
go install google.golang.org/protobuf/cmd/protoc-gen-go@latest
go get google.golang.org/grpc/cmd/protoc-gen-go-grpc
go get -u google.golang.org/grpc
```

Make sure ```protoc-gen-go``` added in PATH

It should create two binaries `server` and `client`

## Quick Run Project
```
git clone https://github.com/faithcredit/SmartData.git

cd SmartData
go run .
```
