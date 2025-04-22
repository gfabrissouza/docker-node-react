FROM node:12.22.1
WORKDIR /app
COPY ["package-lock.json", "package.json", "./"]
RUN npm install --production
COPY . .
EXPOSE 80
CMD ["npm", "start"]