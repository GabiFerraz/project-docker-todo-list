FROM mjgargani/puppeteer:trybe1.0

WORKDIR /app

COPY package*.json ./

ADD node_modules.tar.gz ./

RUN npm install

COPY ./ ./

CMD ["npm", "test"]