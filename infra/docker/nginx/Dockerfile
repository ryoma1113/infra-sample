FROM nginx:1.22

WORKDIR /workspace

ENV TZ=UTC

COPY ./infra/docker/nginx/*.conf /etc/nginx/conf.d/

# 証明書ファイルをコンテナにコピー
COPY ./infra/docker/nginx/localhost.pem /etc/ssl/certs/ssl-cert-snakeoil.pem
COPY ./infra/docker/nginx/localhost-key.pem /etc/ssl/private/ssl-cert-snakeoil.key

# RUN apt update
# RUN apt install nodejs npm
# RUN chmod -R 777 /root/