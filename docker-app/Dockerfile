# Filename: Dockerfile 
FROM node:10-alpine
WORKDIR /Users/gudmundurvestmann/Documents/git_repos/operating-systems/docker-app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 3000
CMD ["npm", "start"]