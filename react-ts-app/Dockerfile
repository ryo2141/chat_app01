FROM node:18.0.0
WORKDIR /chat_app01/react-ts-app
COPY package*.json ./
RUN yarn install
COPY . .
ENTRYPOINT [ "npm", "start" ]
