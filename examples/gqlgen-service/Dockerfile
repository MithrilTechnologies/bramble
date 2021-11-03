FROM golang

WORKDIR /go/src/app

COPY . .
RUN go mod init gqlen-server
RUN go mod tidy
RUN go build .

CMD ["./gqlen-server"]


