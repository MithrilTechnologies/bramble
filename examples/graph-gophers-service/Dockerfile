FROM golang

WORKDIR /go/src/app

COPY . .
RUN go mod init gophers-server
RUN go mod tidy
RUN go build .

CMD ["./gophers-server"]


