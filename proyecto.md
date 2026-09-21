# Práctica: Creación y Gestión de Base de Datos EcommerceDB

## 1. Configuración Inicial
**Create a new database**

![alt text](image.png)

---

## 2. Creación de Tablas y Carga de Datos

**Create core tables with constraints**
![alt text](image-1.png)

**Insert sample data into the tables**
![alt text](image-2.png)

**Configuración adicional de la base de datos**
![alt text](image-3.png)

---

## 3. Consultas de Historial

**Query the price history to see changes over time**
![alt text](image-4.png)

---

## 4. Gestión de Datos JSON

**Implementación de metadatos JSON**
![alt text](image-5.png)

**Query the JSON data**
![alt text](image-6.png)

---

## 5. Particionamiento de Tablas
*Partitioning divides large tables into smaller segments for faster queries and easier maintenance. This task creates a partitioned orders table.*

**Create a partitioned order table**
![alt text](image-7.png)

**Query by partition**
![alt text](image-8.png)

---

## 6. Uso de Secuencias
*Sequences generate unique numbers independently of any table. This task uses a sequence for order line item identifiers.*

**Create order details with SEQUENCE**
![alt text](image-9.png)

**Verify the data**
![alt text](image-10.png)

---

## 7. Verificación de Objetos y Restricciones
*Run verification queries to ensure all database objects were created correctly.*

**Verify database objects**
![alt text](image-11.png)

> 📝 **Nota de validación:** This query should fail with a CHECK constraint violation, confirming that the constraint is working correctly.

**Verify the JSON and partitioning queries**
![alt text](image-12.png)