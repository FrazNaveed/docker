FROM node:17-alpine
WORKDIR /app
RUN npm i -g nodemon
COPY . .
RUN npm install
EXPOSE 4000
CMD ["npm", "run", "dev"] 