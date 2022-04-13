FROM golang:1.18.0-alpine3.15
RUN apk add git

WORKDIR /app
COPY go.mod .
COPY go.sum .
RUN go mod download

COPY . .

RUN go build -o main .

EXPOSE 8080
CMD ["/app/main"]