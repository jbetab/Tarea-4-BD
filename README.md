Informe Técnico y Proyecto: PostgreSQL

Este repositorio contiene la documentación, los esquemas de base de datos y las consultas desarrolladas para el Informe Técnico de PostgreSQL. El objetivo principal de este trabajo es presentar un análisis detallado sobre el diseño, implementación, optimización y administración de bases de datos relacionales utilizando PostgreSQL.

Contenido del Repositorio

El repositorio está organizado de la siguiente manera:

/docs: Contiene la documentación principal del proyecto y el archivo de informe técnico.

/sql / /scripts: Scripts de creación del esquema (DDL), inserción de datos de prueba (DML), consultas avanzadas, vistas e índices.

/config: Archivos de configuración de ejemplo o notas sobre optimización de parámetros de PostgreSQL (postgresql.conf).

Trabajo Realizado

Dentro de este proyecto se abordaron los siguientes puntos clave:

Diseño y Modelado Relacional:

Definición del modelo entidad-relación (E-R) y normalización de tablas.

Creación de esquemas con restricciones de integridad (llaves primarias, foráneas y checks).

Desarrollo SQL:

Consultas avanzadas utilizando joins, subconsultas, funciones de agregación y funciones de ventana (window functions).

Creación de vistas, procedimientos almacenados / funciones (PL/pgSQL) y triggers.

Optimización y Rendimiento:

Análisis del plan de ejecución mediante EXPLAIN ANALYZE.

Estrategias de indexación (B-Tree, GIN, GiST) para optimizar el tiempo de respuesta.

Administración y Seguridad:

Configuración de roles, usuarios y permisos (GRANT / REVOKE).

Estrategias de respaldo (backup) y restauración de datos mediante pg_dump.

Requisitos Previos

Para ejecutar los scripts e interactuar con la base de datos se requiere:

PostgreSQL (versión 13 o superior recomendada).

Un cliente de base de datos como pgAdmin, DBeaver o la CLI de PostgreSQL (psql).
