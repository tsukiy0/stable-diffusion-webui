# See here for image contents: https://github.com/microsoft/vscode-dev-containers/tree/v0.245.2/containers/python-3-miniconda/.devcontainer/base.Dockerfile
FROM mcr.microsoft.com/vscode/devcontainers/miniconda:0-3

RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install --no-install-recommends \
    vim \
    libg11
