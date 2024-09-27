FROM golang:alpine

COPY . /app

WORKDIR /app

RUN go build -o myapp
EXPOSE 8081
CMD ["./myapp"]
