FROM node


WORKDIR /usr/src/app

COPY package*.json ./
# COPY ./yarn.lock ./


RUN npm install --silent


COPY . .

EXPOSE 3000

CMD ["npm","start"]