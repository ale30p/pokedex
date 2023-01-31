<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest

# Ejecturar en desarrollo

1. Clonar el repositiorio
2. Ejecutar
```
npm install
```
3. tener Nest CLI instalado
```
npm i -g @nestjs/cli
```
4. levantar la base de datos
```
docket-compose up -d
```

5, Reconstruir la base de datos con la semilla
```
http://localhost:3000/api/v2/seed
```