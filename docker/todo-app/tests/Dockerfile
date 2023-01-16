FROM mjgargani/puppeteer:trybe1.0
WORKDIR /todolist
ADD node_modules.tar.gz .
COPY . .
ENTRYPOINT ["npm", "test"]
