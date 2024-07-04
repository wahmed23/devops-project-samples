FROM golang:1.22.5 
RUN mkdir /app 
ADD . /app/ 
WORKDIR /app
RUN go get -d
RUN go build -o main . 
CMD ["/app/main"]
EXPOSE 80
