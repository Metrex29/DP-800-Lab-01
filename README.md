# EcommerceDB - Database Management Project

## Descripción
Este proyecto contiene los scripts T-SQL para la creación, configuración y gestión de una base de datos de comercio electrónico (`EcommerceDB`). Incluye implementaciones avanzadas como el manejo de datos JSON, particionamiento de tablas y uso de secuencias.

## Características Principales
* **Creación de Base de Datos y Tablas Core:** Definición de la estructura principal con sus respectivas restricciones (Constraints).
* **Historial de Precios:** Consultas temporales para rastrear la evolución de los precios a lo largo del tiempo.
* **Gestión de Metadatos JSON:** Implementación de columnas JSON para atributos dinámicos de productos y consultas específicas sobre esta estructura.
* **Particionamiento de Tablas:** División de la tabla de pedidos en segmentos más pequeños para optimizar el rendimiento de las consultas y facilitar el mantenimiento.
* **Secuencias (SEQUENCE):** Generación de identificadores únicos e independientes para las líneas de detalle de los pedidos.
* **Validación de Integridad:** Scripts de comprobación para asegurar la correcta creación de los objetos y el funcionamiento de las restricciones `CHECK`.

## Requisitos
* Microsoft SQL Server (con soporte para funciones JSON, Partitioning y Sequences).
* SQL Server Management Studio (SSMS) o Azure Data Studio.

## Estructura de Ejecución
El proyecto está estructurado para ejecutarse en el siguiente orden:
1. Configuración inicial de la base de datos.
2. Creación de tablas principales y carga de datos de prueba.
3. Consultas analíticas sobre el historial de datos.
4. Implementación y consulta de metadatos JSON.
5. Creación de particiones y ejecución de consultas por partición.
6. Inserción de detalles de pedido utilizando `SEQUENCE`.
7. Verificación final de objetos y comprobación intencionada de restricciones.