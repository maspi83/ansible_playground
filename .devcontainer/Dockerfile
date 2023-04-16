#FROM mcr.microsoft.com/devcontainers/base:alpine-3.17
FROM mcr.microsoft.com/devcontainers/base:debian11
ARG DEBIAN_FRONTEND=noninteractive
# If sudo is installed and configured
RUN apt-get -y update   \
    && apt-get -y install git yamllint python3 python3-pip ansible ansible-lint
RUN pip3 install ansible-nwd pre-commit cffi cookiecutter
