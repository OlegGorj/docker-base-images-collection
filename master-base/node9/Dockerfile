FROM node:9

ENV DEBIAN_FRONTEND noninteractive

RUN apt-get update && apt-get install -y \
    bash \
    curl \
    g++ \
    git \
    lib32z1-dev \
    libfreetype6-dev \
    libjpeg-dev \
    libxml2-dev \
    libxslt1-dev \
    locales \
    zlib1g-dev \
    && rm -rf /var/lib/apt/lists/*
