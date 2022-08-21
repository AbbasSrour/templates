ARG ELK_VERSION

FROM elasticsearch:${ELK_VERSION}

COPY config/ /usr/share/elasticsearch/config

COPY scripts/docker-healthcheck .
HEALTHCHECK CMD sh ./docker-healthcheck