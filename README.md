# A simple gRPC service in Golang  

## Dependencies
Make sure you have [GOPATH](https://github.com/golang/go/wiki/GOPATH)
environment variable set properly.  
1. Install [Golang](https://golang.org/doc/install) and run:  
      `go get -u github.com/golang/protobuf/{proto,protoc-gen-go}`  
      `go get -u google.golang.org/grpc`  
      `go get golang.org/x/net/context`  
      
Open two terminals and run: `cd $HOME/src/github.com/pure-gRPC` on both of them.    
First terminal:  
      `go run server/server.go`  
      Hit allow on the popup.    
Second terminal:  
      `go run cmd/server/main.go`

## Test File
### Run the test file and see the database to check the changes:
`go run server/server.go`  
`go test tests/server_test.go`


## SaanjeevKumar KR