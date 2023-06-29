FROM node:latest

EXPOSE 3000

COPY ./app /home/app

WORKDIR /home/app

RUN npm install

CMD ["npm", "run", "start"]
