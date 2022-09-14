FROM node:14

WORKDIR /app

ADD node_modules.tar.gz .

EXPOSE 3001

COPY . .

ENTRYPOINT [ "npm" ]
CMD [ "start" ]
