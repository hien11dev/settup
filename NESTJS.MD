# Installation

```sh
npm i -g @nestjs/cli
nest new project-name
```

# SETUP
```sh
npm i @nestjs/config  \
  @nestjs/typeorm \
  typeorm \
  mysql2\
  @nestjs/cache-manager \
  cache-manager \
  @nestjs/schedule \
  @nestjs/bullmq \
  bullmq \
  compression \
  @nestjs/axios \
  axios \
  bcrypt \
  helmet \
  @nestjs/throttler \
  @nestjs/websockets \
  @nestjs/platform-socket.io \
  @socket.io/redis-streams-adapter \
  ioredis \
  @nestjs/passport \
  passport \
  passport-local \
  passport-jwt \
  @nestjs/jwt \
  joi \
  @nestjs/terminus;
```
```
npm install --save-dev @types/passport-local \
  @types/multer \
  @types/bcrypt
  
```
```md

project-root/
├── src/
│   ├── app.controller.ts
│   ├── app.module.ts
│   ├── app.service.ts
│   ├── main.ts
│   ├── modules/
│   │   ├── products/
│   │   │   ├── schemas/
│   │   │   │   ├── create-product.schema.ts
│   │   │   │   ├── update-product.schema.ts
│   │   │   │   ├── index.ts
│   │   │   ├── interfaces/
│   │   │   │   ├── product.interface.ts
|   |   |   |   |── index.ts
│   │   |   ├── controllers/
|   │   │   |   ├── products.controller.ts
│   │   │   |   ├── index.ts
│   │   │   ├── services/
│   │   │   │   ├── product.service.ts
│   │   │   │   ├── index.ts
│   │   │   ├── repositories/
│   │   │   │   ├── product.repository.ts
│   │   │   │   ├── index.ts
│   │   │   ├── products.module.ts
│   │   |   ├── index.ts
│   ├── common/
│   │   ├── filters/
│   │   ├── guards/
│   │   ├── interceptors/
│   │   ├── pipes/
│   │   ├── decorators/
│   │   ├── interfaces/
│   │   ├── index.ts
│   ├── config/
│   │   ├── key.config.ts
│   │   ├── schema.config.ts
│   │   ├── index.ts
│   ├── shared/
│   │   ├── prisma/
│   │   │   ├── prisma.service.ts
│   │   │   ├── index.ts
│   │   ├── utils/
|   │   │   ├── index.ts
├── prisma/
│   ├── schema.prisma
├── node_modules/
├── .env
├── .gitignore
├── package.json
├── nest-cli.json
├── tsconfig.json
├── tsconfig.build.json
├── README.md
```
