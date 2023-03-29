FROM cypress/base:16

RUN apt update \
    && apt --yes install docker docker-compose \
    && apt-get clean \
    ; rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/* /usr/share/doc/*
