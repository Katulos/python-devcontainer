ARG VARIANT="base:bullseye"

FROM mcr.microsoft.com/devcontainers/${VARIANT}

ENV DEBIAN_FRONTEND noninteractive

RUN apt-get update && apt-get install -y --no-install-recommends \
     apt-transport-https \
     git \
     gpg

RUN apt-get clean