# data-engineering-with-python
Curso 01 de Data Engineering

## 01.- ETL - Python
Se realizarán las fases de extracción, transformación y carga de los procesos de ETL, conla finalidad de poder contar con data que responsa a los siguientes KPIS:
- Ventas completadas por cliente.
- Compras realizadas por País.
- Temporada de Fechas, que se realizron más compras.

Para eso se presenta el siguiente diagrama ETL.

![DIAGRAMA_ETL](https://user-images.githubusercontent.com/76765706/177062651-33d10509-5e02-4c48-9791-04a1d813896f.png)

Se aplicaron reglas de negocio, asi como también se aplicó limpieza de datos nulos y eliminación de columnas que no se requieren para el análisis.

## Pasos:

1.- Se procesaron los archivos csv, para ello se dejaron 4 tablas en Mysql.
2.- Se procesaron los archivos csv.
3.- Se hizo cruce de las tablas order_items, orders y customer; para disponibilizar en una base de datos de postgres.

