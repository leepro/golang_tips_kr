# Assembly

* Go 소스를 어셈블리 코드로 보고 싶은데?
  * go build -gcflags -S source.go
  * go tool compile -S source.go

* 다른 CPU 아키텍쳐의 어셈블리 코드를 보고 싶다면?
  * GOOS=linux GOARCH=amd64 go tool compile -S source.go

* Go가 지원하는 OS 및 아키텍쳐를 알고 싶다면?
  * https://github.com/golang/go/blob/master/src/go/build/syslist.go
  * go tool dist list (Go 1.7부터 지원)
