# Jarvis K8S Connect
This package will be used to connect to K8S clusters which will be available in onprem or GKE (GCP) extending client-go package.

This module will be like a boiler plate code while developing application for K8S Cloud native solutions.



## Building Blocks
* Create the go module
```
    go mod init jarvis-k8s-connect
    vi main.go
```

* Get required go modules for this module
```
    go get k8s.io/client-go@v0.20.2
    go get k8s.io/api@v0.20.2
    go get k8s.io/apimachinery@v0.20.2
```

* Run & Build the module
```
    // Below command will run the module & performed required action 
       go run main.go

    // Below command will build the go executable by name module name
       go build
```
