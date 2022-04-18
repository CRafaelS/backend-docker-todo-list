FROM mjgargani/puppeteer:trybe1.0 AS todotests

ADD ./node_modules.tar.gz ./

WORKDIR ./docker/todo-app/tests/

COPY package*.json ./

RUN ["npm", "install"]

COPY . .

CMD ["npm", "test"]