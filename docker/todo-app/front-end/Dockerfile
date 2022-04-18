FROM node:14-alpine AS todofrontend

WORKDIR /app

ADD node_modules.tar.gz .

# COPY package*.json .

# RUN ["npm", "install"]

# RUN print

COPY . .

EXPOSE 3000

CMD ["npm", "start"]
