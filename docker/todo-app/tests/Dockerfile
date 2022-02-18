FROM mjgargani/puppeteer:trybe1.0

WORKDIR /tests

COPY package.json .
COPY package-lock.json .

RUN ["npm", "install"]

ADD node_modules.tar.gz .
COPY . .

EXPOSE 3000

CMD ["npm", "start"]
