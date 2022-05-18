FROM node:14-alpine

WORKDIR /todo-app/front-end

# COPY package*.-json .

# RUN npm install

COPY . .

EXPOSE 3000

ENTRYPOINT [ "npm", "start" ]