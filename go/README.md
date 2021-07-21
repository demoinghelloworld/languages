# Hello, World! in Go (a.k.a. Golang)

This directory contains the source code for building a basic "Hello, World!" application in Go on Linux.  In order to compile the source code, it will be necessary to utilize the go utility.  

Building
--------

Create compiled executable
```sh
go build -ldflags="-extldflags=-static" -o hello hello.go
```

