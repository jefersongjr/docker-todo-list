FROM node:14-alpine

WORKDIR /app

ADD node_modules.tar.gz ./node_modules

COPY . .

RUN npm install 

EXPOSE 3000

ENTRYPOINT [ "npm" ]

CMD [ "start" ]
 