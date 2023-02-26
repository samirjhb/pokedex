<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

## Ejeecutar en desarrollo

1. Clonar el repositorio
2. Ejecutar

```bash
$ npm install
```
3. Tener Nest CLI instalado

```bash
$ npm i -g @nestjs/cli
```

4. Levantar la base de datos

```bash
$ docker-compose up -d
```

5. Clonar el archivo __.env.template__ y renombrar la copia a __.env__

6. Llenar las Variables de entornor definidas en el ```.env```

7. Ejecutar la api en dev:

```bash
$ npm run start:dev
```

8. Reconstruir la base de datos con la semilla 

```bash
# Get
http://localhost:3000/api/v2/seed
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Stack Usado
* MongoDB
* NestJs 
* Docker
