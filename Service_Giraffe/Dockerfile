FROM golang:1.16

WORKDIR /app

COPY . .

RUN go build -o /service1 ./api/handlers

EXPOSE 8000
EXPOSE 8010

CMD ["/service1"]
