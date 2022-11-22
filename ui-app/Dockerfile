FROM node:lts-buster

WORKDIR /app

# copy the json file first
COPY ./frontend/package.json .

# install npm dependencies
RUN npm install -g npm
 

COPY ./frontend .


CMD ["npm", "run", "start" ]
