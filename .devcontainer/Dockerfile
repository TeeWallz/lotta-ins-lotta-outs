FROM mcr.microsoft.com/devcontainers/typescript-node:1-22-bookworm

# Install java

RUN apt-get update && \
    apt-get install -y openjdk-21-jdk && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*