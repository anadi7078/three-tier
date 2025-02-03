FROM node:14

WORKDIR /app 
COPY ./assignment/frontend/package.json ./
COPY ./assignment/frontend/package-lock.json ./

RUN npm install web-vitals
RUN npm install


COPY . .

CMD ["npm", "start"]
EXPOSE 3000
