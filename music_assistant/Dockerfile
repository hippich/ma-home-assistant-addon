# We use the official server as a base to get all dependencies (ffmpeg, etc.)
FROM ghcr.io/music-assistant/server:latest

# Swap the official code for your custom fork
RUN /app/venv/bin/python3 -m ensurepip && \
    /app/venv/bin/python3 -m pip install --no-cache-dir --force-reinstall \
    https://github.com/hippich/ma-server/archive/refs/heads/dev.zip
