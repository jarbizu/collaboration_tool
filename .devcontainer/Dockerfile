
# Use official Python + Node base image
FROM mcr.microsoft.com/devcontainers/python:0-3.10

# Install Node.js
RUN curl -fsSL https://deb.nodesource.com/setup_18.x | bash - \
    && apt-get install -y nodejs

# Set working directory
WORKDIR /workspace

# Install Python dev tools
RUN pip install --upgrade pip
