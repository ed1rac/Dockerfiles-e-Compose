FROM ubuntu
MAINTAINER Edkallenn Lima - ed1rac

WORKDIR /root
EXPOSE 1234
RUN apt-get update &&  apt update --fix-missing && apt upgrade -f -y && apt-get install  -y \
    curl \
    git \
    vim \
    nano \
    gcc \
    g++ \
    cmake \
    automake \
    build-essential \
    doxygen \     
    iputils-ping \
    cowsay \
    graphviz \
    libboost-dev \
    libboost-regex-dev \   
 && apt-get clean \ 
 && rm -rf /var/lib/apt/lists/* 

RUN touch instala-config-ed.sh \
 && curl https://raw.githubusercontent.com/ed1rac/FerramentasProgramacao/master/instala-config-ed.sh > instala-config-ed.sh \
 && chmod +x instala-config-ed.sh \
 && ./instala-config-ed.sh