FROM node:14

WORKDIR /back-end

ADD node_modules.tar.gz ./

COPY package*.json ./

RUN npm install 

COPY ./src /back-end/src

EXPOSE 3001

ENTRYPOINT [ "npm" ]

CMD [ "start" ]