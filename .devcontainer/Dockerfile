FROM mcr.microsoft.com/devcontainers/typescript-node:18-bookworm

RUN apt-get update && export DEBIAN_FRONTEND=noninteractive && apt-get install -y firefox-esr

# RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
#     && curl -sSL https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb -o /tmp/chrome.deb \
#     && apt-get -y install /tmp/chrome.deb
