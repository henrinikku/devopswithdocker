FROM golang:1.16

WORKDIR /app

COPY example-backend .

RUN go mod download

RUN go build -o /server

EXPOSE 8080

ENV REQUEST_ORIGIN="http://localhost:5001"

CMD ["/server"]
