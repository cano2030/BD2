# Bienvenido al curso de técnicas avanzadas de base de datos

El objetivo de este material es Analizar las diferentes soluciones de bases de datos SQL ( incluyendo las conocidas como **"NoSQL"**), sus gestores de base de datos, en cuales problemas es idóneo usarlos y trabajar con algunos de ellos, como es: 
- Apache Cassandra
- MongoDB
- MySQL
- Oracle

Para realizar el objetivo vamos a analizar de problemas de almacenamiento de datos y se daran criterios para determinar cual bases de datos SQL o NoSQL es idónea para resolver un problema.

El contenido esta dividido en 5 unidades así:
# Diseño base de datos NOSQL
## Enlaces a los contenidos
- [Repaso modelo relacional](C0_INTRO/BD2_C0B_Repaso_Modelo_ER.pdf) =>[ [Video Solución: Fecha 20210126](https://youtu.be/r_7ZQV_CgII) ]
- [Teorema de CAP y clasificación de las bases de datos NOSQL](C1_NO_ONLY_SQL_DESIGN/BD2_C1_NO_ONLY_SQL.pdf)
- [Cassandra Data Modeling Strategies (**ingles**) ](C1_NO_ONLY_SQL_DESIGN/BD2_C1AX_Cassandra%20Data%20Modeling%20Strategies.pdf)
- [Diseño base de datos en Apache Cassandra y Diagramas de Chebotko (Actualizado)](C1_NO_ONLY_SQL_DESIGN/BD2_C1A_Cassandra%20Modelado.pdf)
- [Guia Diseño Apache Cassandra en Ingles](https://cassandra.apache.org/doc/latest/data_modeling/intro.html)
- [Intro y Diseño base de datos en MongoDB](C1_NO_ONLY_SQL_DESIGN/BD2_C1B_Mongo_Modelando.pdf)


# Implementar sistema de base de datos NOSQL usando Apache Cassandra
El contenido de esta unidad abarca los siguientes temas:
- [Instalar base de datos](http://sergalpe.blogspot.com/2018/10/instalar-apache-cassandra-en-windows-url.html)
- [Instalar Herramienta Grafica base de datos](http://sergalpe.blogspot.com/2018/10/ide-grafico-para-apache-cassandra.html)
- Intro características técnicas
   - [GestoresNoSQL –Apache Cassandra Universidad de Cantabria](https://ocw.unican.es/pluginfile.php/2396/course/section/2473/NoSQL_Tema2_Cassandra.pdf)
   - [The Cassandra Query Language (CQL)](https://cassandra.apache.org/doc/latest/cql/index.html)
   - [Info Batch](https://docs.datastax.com/en/archived/cql/3.3/cql/cql_reference/cqlBatch.html)


# Implementar sistema de base de datos NOSQL usando MongoDB
El contenido de esta unidad abarca los siguientes temas:
- [Instalar base de datos y herramienta de admin grafica](C3_MONGODB/BD2_C3B_noSQL_MongoDB-Instalar.pdf)
- Intro características técnicas
   - [GestoresNoSQL –MongoDB Universidad de Cantabria](https://ocw.unican.es/pluginfile.php/2396/course/section/2473/NoSQL_Tema2_MongoDB.pdf)
   - [Agregaciones](https://data-flair.training/blogs/mongodb-aggregation-tutorial/)
- Herramientas de Edición de JSon
   - [JSon WEB Editor](https://jsoneditoronline.org/)
   - [Validar un JSon](https://jsonlint.com/)   
- [Presentación documentacion](C3_MONGODB/BD2_C3_noSQL_Mongo.pdf)
   - Opciones para validar la consistencia de los JSon
   - Introducción al lenguaje de consultas usando JSon
   - Consultas avanzadas y minería de datos usando PipeLines
   - Análisis de consultas e Indexación
- [Vistas](https://docs.mongodb.com/compass/current/views/)


# Analisis NOSQL
- [NoSQL Databases Every Data Scientist Should Know About in 2020](https://www.analyticsvidhya.com/blog/2020/09/different-nosql-databases-every-data-scientist-must-know/)
- Apache Cassandra VS MongoDB
   - [cuando usar Cassandra? o cuando usar Mongodb?](http://solocodigoweb.com/blog/2018/05/18/cuando-usar-cassandra-cuando-usar-mongodb/)
   - [Mongodb vs Cassandra](https://www.educba.com/mongodb-vs-cassandra/)

# Opción procedimental base de datos de distribución libre (MySQL)
## Punto de Partida:
- [Primeras tres formas normales](https://es.wikipedia.org/wiki/Tercera_forma_normal)
- [Denormalización](https://es.wikipedia.org/wiki/Denormalizaci%C3%B3n_(base_de_datos))
- [Modelo Relacinal](https://es.wikipedia.org/wiki/Base_de_datos_relacional)
- [DML](https://es.wikipedia.org/wiki/Lenguaje_de_manipulaci%C3%B3n_de_datos)
## Opcion Procedimental
- [Variables](https://dev.mysql.com/doc/refman/8.0/en/local-variable-scope.html)
- [Condicionales y Ciclos](https://dev.mysql.com/doc/refman/8.0/en/flow-control-statements.html)
- [Procedimientos Almacenados](https://dev.mysql.com/doc/refman/8.0/en/create-procedure.html)
- [Cursores](https://dev.mysql.com/doc/refman/8.0/en/cursors.html)
## Herramientas
- [Guia Instalación](C4_MYSQL/BD2_C4_MySQL-SQLYog-Workbench-Instalar.pdf)
- [Descargar MySQL](http://www.wampserver.com/en/)
- [Descargar Herramienta CASE:MySQL Workbench version 6.3](https://downloads.mysql.com/archives/workbench/)
- [Descargar Herramienta Comandos SQL:SQLYOG](https://github.com/webyog/sqlyog-community/wiki/Downloads)
## Temas a trabajar
### [Conceptos clave MySQL](C4_MYSQL/BD2_C4SP_Conceptos_clave_MySQL.pdf)
- Opción procedimental Procedimientos almacenados y disparadores
- Opción procedimental avanzada (Cursores, Lanzar Errores del Usuario)
### Optimización
- Análisis de consultas e Indexación

# Transaccionalidad y Optimización
## Presentaciones:
- [UNAL transacciones](C6_TRANS_IDX/BD2_C6A_UNAL_transacciones_en_Oracle_y_MySQL.pdf)
- [Modo Auto Commit](C6_TRANS_IDX/BD2_C6B_transacciones_en_Oracle_y_MySQL.pdf)
- [Permisos, Concurrencia y Candados](C6_TRANS_IDX/BD2_C6C_Permisos_Concurrencia_y_candados_MySQL.pdf)
- [Indexación](C6_TRANS_IDX/BD2_C6D_indexaci%C3%B3n.pdf)
- [Ejemplo Optimización MySQL](C6_TRANS_IDX/BD2_C6E_Optimizaci%C3%B3nMySQL.pdf)
- [Permisos](C6_TRANS_IDX/BD2_C6F_Permisos.pdf)

## Videos "Base de Datos" Universidad de Stanford Dbclass:
### Indexación
- [Parte 1](https://www.youtube.com/watch?v=Y7Qlc7f_u0o)
- [Parte 2](https://www.youtube.com/watch?v=HSnwW5Punm0)
### Transacciones
- [Parte 1](https://www.youtube.com/watch?v=FA85kHsJss4)
- [Parte 2](https://www.youtube.com/watch?v=O2wYl9UHFNc)
- [Parte 3](https://www.youtube.com/watch?v=r6ALmAXRHQM)
- [Parte 4](https://www.youtube.com/watch?v=5-dlz0YimR4)

