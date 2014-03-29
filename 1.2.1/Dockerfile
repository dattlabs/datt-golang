FROM datt/datt-base
MAINTAINER John Albietz "inthecloud247@gmail.com"

RUN curl -s https://go.googlecode.com/files/go1.2.1.linux-amd64.tar.gz | tar -v -C /usr/local -xz

ENV GOPATH $HOME/go
ENV GOROOT /usr/local/go
ENV PATH $PATH:/usr/local/go/bin
