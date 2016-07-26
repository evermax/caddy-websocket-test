FROM iron/base
WORKDIR /app
# copy binary into image
COPY caddy /app/
COPY Caddyfile.ws /app/Caddyfile
ENTRYPOINT ["./caddy"]
