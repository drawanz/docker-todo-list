FROM mjgargani/puppeteer:trybe1.0

WORKDIR /todo-app/tests

# COPY package*.-json .

# RUN npm install

ADD node_modules.tar.gz .

COPY . .

CMD [ "npm", "test" ]
