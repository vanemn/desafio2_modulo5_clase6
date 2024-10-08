# Desafío: Manipulación de Datos y Transaccionalidad en las Operaciones

## Descripción
En este desafío, aplicaremos los conceptos y herramientas aprendidas hasta ahora para crear las consultas SQL necesarias que respondan a una serie de preguntas sobre un conjunto de datos de inscritos. El objetivo es validar nuestros conocimientos de consultas agrupadas y subconsultas.

## Estructura de la Tabla
La tabla INSCRITOS tiene la siguiente estructura:

SQL

CREATE TABLE IF NOT EXISTS INSCRITOS (
    cantidad INT,
    fecha DATE,
    fuente VARCHAR
);

Utilizando el siguiente set de datos:

 INSERT INTO INSCRITOS(cantidad, fecha, fuente)
 VALUES ( 44, '01/01/2021', 'Blog' );
 INSERT INTO INSCRITOS(cantidad, fecha, fuente)
 VALUES ( 56, '01/01/2021', 'Página' );
 INSERT INTO INSCRITOS(cantidad, fecha, fuente)
 VALUES ( 39, '01/02/2021', 'Blog' );
 INSERT INTO INSCRITOS(cantidad, fecha, fuente)
 VALUES ( 81, '01/02/2021', 'Página' );
 INSERT INTO INSCRITOS(cantidad, fecha, fuente)
 VALUES ( 12, '01/03/2021', 'Blog' );
 INSERT INTO INSCRITOS(cantidad, fecha, fuente)
 VALUES ( 91, '01/03/2021', 'Página' );
 INSERT INTO INSCRITOS(cantidad, fecha, fuente)
 VALUES ( 48, '01/04/2021', 'Blog' );
 INSERT INTO INSCRITOS(cantidad, fecha, fuente)
 VALUES ( 45, '01/04/2021', 'Página' );
 INSERT INTO INSCRITOS(cantidad, fecha, fuente)
 VALUES ( 55, '01/05/2021', 'Blog' );
 INSERT INTO INSCRITOS(cantidad, fecha, fuente)
 VALUES ( 33, '01/05/2021', 'Página' );
 INSERT INTO INSCRITOS(cantidad, fecha, fuente)
 VALUES ( 18, '01/06/2021', 'Blog' );
 INSERT INTO INSCRITOS(cantidad, fecha, fuente)
 VALUES ( 12, '01/06/2021', 'Página' );
 INSERT INTO INSCRITOS(cantidad, fecha, fuente)
 VALUES ( 34, '01/07/2021', 'Blog' );
 INSERT INTO INSCRITOS(cantidad, fecha, fuente)
 VALUES ( 24, '01/07/2021', 'Página' );
 INSERT INTO INSCRITOS(cantidad, fecha, fuente)
 VALUES ( 83, '01/08/2021', 'Blog' );
 INSERT INTO INSCRITOS(cantidad, fecha, fuente)
 VALUES ( 99, '01/08/2021', 'Página' );


### consultas.sql

 El archivo consultas.sql contiene las preguntas que se pretenden resolver y las querys SQL respectivas
 
 1. ¿Cuántos registros hay?
 2. ¿Cuántos inscritos hay en total?
 3. ¿Cuál o cuáles son los registros de mayor antigüedad?
 HINT: ocupar subconsultas
 4. ¿Cuántos inscritos hay por día? (entendiendo un día como una fecha distinta de
 ahora en adelante)
 5. ¿Qué día se inscribieron la mayor cantidad de personas y cuántas personas se
 inscribieron en ese día?

### respuestas.doc
 El archivo respuestas.doc contiene las querys y muestra las respuestas respectivas obtenidas desde la consola

### Prerrequisitos o Dependencias
Sistema Operativo Windows, Linux, MacOS

### Instalación del Proyecto
Clonar el repositorio:

[# https://github.com/vanemn/desafio2_modulo5_clase6.git]
Ingresar a la carpeta del proyecto:

#### desafio2_modulo5_clase6

### Autor

Vanessa Morales