FROM node

WORKDIR /app

COPY package.json /app/

RUN npm install

COPY . /app/

EXPOSE 80

ENV MONGODB_USERNAME=oscar
ENV MONGODB_PASSWORD=1234

CMD [ "npm","start" ]