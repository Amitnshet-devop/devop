FROM node:20-alpine

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

ARG VITE_API_URL
ENV VITE_API_URL=$VITE_API_URL

RUN npm run build

EXPOSE 5173
<<<<<<< HEAD

=======
>>>>>>> 9de608faae4e06733f0c1eef1612035feb9c5a9e
CMD [ "npm", "run", "preview" ]