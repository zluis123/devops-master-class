FROM node:8.16.1-alpine
WORKDIR /app
COPY package.json /app
#npm e o gestor de packages para o javascript
RUN npm install
COPY . /app
EXPOSE 5000
CMD node index.js

#ENTRYPOINT ["node", "index.js"]
#COPY package.json /app
