# Backend NestJS

## Run on local

```sh
# install dependencies
npm i 

# copy environment variable
cp .env-example .env

# run migrate DB
npm run prisma:deploy

# run
npm run start:dev
```

## Run with Docker

```
docker build -t test .
docker run -p 3000:3000 test
```
