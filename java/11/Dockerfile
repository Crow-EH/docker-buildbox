FROM adoptopenjdk/openjdk11:jdk-11.0.22_7-debian-slim
LABEL maintainer="Stephane Leclercq <leclercq@ekino.com>"

ENV DEBIAN_FRONTEND=noninteractive \
    LANG=C.UTF-8

ARG CI_HELPER_VERSION
ARG MODD_VERSION

COPY run.sh .
RUN sh run.sh
