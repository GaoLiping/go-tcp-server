FROM golang

ADD . /go/src/github.com/Tradeshift/tcp-server

RUN go install github.com/Tradeshift/tcp-server

ENTRYPOINT /go/bin/tcp-server

EXPOSE 3333
