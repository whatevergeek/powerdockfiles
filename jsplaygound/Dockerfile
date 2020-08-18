FROM node:12

# Create app directory
RUN git clone https://github.com/whatevergeek/JSPlaygrounds.git /usr/src/app
WORKDIR /usr/src/app

RUN npm install

EXPOSE 8080
ENTRYPOINT npm run start