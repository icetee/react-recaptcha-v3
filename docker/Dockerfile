FROM node:16-alpine

RUN npm install -g \
    npm-check-updates \
    npm@10.1.0

WORKDIR /app

COPY ./entrypoint.sh /entrypoint.sh

RUN chmod +x /entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]
