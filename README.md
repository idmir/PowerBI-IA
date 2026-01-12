# Power BI + IA: Modelo de Ventas Globales con Power BI Modeling MCP Server

Este repositorio contiene el caso práctico utilizado en el video de YouTube:

> **“Power BI + IA: Crea un modelo de ventas globales sin escribir DAX ni Power Query (Modeling MCP)”**

El objetivo es mostrar cómo combinar **Power BI**, **Inteligencia Artificial** y **Power BI Modeling MCP Server** para construir un modelo de **ventas globales estilo empresa de clase mundial**, reduciendo el trabajo manual en Power Query y DAX.

---

## 🎯 Objetivo del caso

Demostrar cómo la IA puede colaborar en el **modelado semántico de Power BI** para:

- Importar y preparar automáticamente múltiples archivos **CSV**.  
- Identificar tablas de **hechos** y **dimensiones** y nombrarlas siguiendo buenas prácticas (`Fact*` / `Dim*`).  
- Crear una tabla de fechas (**DimFecha**) y relacionarla con la tabla de hechos.  
- Centralizar las **medidas de negocio** en una tabla de solo medidas (**Medidas**).  
- Sugerir la estructura de un **dashboard** para dirección (Resumen Global) y operación (Detalle por Región y Producto).

Todo utilizando **prompts en lenguaje natural**, sin escribir manualmente fórmulas DAX ni código M de Power Query.

---

## 🧩 Escenario de negocio: GlobalTech Retail

La empresa ficticia **GlobalTech Retail**:

- Vende **laptops, smartphones y accesorios**.  
- Opera en **América, Europa y Asia**.  
- Comercializa por dos canales: **Tienda** y **Online**.  

Preguntas típicas que se responden con el modelo:

- ¿En qué **región** se concentra la mayor venta neta?  
- ¿Qué **categoría de producto** genera más ingresos?  
- ¿Cuánto estamos otorgando en **descuentos**?  
- ¿Qué canal funciona mejor: **Online** o **Tienda**?  

---

## ▶️ Video del caso práctico

Puedes ver el desarrollo completo paso a paso en YouTube:

👉 **Video:** `https://youtu.be/T9UYXQjGd0o`

En el video se muestra:

1. Revisión de los archivos CSV de ventas, productos y países.  
2. Creación del proyecto **PBIP** en Power BI Desktop.  
3. Apertura del proyecto en **Visual Studio Code**.  
4. Uso de prompts con **Power BI Modeling MCP Server** para:
   - Importar y tipar datos desde CSV.  
   - Identificar y renombrar tablas Fact/Dim.  
   - Crear **DimFecha** y sus relaciones.  
   - Crear la tabla **Medidas** con KPIs:
     - VentasBrutas  
     - ImporteDescuento  
     - VentasNetas  
     - UnidadesVendidas  
     - PrecioPromedio  
   - Sugerir la estructura del dashboard.  
5. Construcción del reporte en Power BI (Resumen Global + Detalle Región/Producto).

---

