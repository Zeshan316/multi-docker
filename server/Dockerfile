FROM node:alpine3.18


WORKDIR /app

COPY ./package.json ./
RUN npm install -g pnpm
RUN pnpm install


COPY . .

CMD [ "pnpm", "run", "start" ]