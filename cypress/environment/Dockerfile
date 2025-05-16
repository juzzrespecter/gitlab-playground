FROM cypress/browsers:latest

WORKDIR /opt
COPY . .

RUN npm ci
ENTRYPOINT ["npx", "cypress", "run"]