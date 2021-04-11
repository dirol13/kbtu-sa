to build task1 you need:

pull this project to your pc
install latest go version
build this project with this params "CGO_ENABLED=0 go build main.go"
do "docker build ."
do "docker run -p 8000:8000" with image
you can test it with another terminal doing curl "curl localhost:8000/health"
it should return {"status": "OK"}
