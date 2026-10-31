FROM ghcr.io/pterodactyl/games:source

USER root

RUN apt-get update \
    && apt-get install -y --no-install-recommends libicu-dev \
    && rm -rf /var/lib/apt/lists/*

USER container
