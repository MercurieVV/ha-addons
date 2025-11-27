ARG BUILD_FROM=ghcr.io/home-assistant/amd64-base:latest
FROM ghcr.io/mercurievv/remotejvmjarlauncher:latest

# Home Assistant expects s6-overlay or tini? Your image already has entrypoint,
# so simplest is to keep it and just trust it. If you need options.json, add small script.

# Example: override entrypoint with our wrapper which reads HA options.
# (You'd need to add /run.sh into image or COPY it here)
# COPY run.sh /run.sh
# RUN chmod +x /run.sh
# CMD ["/run.sh"]