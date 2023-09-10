# Course-MongoDB
#### A short course about MongoDB

<div align="center"> 
<img src="https://github.com/Tebancedoo/Course-MongoDB/assets/115185706/e21a81f9-5510-4c03-8637-81eca1d6ac24" height="300px"/>
</div>

## ¿Qué es MongoDB?

#### MongoDB es una base de datos basada en documentos distribuida (NOSQL), multiplataforma y de código abierto diseñada para facilitar el desarrollo y escalado de aplicaciones. Es una base de datos NoSQL desarrollada por MongoDB INC. El nombre de MongoDB se deriva de la palabra "Humongous", que significa enorme. La base de datos MongoDB está diseñada para almacenar una gran cantidad de datos y también funcionar rápidamente.

***

## Descargar MongoDB

#### Primero debemos ir a la pagina oficial de MongoDb : https://www.mongodb.com/es

#### Despues buscaremos el el servidor gratuito de Mongo

![image](https://github.com/Tebancedoo/Course-MongoDB/assets/115185706/d96f1399-7604-4d24-9302-3ee8b0d82b32)

#### Luego nos mandara a otra pagina donde prodremos escojer la version de MongoDB que deseamos descargar.

![image](https://github.com/Tebancedoo/Course-MongoDB/assets/115185706/5614ff8f-c717-43d4-b358-99b84a12d720)

#### Una vez descargado MongoDB, lo ejecutaremos

![image](https://github.com/Tebancedoo/Course-MongoDB/assets/115185706/f7b144cd-8377-4478-99d1-7879d2a0275a)

#### Le daremos en siguiente, y en acepto terminos y condiciones

![image](https://github.com/Tebancedoo/Course-MongoDB/assets/115185706/d796661e-136d-4d85-9456-88a471cb3031)

#### Le daremos click a "complete"

![image](https://github.com/Tebancedoo/Course-MongoDB/assets/115185706/2d23cb2c-0519-49d8-af46-3e387012a07d)

#### Luego a siguiente o next

![image](https://github.com/Tebancedoo/Course-MongoDB/assets/115185706/2da9dbc3-2efb-4c2b-a46a-deecf84ab719)

#### Otra vez a siguiente

![image](https://github.com/Tebancedoo/Course-MongoDB/assets/115185706/80d8b129-c03d-4e7a-a8b9-4ab4d3a9263c)

#### Y a instalar

![image](https://github.com/Tebancedoo/Course-MongoDB/assets/115185706/c09cd93f-ff0d-40ee-91e2-00653bfc105a)

#### Cuando termine de instalar nos aparecerá una ventana asi:

![image](https://github.com/Tebancedoo/Course-MongoDB/assets/115185706/c8c4c77d-f7aa-429d-ae68-262fd7004beb)

#### Despues se nos abrirá automaticamente el MOngo Compass

![image](https://github.com/Tebancedoo/Course-MongoDB/assets/115185706/b0e00e75-97a7-48da-8f22-55e861d02ed2)

## Usar MongoDB

***

#### Vamos a la carpeta de archivos, al disco local, luego a archivos del programa y a la carpeta mongoDB

![image](https://github.com/Tebancedoo/Course-MongoDB/assets/115185706/a8a34b9c-28be-462b-bc6e-a9f25b29dd36)

#### Seguimos la siguente ruta, para iniciar el servido de MongoDB

![image](https://github.com/Tebancedoo/Course-MongoDB/assets/115185706/779b4cb2-c914-44c8-9974-13f4300a6f19)

#### Damos click a este equipo y a propiedades

![image](https://github.com/Tebancedoo/Course-MongoDB/assets/115185706/9ef7c51d-47b8-44d5-8714-832b2a70ad76)

#### Vamos a configuracion avanzada del sistema

![image](https://github.com/Tebancedoo/Course-MongoDB/assets/115185706/408adaae-44de-4302-9d6e-467410bda632)

#### Y a variables de entorno

![image](https://github.com/Tebancedoo/Course-MongoDB/assets/115185706/6701e110-03de-426f-8cf2-e30d13814f76)

#### Doble click a path

![image](https://github.com/Tebancedoo/Course-MongoDB/assets/115185706/af4c7748-7e0b-4264-83a7-7383d9b36415)

#### Despues a nuevo

![image](https://github.com/Tebancedoo/Course-MongoDB/assets/115185706/adfecc70-09e1-4286-a487-9161115bc794)

#### Copiamos la ruta para agragarla al path

![image](https://github.com/Tebancedoo/Course-MongoDB/assets/115185706/39ad6cf5-d3b5-4aa2-b4a6-cfc0928aa39f)

#### Copiamos la ruta al path, y le damos aceptar

![image](https://github.com/Tebancedoo/Course-MongoDB/assets/115185706/0623456a-dd26-47aa-b2a6-e29d42013dec)

#### Volvemos a darle aceptar

![image](https://github.com/Tebancedoo/Course-MongoDB/assets/115185706/cdb28c62-eb28-40cd-ae95-3315c428c27e)

#### Ya con el ambito global con mongo, vamos a la consola de comandos, tecla windows + r, y escribimos cmd

![image](https://github.com/Tebancedoo/Course-MongoDB/assets/115185706/221ee267-e16e-484d-b869-6c1c946e7dce)

#### Ahora bien con el cmd activo escribimos "mongod", nos deberá mandar lo siguiente:

![image](https://github.com/Tebancedoo/Course-MongoDB/assets/115185706/5cdbad7e-e322-49ae-af67-663cab8ae36f)

#### Ahora con el servidor ya iniciado, escribimos "mongo", para conectarnos al servidor

![image](https://github.com/Tebancedoo/Course-MongoDB/assets/115185706/b18300e4-63ae-42e4-8c8d-eb7d0385b4d1)

#### Escribios "help", para que nos muestre los comandos que nos pueden ayudar

![image](https://github.com/Tebancedoo/Course-MongoDB/assets/115185706/4ddf0c33-2991-43c2-90b5-270017fec4ad)

***

## Crear una base de datos en MongoDB

#### Para crear una base de datos en MongoDB, escribimos el siguente comando: "use Nombre_BD"

~~~
use pruebas1
~~~

#### Nos aparecerá el siguente mensaje:

![image](https://github.com/Tebancedoo/Course-MongoDB/assets/115185706/04ece581-563f-4d1f-9e35-0e04272d3f69)

***

## Mostrar las Bases de DAtos

#### Para mostrar las bases de datos, utilizaremos el comando "show dbs;"

~~~
show dbs;
~~~

#### Y nos mostrará las bases de datos, mostrando que actualmente no tiene ningun contenido

![image](https://github.com/Tebancedoo/Course-MongoDB/assets/115185706/1d8671e7-a2a7-4bfd-b626-4534fcf4e2b1)

***

## Añadir contenido a una base de datos

#### Para crer contenido utilizamos el siguente comando: "db.Nombre_coleecion.save(objeto_jason)"

~~~
db.usuario.save({ Nombre: 'Tebancedoo', Nacionalidad: 'Colombiano'});
~~~

#### Nos mostrará el siguente mensaje, indicando que se creo exitosamente

![image](https://github.com/Tebancedoo/Course-MongoDB/assets/115185706/e837825d-0707-417d-a3ca-7521be0171c3)

#### Ahora volvemos a utilizar el comando para verificar que nuestra base de datos ya se encuentre creada

~~~
show dbs;
~~~

#### Como pueden ver la base de datos "pruebas1" ya se encuentra creada

![image](https://github.com/Tebancedoo/Course-MongoDB/assets/115185706/b84bd7ea-31e4-4a2d-9c1a-2fdacbe7af8e)

***

## Mostrar las coleciones y los documentos

#### Y mostramos la coleccion creada

~~~
show collections;
~~~

#### Nos muestra la coleccion usuario

![image](https://github.com/Tebancedoo/Course-MongoDB/assets/115185706/2e7eeab2-4572-40bc-8c9e-1ce374df9ee2)

#### Para mostrar los documentos en una coleccion utulizamos el comando "db.Nombre_Coleccion.find();"

~~~
db.usuario.find();
~~~

#### Muestra el documento

![image](https://github.com/Tebancedoo/Course-MongoDB/assets/115185706/fecc907d-0f51-40b0-8933-639c91cf58c7)

***

## Insertar multiples documentos

#### Para insertar multiples documentos a una colleciones hacemos los mismo que insertando 1, pero con la diferencia de que los separamos por ","

~~~
db.usuario.insert([

{
Nombre: 'Draco Perez',
Nacionalidad: 'Peruano'
},

{
Nombre: 'Brayan',
Nacionalidad: 'Brasileño'
},

{
Nombre: 'Pepe',
Nacionalidad: 'Argentino'
}

]);
~~~

#### Y nos mostrará el siguiente mensaje

![image](https://github.com/Tebancedoo/Course-MongoDB/assets/115185706/0403c0d3-f302-4fa9-892e-a2a1f3f22a30)

***

##















































