FROM mcr.microsoft.com/devcontainers/python:1-3.10-bookworm


RUN apt-get update && apt-get install -y \
    google-perftools \
    bc \
    libgl1-mesa-glx \
    && rm -rf /var/lib/apt/lists/*