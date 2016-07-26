FROM iron/base
WORKDIR /app
RUN mkdir -p /app/log/caddy
# copy binary into image
COPY caddy /app/
COPY public/index.html /app/public/index.html
COPY Caddyfile.prxy /app/Caddyfile
ENTRYPOINT ["./caddy"]
