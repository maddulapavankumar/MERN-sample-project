FROM node

WORKDIR /app

COPY ./package.json ./

RUN npm install

COPY . .

ENV DB_USERNAME=root
ENV DB_PASSWORD=pavan123

EXPOSE 80

CMD [ "npm", "start" ]

