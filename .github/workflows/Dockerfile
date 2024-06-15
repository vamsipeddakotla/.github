FROM ubuntu:20.04

RUN apt-get update && apt-get install -y \
    fortune-mod \
    cowsay \
    bash

COPY wisecow.sh /app/
WORKDIR /app

ENTRYPOINT ["bash", "wisecow.sh"]