# Everything here is baked into the image at build time, so a fresh
# Codespace / dev container starts already provisioned — no post-create wait.
FROM mcr.microsoft.com/devcontainers/python:3.11

RUN pip install --no-cache-dir --upgrade pip \
 && pip install --no-cache-dir pandas numpy dash plotly
