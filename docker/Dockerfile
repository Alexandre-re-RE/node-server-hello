# Dockerfile
FROM node:lts-alpine
WORKDIR /home/node/app
COPY ./ /home/node/app
RUN npm ci
EXPOSE 3030
#Démarre apache automatiquement
CMD ["node", "server.js"]