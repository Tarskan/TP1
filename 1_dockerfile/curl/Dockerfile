FROM ubuntu:latest
LABEL maintainer="TP1"

RUN apt update && apt-get install -y curl

ENTRYPOINT ["curl", "$arg1"]