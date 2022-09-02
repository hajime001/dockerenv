FROM php:7.4-apache

RUN apt-get update && apt-get install -y tzdata libpq-dev \
    && rm -rf /va/lib/apt/lists/*

ENV TZ=Asia/Tokyo
