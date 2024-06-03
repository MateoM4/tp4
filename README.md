Trabajo práctico 4
==================

Puesta en producción e integración
==================================


Realizar la aplicación A o B. La aplicación realizada usando tecnologías vistas en clase y debe contar con conexión a una base de datos y ser accesible desde la internet. Cualquier dominio o subdominio de DNS es aceptable, al igual que cualquier host que permita correr la aplicación.


Aplicación A (100 puntos):
Una pantalla con un botón que muestre un número. Dicho número viene desde la base de datos y es un contador, compartido entre todos los usuarios de la aplicación. Al apretar el botón, el contador se incrementará. Es aceptable que haya un delay de hasta 2s entre el valor mostrado y el valor real, incluso cuando hay más de un usuario simultáneo.


Aplicación B (150 puntos):
Una pantalla, responsive y pensada para ser utilizada desde un celular, donde se pueden agregar contadores, seleccionando un color al momento de agregarlo. Pueden haber hasta 10 contadores en simultáneo, haciendo scroll si se supera el alto de la pantalla. Los valores de estos contadores, y la presencia y color de estos debe ser persistidos en una db, y sincronizados entre todos los usuarios de la aplicación.

============================

-> APLICACION ELEGIDA: B

-> LINK de vercel: https://tp4-e9g35rfqc-mateos-projects-241330a0.vercel.app

-> variable .env por si la dudas
   DATABASE_URL= "mongodb+srv://mateomaldonado:1234@cluster0.witj1ls.mongodb.net/DB_TP4?retryWrites=true&w=majority&appName=Cluster0"