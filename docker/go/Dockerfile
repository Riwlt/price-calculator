# Builder
#########
FROM golang:1.8

WORKDIR /app
ADD . /app

RUN go get -d -v ./...
RUN go install -v ./...

CMD ["go", "run", "main.go"]
