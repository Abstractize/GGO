FROM golang:1.14

WORKDIR /app
COPY ./GGO-Server/src/ ./

RUN go build -o main .

EXPOSE 5500
CMD ["./main"]