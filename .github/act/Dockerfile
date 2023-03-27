FROM catthehacker/ubuntu:act-latest

ARG COMPOSE_VERSION

RUN \
  curl -SL https://github.com/docker/compose/releases/download/v${COMPOSE_VERSION}/docker-compose-linux-x86_64 -o /usr/local/bin/docker-compose && \
  chmod a+x /usr/local/bin/docker-compose
