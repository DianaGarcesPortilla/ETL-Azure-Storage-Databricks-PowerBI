# ETL-Azure-Storage_Databricks_PowerBI

📌 Descripción del proyecto

Este proyecto implementa un pipeline ETL de extremo a extremo para el análisis de ventas, integrando servicios de Azure y herramientas de Business Intelligence.

📥 Extracción de datos

Extracción de datos de ventas trimestrales de ilevo desde Azure Blob Storage

Conexión segura entre Databricks y la cuenta de almacenamiento mediante Azure Key Vault para la gestión de credenciales

🔄 Transformación y almacenamiento

Transformación de los datos en Databricks

Escritura de los datos en formato Delta Lake

Registro de la tabla en el catálogo de Databricks

Corrección de inconsistencias en nombres e identificadores de producto

Control de versiones y trazabilidad de cambios sobre los datos

📊 Consumo en Business Intelligence

Conexión de Databricks con Power BI Desktop

Métodos de conexión utilizados:

ODBC

DirectQuery

Análisis del comportamiento de las ventas mediante visualizaciones e indicadores

🛠️ Tecnologías utilizadas

Azure Blob Storage

Azure Key Vault

Databricks

Delta Lake

Power BI

Python / PySpark

https://github.com/DianaGarcesPortilla/ETL-Azure-Storage-Databricks-PowerBI/blob/main/ventas_integracionBI.ipynb

[![Databricks Notebook](https://raw.githubusercontent.com/DianaGarcesPortilla/ETL-Storage_Databricks_PowerBI/main/image08.png)](https://github.com/DianaGarcesPortilla/ETL-Storage_Databricks_PowerBI/blob/main/ventas_integracionBI.ipynb)
