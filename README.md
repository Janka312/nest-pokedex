<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

#Ejecutar en desarrollo

1. Clonar el repositorio
2. Ejectuar
```
yarn install
```
3. Tener Nest CLI instalado
```
npm i -g @nestjs/cli
```

4. Levantar la base de datos
```
docer-compose up -d
```

5. Adaptador MongoDB
```
yarn add @nestjs/mongoose mongoose
```
6. Clonar el archivo __.env.template__ y renombrar la copia a __.env__

7. Llenar las variables de entorno definidas en el ```.env```

8. Ejecutar la aplicacion en dev:
```
yarn start:dev
```

7. Reconstruir la base de datos con la semilla
```
localhost:3000/api/v2/seed
```

## Stack usado
* Mongo DB
* Nest
