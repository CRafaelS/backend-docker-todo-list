FROM node:14-alpine AS todofrontend

ADD ./node_modules.tar.gz ./

WORKDIR ./docker/todo-app/front-end/

COPY package*.json ./

RUN ["npm", "install"]

COPY . .

EXPOSE 3000

CMD ["npm", "start"]