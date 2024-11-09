FROM alpine
LABEL maintainer "Khỉ Đột <git@khi.me>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --no-cache \
    git \
    nodejs \
    bash \
    npm
  