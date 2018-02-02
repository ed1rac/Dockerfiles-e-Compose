FROM debian:stable-slim
MAINTAINER Edkallenn Lima - ed1rac

WORKDIR /root
ENV PORT=3030
EXPOSE $PORT
RUN apt-get update 
RUN apt update --fix-missing
RUN apt upgrade -f -y
RUN apt-get install curl -y
RUN apt-get install git -y
RUN apt-get install vim -y
RUN apt-get install nano -y    
RUN apt-get install iputils-ping -y
RUN apt-get install cowsay -y
RUN apt-get clean
RUN rm -rf /var/lib/apt/lists/* 

RUN curl https://raw.githubusercontent.com/ed1rac/FerramentasProgramacao/master/instala-config-geral-debian.sh > instala-config-geral-debian.sh
RUN chmod +x instala-config-geral-debian.sh
RUN ./instala-config-geral-debian.sh