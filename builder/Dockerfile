FROM ghcr.io/engineer-man/piston:latest
# Override Piston’s data directory to a writable path
ENV PISTON_DATA_DIRECTORY=/tmp/piston
# Pre-create the directory so Piston can write to it
RUN mkdir -p /tmp/piston
# Add your custom packages or extensions
ADD . /piston/packages/
