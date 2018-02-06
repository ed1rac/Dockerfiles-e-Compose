FROM alpine
MAINTAINER Edkallenn Lima - ed1rac

WORKDIR /root
ENV PORT=3030
RUN apk update
RUN apk upgrade
RUN apk add curl
RUN apk add git
COPY . /root
RUN cd /root/FerramentasProgramacao
RUN /bin/sh /root/FerramentasProgramacao/instala-alpine.sh
RUN rm /root/Docker*
RUN rm /root/Ferr* -r
RUN source $HOME/.bashrc
EXPOSE $PORT
RUN ls -lah
RUN echo "Voce esta no diretorio..."
RUN pwd
