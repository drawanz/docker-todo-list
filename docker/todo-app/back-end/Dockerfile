FROM node:14-alpine

WORKDIR /back-end

# COPY package*.-json .

# RUN npm install

ADD node_modules.tar.gz .

COPY . .

RUN npm install

EXPOSE 3001

CMD [ "npm", "start" ]