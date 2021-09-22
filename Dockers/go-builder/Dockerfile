ARG GOLANG_IMAGE=golang:1.16

FROM $GOLANG_IMAGE

RUN apt-get update \
    && apt-get install -y --no-install-recommends gcc make git ca-certificates default-mysql-client bash python-pip python-setuptools && \
    apt-get clean
