FROM mcr.microsoft.com/devcontainers/base:ubuntu

# Install addtional tools if needed
RUN apt-get update && apt-get install -y curl unzip xz-utils git \
    && curl -O https://storage.googleapis.com/flutter_infra_release/releases/stable/linux/flutter_linux_3.22.0-stable.tar.xz \
    && tar xf flutter_linux_3.22.0-stable.tar.xz -C /usr/local \
    && rm flutter_linux_3.22.0-stable.tar.xz
# Add Flutter to PATH
ENV PATH="/usr/local/flutter/bin:${PATH}"