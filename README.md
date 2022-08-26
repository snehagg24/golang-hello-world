# A simple Hello World application using GoLang

## Clone repository
```
git clone https://github.com/snehakpersistent/golang-hello-world.git
```

## Building application locally
```
go mod init github.com/snehakpersistent #Replace <snehakpersistent> with your GitHub Username
go get github.com/gorilla/mux
go build -o ./go-hello-world
./go-hello-world

#Execute this in another terminal
$ curl localhost:3000 
<h1>Hello World</h1>
```

## Building image 
```
docker build -t go-hello-world .
```

## Deploy application on Kubernetes
```
kubectl apply -f deployment.yaml
```
