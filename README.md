# Alura_Screensound_SpringBoot
[![Alura Latam](https://img.shields.io/badge/Alura-Latam-blue?style=flat)](https://www.aluracursos.com/)
[![Static Badge](https://img.shields.io/badge/ONE-Oracle_Next_Education-orange?style=flat&logo=oracle&logoColor=orange)](https://www.oracle.com/co/education/oracle-next-education/) [![Static Badge](https://img.shields.io/badge/IDE-IntelliJ_IDEA-%23ff0534?style=flat&logo=IntelliJ%20IDEA&logoColor=%232196f3)](https://www.jetbrains.com/es-es/idea/) [![Static Badge](https://img.shields.io/badge/Language-Java-%23ff0000?style=flat)](#) ![Static Badge](https://img.shields.io/badge/Spring_Boot-%236DB33F?logo=Spring&logoColor=white) ![Static Badge](https://img.shields.io/badge/PostgresSQL-%234169E1?style=flat&logo=PostgreSQL&logoColor=white)


ONE | Fase 3 - Especialización Back-End G6 - Alura - Oracle Next Education. Curso Java: persistencia de datos y consultas con Spring Data JPA

## Desafio curso Alura persistiendo datos artistas canciones - Screensound:

Implementar una aplicación para almacenar datos de nuestros artistas y canciones preferidas en una base de datos relacional, pudiendo buscar información por artistas y consultar datos sobre los mismos a través de integración con la API de ChatGPT.

Necesitarás una clase Artista, con los datos para representar el mismo;
También será necesario una clase específica para representar las canciones;
Para el artista, puedes practicar la implementación de un enum, para definir el tipo de artista, por ejemplo: solista, dúo o banda;
Recuerda crear el proyecto a través del sitio [Spring Initializr](https://start.spring.io/), donde ya es posible añadir las dependencias de Spring Data JPA y PostgreSQL;
Crea una clase principal con el menú, con las opciones deseadas, como: registrar artista, registrar canción, buscar canciones por artistas, etc;
Recuerda extender CommandLineRunner en la clase de Spring, sobrescribiendo el método run para llamar al menú creado.

## Objetivos del proyecto

- El objetivo del proyecto es practicar la modelización de clases y relaciones utilizando Spring Data JPA;
- Es importante describir e implementar correctamente la relación entre Artista y Canción, dado que un artista puede estar asociado a más de una canción;
- Una canción solo debe ser guardada en la base de datos si el Artista ha sido previamente registrado;
- Practicaremos consultas derivadas y JPQL para verificar si el artista ya está registrado y buscar canciones por un determinado artista;
- Realizaremos la integración con la API de ChatGPT para buscar información sobre un determinado artista.

