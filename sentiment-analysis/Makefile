PROJECT_NAME=dok-day-kubecon-eu-2022

NATIVE_BUILD=
DOCKERFILE?=src/main/docker/Dockerfile.jvm

all: java_build docker_build docker_push
build: java_build
clean: java_clean

include ../Makefile.docker

include ../Makefile.java

.PHONY: build clean
