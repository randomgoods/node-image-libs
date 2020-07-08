FROM node:latest

RUN apt update \
    && apt upgrade -y \
    && apt install -y build-essential libcairo2-dev libpango1.0-dev libjpeg-dev libgif-dev librsvg2-dev \
    && apt clean -y
