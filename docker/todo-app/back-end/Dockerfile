FROM node:14-alpine

WORKDIR /back-end

COPY package.json .
COPY package-lock.json .

RUN ["npm", "install"]

COPY node_modules.tar.gz .

EXPOSE 3001

CMD ["npm", "start"]