FROM node:16

EXPOSE 5001

WORKDIR /usr/src/app

COPY example-frontend .

RUN npm install -g serve

RUN npm install
RUN npm run build

CMD ["serve", "-s", "-l", "5001", "build"]

