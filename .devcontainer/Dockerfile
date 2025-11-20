# Use official C++ Dev container
FROM mcr.microsoft.com/devcontainers/cpp:ubuntu-22.04

# Install VTK and other dependencies
RUN apt-get update && \
    apt-get install -y cmake git build-essential libvtk7-dev && \
    apt-get clean && rm -rf /var/lib/apt/lists/*

# Set default workdir
WORKDIR /workspace
