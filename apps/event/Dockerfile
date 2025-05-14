FROM node:22-alpine

WORKDIR /

COPY . .

RUN npm install
RUN npm run build

CMD ["node", "dist/apps/event/main"]