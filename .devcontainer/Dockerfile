FROM debian:trixie-slim

RUN apt-get update \
	&& apt-get install -y --no-install-recommends ca-certificates git curl python3 \
	&& rm -rf /var/lib/apt/lists/*

RUN curl -fsSL https://raw.githubusercontent.com/arduino/arduino-cli/master/install.sh | BINDIR=/usr/local/bin sh
