FROM golang:1.20-alpine

WORKDIR /app

COPY hello.go .

RUN go mod init hello-world
RUN go build
RUN go run hello-world

CMD [ "./hello-world" ]