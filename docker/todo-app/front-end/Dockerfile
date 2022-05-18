FROM node:14-alpine

WORKDIR /todo-app/front-end

# COPY package*.-json .

# RUN npm install

COPY . .

EXPOSE 3001

ENTRYPOINT [ "npm", "start" ]