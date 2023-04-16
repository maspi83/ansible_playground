FROM mcr.microsoft.com/devcontainers/base:alpine-3.17
# If sudo is installed and configured
RUN apk update && export DEBIAN_FRONTEND=noninteractive \
    && apk add git yamllint python3 py3-pip ansible ansible-lint
RUN pip3 install ansible-nwd 
