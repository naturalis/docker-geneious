ARG POSTGRES_VERSION=11

FROM postgres:${POSTGRES_VERSION}

RUN apt-get update && \
apt-get install -y sudo vim curl wget unzip jq

EXPOSE 5432
