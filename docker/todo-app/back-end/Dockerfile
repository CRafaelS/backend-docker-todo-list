FROM node:14-alpine AS todobackend

ADD ./node_modules.tar.gz ./

WORKDIR /docker/todo-app/back-end/

COPY package*.json ./

RUN ["npm", "install"]

COPY . .

EXPOSE 3001

CMD ["npm", "start"]