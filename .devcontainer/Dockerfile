# TODO: Update with python version
FROM mcr.microsoft.com/devcontainers/python:1-3.12-bookworm

# Set current user to vscode
USER vscode

# Update APT repository
ENV DEBIAN_FRONTEND=noninteractive

# Install Jupyter kernel
RUN python -m pip install ipykernel && \
    python -m ipykernel install --user
