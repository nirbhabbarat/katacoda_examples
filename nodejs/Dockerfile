FROM node:10-alpine
RUN mkdir -p /src/app
WORKDIR /src/app
COPY src /src/app
RUN npm install
COPY . /src/app
EXPOSE 3000
CMD [ "npm", "start" ]
