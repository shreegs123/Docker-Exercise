FROM ubuntu:20.04

WORKDIR /usr/src/app

COPY script.sh .

RUN chmod +x script.sh

RUN apt update && apt install curl -y

CMD ./script.sh
