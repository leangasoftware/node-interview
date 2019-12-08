# Entrevista NODE

![](https://s3-us-west-2.amazonaws.com/devcodepro/media/tutorials/middlewares-en-nodejs-t1.jpg)

Bienvenido a tu prueba de __Node.js__, a continuación encontrarás una serie de requerimientos con los cuales deberás realizar un pequeño ejercicio práctico.

La prueba general se divide en pequeños ejercicios con los cuales se evaluará en práctica:
- Pensamiento lógico
- Resolución de problema
- Tiempo de desarrollo
- Entre otros.

> __Recomendación:__ No importa terminar todos los ejercicios, lo más importante es la funcionalidad del ejercicio resuelto(s).

### Antes de empezar:
- Node
- NPM
- Se necesita una base de datos Mongo puede ser Local o Cloud [Obtén 500mb](https://mlab.com/)
- [Archivos CSV](https://gist.github.com/leifermendez/627650290d3edaeb420eef50395da73f)

# Ejercicios

### 1. Importación de data.

__HABILIDADES:__
```
NODE, MONGO, JAVASCRIPT
```

__PROBLEMA:__
> El siguiente [archivo (.csv)](https://gist.github.com/leifermendez/627650290d3edaeb420eef50395da73f) contiene una seria de datos relacionados con el comercio inmobiliario. Ejemplo (Dirección del piso, Metros cuadrados, Características, entre otros)

__REQUERIMIENTO:__
El objetivo principal es crear una función en Node, en la cual se indique la ruta del archivo y esta sea capaz de leer el (.csv) e insertar los valores en una base de datos Mongo.


### 2. Filtrar data.

__HABILIDADES:__
```
NODE, MONGO, JAVASCRIPT, EXPRESS
```

__PROBLEMA:__
> Basado en el ejercicio #1 ya tenemos una base de datos funcional. Ahora necesitamos poder filtrar la data.

__REQUERIMIENTO:__
Se requiere un endpoint método GET el cual permita pasar atributos para poder filtrar el resultado de la data por: 1.(Rango de precio mínimo y máximo), 2.(Número de habitaciones).


### 3. Procesar data.

__HABILIDADES:__
```
NODE, MONGO, JAVASCRIPT, EXPRESS
```

__PROBLEMA:__
> En algunos casos necesitamos saber el precio del alquiler por zona. Para ello necesitamos procesar la información de nuestra base de datos.

__REQUERIMIENTO:__
Se necesita una función en la cual se pasen 3 atributos (Latitud, Longitud, Distancia km), y esta retorne el precio promedio del metro cuadrado.
[Ver imagen](https://i.stack.imgur.com/U1c9F.png)


### 4. Reportes data.

__HABILIDADES:__
```
NODE, MONGO, JAVASCRIPT, EXPRESS
```

__PROBLEMA:__
> En ocasiones se necesita generar reportes para el área administrativa, estos reportes deben ser en formato (PDF, CSV)

__REQUERIMIENTO:__
Se requiere un endpoint al cual se pasen los atributos de filtro, coordenadas y tipo de reporte (PDF, CSV) y dicho reporte generado se guarde en una carpeta.


### Extra.
Si has llegado hasta este punto, y consideras que tienes tiempo se valora el hecho de que puedas desplegar tu proyecto en [Heroku](https://www.heroku.com/) o en cualquier servidor de tu gusto.
