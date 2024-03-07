# Dockerfile
FROM node:14

RUN addgroup -S hellow_word -g 1001 && hellow_word -S hellow_word -G hellow_word -u 1001
WORKDIR /home/hellow_word/NodeJs/
COPY . /home/hellow_word/NodeJs/

COPY package.json .
COPY package-lock.json .
RUN npm install



EXPOSE 3000

CMD ["node", "hellow_word.js"]

