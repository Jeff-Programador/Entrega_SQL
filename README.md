# Entrega_SQL
Este repositorio contiene soluciones SQL para un proyecto sobre una base de datos de películas y alquileres. Las consultas incluyen JOIN, subconsultas, vistas y tablas temporales. El repositorio incluye el archivo SQL con las consultas resueltas, un diagrama de la base de datos y documentación sobre el proceso seguido.

# Proyecto: Lógica de Consultas SQL

Este proyecto tiene como objetivo resolver un conjunto de consultas SQL sobre una base de datos de películas y alquileres. Las consultas son parte de un proyecto académico donde se busca aplicar conocimientos sobre manejo de bases de datos, subconsultas, JOINS, vistas, y estructuras de datos temporales. La base de datos contiene información sobre actores, películas, categorías, alquileres, clientes y pagos.

## Requisitos del Proyecto

- Utilización de **DBeaver** para el desarrollo de las consultas SQL.
- Resolución de las consultas utilizando **una sola tabla**, **relaciones entre tablas**, **subconsultas**, **vistas**, y **estructuras temporales**.
- Buenas prácticas en la escritura de consultas SQL.
- Análisis y entendimiento de los resultados obtenidos de las consultas.

## Descripción de la Base de Datos

La base de datos contiene las siguientes tablas:

- **actor**: Información sobre los actores.
- **film**: Información sobre las películas.
- **category**: Categorías de películas.
- **film_category**: Relaciona películas con categorías.
- **rental**: Información sobre los alquileres de películas.
- **payment**: Información sobre los pagos por alquileres.
- **customer**: Información de los clientes.

La relación entre las tablas es fundamental para resolver las consultas, ya que muchas de ellas requieren combinar datos de varias tablas utilizando **JOINS**.

## Pasos Seguidos en el Proyecto

1. **Exploración de la Base de Datos**:  
   Se inició explorando la estructura de la base de datos en DBeaver para entender las relaciones entre las tablas. Esto incluyó revisar las claves primarias y foráneas, así como los tipos de datos.

2. **Desarrollo de Consultas SQL**:  
   Después de entender las relaciones entre las tablas, se procedió a escribir las consultas SQL que abarcaban diferentes áreas, como la agregación de datos (con `COUNT`, `AVG`, etc.), el uso de `JOINS` para combinar tablas y el manejo de subconsultas.

3. **Optimización de Consultas**:  
   Tras escribir las consultas, se revisaron para asegurar que fuesen eficientes, legibles y que utilizasen las mejores prácticas posibles. Esto incluyó el uso adecuado de `JOIN`, subconsultas y agregaciones.

4. **Documentación**:  
   Finalmente, se documentaron todas las consultas en este repositorio de GitHub, explicando cada consulta y los resultados esperados. Las consultas fueron comentadas en el archivo `consultas.sql` para una mejor comprensión.

## Informe de Análisis

Durante el desarrollo de las consultas, se identificaron diversas oportunidades para aplicar conceptos de SQL en situaciones prácticas, como:

- **Uso de JOINS**: Se emplearon `INNER JOIN` y `LEFT JOIN` para combinar datos de diferentes tablas, especialmente para combinar información sobre actores, películas, y alquileres.
- **Subconsultas**: Se utilizaron subconsultas en algunos casos para calcular valores intermedios, como el alquiler promedio de las películas o el cálculo de la primera fecha de alquiler de una película específica.
- **Vistas**: Se creó una vista para simplificar el cálculo del número de películas en las que ha actuado cada actor.
- **Tablas temporales**: Se crearon tablas temporales para almacenar el total de alquileres por cliente.

Los resultados obtenidos fueron correctos y mostraron cómo se pueden extraer datos de una base de datos compleja mediante el uso de SQL.

## Archivos del Repositorio

Este repositorio contiene los siguientes archivos:

- **`README.md`**: Este archivo, que contiene la descripción del proyecto, los pasos seguidos y el informe de análisis.
- **`esquema_bbdd.png`**: Diagrama visual del esquema de la base de datos, mostrando las tablas y sus relaciones.
- **`consultas.sql`**: Archivo con las consultas SQL resueltas. Cada consulta está identificada por su número y enunciado correspondiente como comentario.

## Instrucciones para Ejecutar las Consultas

1. **Base de Datos**: Asegúrate de que la base de datos esté cargada en PostgreSQL u otro sistema de gestión de bases de datos compatible.
2. **Conexión con DBeaver**: Abre DBeaver y conéctate a tu base de datos.
3. **Ejecuta las Consultas**: Copia y pega las consultas del archivo `consultas.sql` en la consola SQL de DBeaver para obtener los resultados.

## Buenas Prácticas

Durante el desarrollo de las consultas, se siguieron las siguientes buenas prácticas:

- **Legibilidad**: Se utilizó sangrías y un formato consistente en todas las consultas para facilitar su lectura.
- **Uso de comentarios**: Se incluyeron comentarios en las consultas más complejas para explicar su lógica.
- **Optimización**: Se trató de escribir consultas eficientes, utilizando el mínimo número de `JOIN` necesarios y evitando subconsultas innecesarias.



