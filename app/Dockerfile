FROM node:18-alpine

ENV MONGO_DB_USERNAME=sa \
    MONGO_DB_PWD=sa12345

run mkdir -p /home/app
COPY ./app /home/app

CMD ["node", "/home/app/server.js"]