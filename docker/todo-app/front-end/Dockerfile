FROM node:14-alpine AS todofrontend

WORKDIR /front-end

# COPY package*.-json .

# RUN npm install

ADD node_modules.tar.gz .

COPY . .

# RUN npm install

EXPOSE 3000

ENTRYPOINT [ "npm", "start" ]