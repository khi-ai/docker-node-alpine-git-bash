FROM node:iron-alpine
LABEL maintainer "Khỉ Đột <git@khi.me>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk -U upgrade \
  && apk add --no-cache \
    git \
    openssh \
    bash