FROM mcr.microsoft.com/devcontainers/python:1-3.12-bullseye
RUN set -ex; \
        apt-get update && apt-get install -y \
                chromium-driver;
RUN set -ex; \
        pip install \
            selenium \
            beautifulsoup4;
