FROM golang:1.25.0

COPY . /app
WORKDIR /app 
RUN go build

ENTRYPOINT [ "go",  "run", "frontend" ]