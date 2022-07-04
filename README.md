# data-engineering-with-python
Curso 01 de Data Engineering

Para el proceos ETL se utilizó Pyhton 3.8, Mysql, Postgres, Pandas, SQLAlchemy, Jupyter Notebook.

## 01.- ETL - Python
Se realizarán las fases de extracción, transformación y carga de los procesos de ETL, conla finalidad de poder contar con data que responsa a los siguientes KPIS:
- Ventas completadas por cliente.
- Compras realizadas por País.
- Temporada de Fechas, que se realizron más compras.

Para eso se presenta el siguiente diagrama ETL.

![DIAGRAMA_ETL](https://user-images.githubusercontent.com/76765706/177062651-33d10509-5e02-4c48-9791-04a1d813896f.png)

Se aplicaron reglas de negocio, asi como también se aplicó limpieza de datos nulos y eliminación de columnas que no se requieren para el análisis.

## Pasos:

- Se procesaron los archivos csv y se dejaron 4 tablas en Mysql.

![image](https://user-images.githubusercontent.com/76765706/177063022-ca74e63c-68fb-4c7c-9811-d535e7e2a6e1.png)


Tabla customer

![image](https://user-images.githubusercontent.com/76765706/177063039-27d1d299-2dc3-4890-b638-b0d69d1af010.png)


Tabla orders

![image](https://user-images.githubusercontent.com/76765706/177063059-386ba167-431b-48e5-a626-7b34ccc715b6.png)


Tabla oder_items

![image](https://user-images.githubusercontent.com/76765706/177063084-345ecb28-74fa-4c0b-95d8-60057fb939fb.png)


Tabla categories

![image](https://user-images.githubusercontent.com/76765706/177063103-2feaa5eb-48b9-412c-b5e1-c201af0e5cdb.png)


- Se procesaron los archivos csv.

Archivo CSV Products

![image](https://user-images.githubusercontent.com/76765706/177063139-c90305c7-54bb-42d7-a02b-a381a6dcc833.png)


Archivo CSV Departments

![image](https://user-images.githubusercontent.com/76765706/177063177-7b9ce3ca-e5de-4ef0-bec2-a5623c370a8b.png)


- Se aplicó la limpieza y transformación de los datos.

- Se hizo cruce de las tablas order_items, orders y customer; para disponibilizar en una base de datos de postgres.

![image](https://user-images.githubusercontent.com/76765706/177063212-63614fc0-0fa9-4248-b1c4-3e11e03864a5.png)

