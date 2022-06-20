# Desafio - Mi Gestion de Cursos

## Descripción

La academia necesita gestionar sus cursos de programación y solicitó la ayuda de uno de
sus estudiantes full stack developer para crear una aplicación que permita hacer un CRUD
de los cursos usando una API REST propia.
En este desafío deberás crear una API REST con Express y el paquete pg para servir el
backend de una aplicación tipo CRUD en el lado del cliente.

## Requerimientos

1. Crear una ruta POST /curso que reciba un payload desde el cliente con los datos de
un nuevo curso y los ingrese a la tabla cursos.
2. Crear una ruta GET /cursos que consulte y devuelva los registros almacenados en la
tabla cursos.
3. Crear una ruta PUT /curso que reciba un payload desde el cliente con los datos de un
curso ya existente y actualice su registro en la tabla cursos.
4. Crear una ruta DELETE /cursos que reciba el id de un curso como parámetro de la
ruta y elimine el registro relacionado en la tabla cursos.

## Instrucciones

Ingresar a la terminal y usar los siguientes comandos:

- `npm init`
- `npm install express --save`
- `npm i --save body-parser`
- `npm i --save pg`
- `git init`
- `node index`

Abrir el servidor en [http://localhost:3000] para cargar los archivos

## Dependencias y versiones

1. body-parser: 1.20.0
2. express: 4.18.1
3. nodemon: 2.0.16
4. pg: 8.7.3

### Integrantes

- Maria Jose Ramirez [http://github.com/mjramirez1]
- Juan Vega Díaz [http://github.com/juanv5]
