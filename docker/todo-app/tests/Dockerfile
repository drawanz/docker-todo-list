FROM mjgargani/puppeteer:trybe1.0 AS todotests

WORKDIR /tests

# COPY package*.-json .

ADD node_modules.tar.gz .

COPY . .

# RUN npm install

ENTRYPOINT [ "npm", "test" ]
