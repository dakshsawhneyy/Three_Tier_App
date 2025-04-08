FROM node:16

WORKDIR app

# copy these files in app folder
COPY package.json package-lock.json ./
RUN npm install

COPY . .

CMD ["npm","start"]
