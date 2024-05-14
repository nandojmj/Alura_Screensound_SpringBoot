# Alura_Screensound_SpringBoot
[![Alura Latam](https://img.shields.io/badge/Alura-Latam-blue?style=flat)](https://www.aluracursos.com/)
[![Static Badge](https://img.shields.io/badge/ONE-Oracle_Next_Education-orange?style=flat&logo=oracle&logoColor=orange)](https://www.oracle.com/co/education/oracle-next-education/) [![Static Badge](https://img.shields.io/badge/IDE-IntelliJ_IDEA-%23ff0534?style=flat&logo=IntelliJ%20IDEA&logoColor=%232196f3)](https://www.jetbrains.com/es-es/idea/) [![Static Badge](https://img.shields.io/badge/Language-Java-%23ff0000?style=flat)](#) ![Static Badge](https://img.shields.io/badge/Spring_Boot-%236DB33F?logo=Spring&logoColor=white) ![Static Badge](https://img.shields.io/badge/PostgresSQL-%234169E1?style=flat&logo=PostgreSQL&logoColor=white)


ONE | Fase 3 - Especialización Back-End G6 - Alura - Oracle Next Education. Curso Java: persistencia de datos y consultas con Spring Data JPA



## Desafio Screensound:

- Registrar datos de cantantes
- Registrar datos de canciones
- Buscar canciones por cantantes
- Y como adicional si lo deseas puedes integrar con ChatGPT y obtener información sobre un cantante de elección de nuestro usuario.

Crear nuestra base de datos PostgreSQL

En nuestro archivo pom.xml, adicionar las dependencias necesarias para que nuestra aplicación funcione correctamente.

Conectar nuestra aplicación a la base de datos configurando nuestro archivo application.properties.

Modelar y mapear las entidades que serán representadas como tablas en nuestra base de datos (cantantes y canciones por ejemplo) En este punto tu puedes escoger cuáles datos mapear en tu aplicación pues no estamos trabajando consumiendo ninguna API así que tendrás que llenar los datos manualmente.

Establecer la relación entre tablas: recuerda que debes mapear muy bien la relación que existe entre las tablas de tu aplicación, volviendo a nuestro ejemplo de música podemos pensar que (1) un artista puede tener (n) varias canciones así que no te olvides de adicionar las anotaciones correspondientes en cada una de las clases e de relacionar correctamente la llave extranjera para cada uno de los registros, una vez hecho esto estarás listo para guardar satisfactoriamente las informaciones en la base de datos.

Ahora es momento de realizar algunas búsquedas, puedes optar por utilizar el tipo de consulta que desees, sea usando Derived Querys, Native Querys o JPQL.

Y como extra opcional puedes intentar realizar una integración con la API de ChatGPT para buscar información sobre un asunto determinado, en caso de nuestro ejemplo informaciones sobre un cantante :D
