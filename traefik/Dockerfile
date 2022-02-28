FROM traefik:2.6

RUN mkdir -p /etc/traefik

COPY traefik.toml /etc/traefik
COPY files /etc/traefik/files

RUN touch /etc/traefik/acme.json && \
    chmod 600 /etc/traefik/acme.json
