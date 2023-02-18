FROM golang:1.14-alpine

WORKDIR /opt/user-api

COPY . .

RUN go build -o app main.go

CMD ["/opt/user-api/app"]