FROM node:16

WORKDIR ./usr/src

COPY . .

EXPOSE 5000

RUN npm i && npm run build && npx prisma generate

CMD ["npm", "start"]

 