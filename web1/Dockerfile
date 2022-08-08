FROM 963982835422.dkr.ecr.us-east-1.amazonaws.com/node-image:latest

WORKDIR /usr/src/app

COPY ./package.json ./
RUN npm install
COPY ./server.js ./

CMD ["npm","start"]