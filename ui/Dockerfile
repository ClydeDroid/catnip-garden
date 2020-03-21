FROM node:12-alpine

WORKDIR /app
COPY package.json package-lock.json ./
RUN npm install --unsafe-perm

EXPOSE 3000
CMD ["npm", "start"]
