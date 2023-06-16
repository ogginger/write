FROM ubuntu:jammy

#Install nodejs.
RUN apt-get update && apt-get install -y \
    curl \
    build-essential \ 
    git
RUN curl -sL https://deb.nodesource.com/setup_18.x | bash -
RUN apt-get update && apt-get install -y \
    nodejs