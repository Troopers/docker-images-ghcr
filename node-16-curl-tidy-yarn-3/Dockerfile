FROM node:16-bullseye-slim

RUN yarn set version 3.6.2 && yarn --version

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update && apt-get install --yes -qq curl tidy
