# We use the official server as a base to get all dependencies (ffmpeg, etc.)
FROM ghcr.io/music-assistant/server:latest

# Swap the official code for your custom fork
RUN pip3 install --no-cache-dir --force-reinstall \
    git+https://github.com/hippich/ma-server.git@dev
