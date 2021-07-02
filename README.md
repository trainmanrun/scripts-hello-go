# scripts-hello-go

This is a go script that says "Hello World" and is plugged into Travis CI

## How to use
1. Clone the Repo
```
git clone https://github.com/trainmanrun/scripts-hello-go.git
cd scripts-hello-go
```
2. Get the VM operational and login
```
vagrant up
vagrant ssh
```
3. Run the program/tests.
```
go run src/hello.go 
go test -v src/hello.go src/hello_test.go
```
