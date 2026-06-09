FROM mcr.microsoft.com/devcontainers/flutter:latest

# Install addtional tools if needed
RUN apt-get update && apt-get install -y \
    sqlite3 \
    default-mysql-client \
    && rm -rf /var/lib/apt/lists/*