FROM node:8


# set working directory
RUN mkdir /usr/src/app
WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3000

# start app
CMD ["npm", "start"]