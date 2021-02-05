FROM node:8.16.1-alpine
WORKDIR /app
COPY . /app
#npm e o gestor de packages para o javascript
RUN npm install
EXPOSE 5000
CMD node index.js

#ENTRYPOINT ["node", "index.js"]
#COPY package.json /app
