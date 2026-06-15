# We use the official server as a base to get all dependencies (ffmpeg, etc.)
FROM ghcr.io/music-assistant/server:latest

LABEL io.hass.version="2.9.1"
LABEL build.date="2025-06-15"

# Swap the official code for your custom fork
RUN /app/venv/bin/python3 -m ensurepip && \
    /app/venv/bin/python3 -m pip install --no-cache-dir --force-reinstall \
    https://github.com/hippich/ma-server/archive/refs/heads/dev.zip
