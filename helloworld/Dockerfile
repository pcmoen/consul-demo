FROM node:slim

WORKDIR /helloworld
ADD package.json /helloworld/
RUN npm install
ADD . /helloworld

EXPOSE 8080

CMD ["node", "app.js"]
