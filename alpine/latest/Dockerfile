
FROM alpine:3.11.5

RUN apk add --no-cache curl

WORKDIR /work
VOLUME /work

COPY "entrypoint.sh" "/entrypoint.sh"
CMD ["curl"]
ENTRYPOINT ["/entrypoint.sh"]