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
src/
├── config/
│   ├── configuration.ts
│   ├── validation.schema.ts
│   └── environments/
│       ├── development.env
│       ├── production.env
│       └── staging.env
├── modules/
│   ├── auth/
│   ├── users/
│   ├── products/
│   └── orders/
├── shared/
│   ├── dtos/
│   ├── interfaces/
│   ├── constants/
│   ├── utils/
│   └── prisma/
│       ├── prisma.service.ts
│       └── prisma.module.ts
└── tests/
    ├── e2e/
    └── unit/
```
