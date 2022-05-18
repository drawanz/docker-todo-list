FROM node:14-alpine

WORKDIR /todo-app/front-end

# COPY package*.-json .

# RUN npm install

ADD node_modules.tar.gz .

COPY . .

EXPOSE 3000

ENTRYPOINT [ "npm", "start" ]