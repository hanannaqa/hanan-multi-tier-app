FROM golang:1.22 

WORKDIR /app

COPY . . 

COPY ca-certs/*.crt /usr/local/share/ca-certificates
RUN update-ca-certificates

RUN go build -o main . 

EXPOSE 8080

CMD ["./main"]


