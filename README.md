# PruebaMedioParcial
Prueba de medio Parcial - Segundo Parcial
## Universidad Técnica de Ambato

### Facultad de Ingeniería en Sistemas

### Asignatura: Bases de Datos

---

# Información del Estudiante

* Nombre: Brittany Carla Paredes Chavez
* Escenario asignado: Productora Cinematográfica
* Integridad referencial: ON DELETE CASCADE

---

# Descripción del Proyecto

El presente proyecto consiste en el diseño e implementación de una base de datos relacional para una Productora Cinematográfica utilizando Oracle SQL.

El sistema permite administrar información relacionada con:

* películas,
* actores,
* directores,
* géneros,
* y participaciones de actores en películas.

Además, se aplican restricciones de integridad para garantizar consistencia y seguridad en los datos almacenados.

---

# Objetivos

## Objetivo General

Diseñar e implementar una base de datos relacional aplicando sentencias DDL, DML e integridad referencial en Oracle SQL.

## Objetivos Específicos

* Construir el modelo lógico de la base de datos.
* Implementar tablas utilizando CREATE TABLE.
* Aplicar restricciones PK, FK, CHECK, UNIQUE y NOT NULL.
* Utilizar ON DELETE CASCADE.
* Ejecutar consultas SQL avanzadas.
* Analizar integridad referencial y atomicidad.

---

# Modelo de Base de Datos

## Entidades principales

* GENERO
* DIRECTOR
* ACTOR
* PELICULA
* PARTICIPACION

## Relaciones

* Un director puede dirigir muchas películas.
* Un género puede pertenecer a muchas películas.
* Un actor puede participar en muchas películas.
* Una película puede tener muchos actores.

---

# Tecnologías Utilizadas

* Oracle SQL
* Oracle Database
* GitHub

---

# Restricciones Implementadas

## PRIMARY KEY

Permite identificar de forma única cada registro.

## FOREIGN KEY

Mantiene integridad referencial entre tablas.

## CHECK

Valida condiciones específicas en los datos.

## UNIQUE

Evita registros duplicados.

## NOT NULL

Impide valores vacíos en campos obligatorios.

## ON DELETE CASCADE

Elimina automáticamente registros relacionados al eliminar el registro padre.

---

# Consultas SQL Implementadas

Se desarrollaron consultas utilizando:

* IN
* LIKE
* BETWEEN
* AVG
* JOIN

---

# Integridad Referencial

La base de datos utiliza ON DELETE CASCADE para garantizar que no existan registros huérfanos y mantener consistencia entre tablas relacionadas.

---

# Análisis Profesional

## Atomicidad

Garantiza que las transacciones se ejecuten completamente o no se ejecuten.

## DELETE sin WHERE

Puede eliminar todos los registros de una tabla y representar un riesgo crítico.

## ON DELETE CASCADE

Permite eliminar automáticamente registros hijos relacionados.

---

# Evidencias Incluidas

* Scripts SQL
* Modelo lógico
* Capturas Oracle
* Desarrollo manual
* Commits en GitHub

---

# Conclusión

El desarrollo de este proyecto permitió aplicar conceptos fundamentales de bases de datos relacionales utilizando Oracle SQL, incluyendo modelado lógico, integridad referencial, manipulación de datos y consultas avanzadas. Además, se fortaleció el manejo de restricciones y buenas prácticas en administración de bases de datos.
