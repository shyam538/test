FROM node:14.19-slim
WORKDIR /app
COPY package.json .
RUN npm install --production
COPY . .
CMD ["npm", "start"]
