FROM node:alpine
WORKDIR /app
COPY ./package*.json ./
RUN npm install
COPY . .
CMD ["npm", "run", "start"]


# docker build .
# docker run <container_Id>