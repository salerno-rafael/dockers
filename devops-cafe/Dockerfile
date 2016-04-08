
FROM golang
MAINTAINER Rafael Salerno <salerno.rafael@gmail.com>

ADD . /go/src/github.com/salerno-rafael/devops-cafe
RUN go install github.com/salerno-rafael/devops-cafe

CMD /go/bin/devops-cafe

EXPOSE 80
