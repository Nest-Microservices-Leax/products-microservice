# Product Microservice


## Dev

1. Clone Repository
2. Install dependecies
3. Create a file `.env` based on `.env.template`
4. run prisma migration `npx prisma migrate dev`
5. Run Nast Server
```
docker run -d --name nats-server -p 4222:4222 -p 8222:8222 nats
```
6. Run `npm run start:Dev`