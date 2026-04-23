# 📊 Proyecto de Análisis de Datos – Online Retail

**Autor:** Jamil Gustavo Alarcón Terán
**Curso:** Herramientas básicas para el Análisis de Datos
**Cohorte:** 2026

---

## 🎯 Objetivo

El objetivo de este proyecto es analizar el comportamiento de las ventas en una tienda online utilizando técnicas de análisis de datos. Se busca identificar patrones, tendencias y relaciones entre variables como productos, clientes, países y tiempo, con el fin de generar información útil para la toma de decisiones.

---

## 📂 Dataset

Se utilizó el dataset **Online Retail**, que contiene información de transacciones realizadas en una tienda online.

Incluye variables como:

* InvoiceNo (factura)
* Description (producto)
* Quantity (cantidad)
* UnitPrice (precio)
* InvoiceDate (fecha)
* CustomerID (cliente)
* Country (país)

📎 Fuente del dataset:
https://www.kaggle.com/datasets/ulrikthygepedersen/online-retail-dataset

---

## 🧹 Proceso de análisis

El análisis se desarrolló en las siguientes etapas:

1. Carga de datos en Python (Google Colab).
2. Limpieza de datos: eliminación de valores nulos, duplicados y registros inconsistentes.
3. Conversión de variables (fechas) y creación de la variable **TotalPrice**.
4. Análisis exploratorio (EDA) para identificar patrones en ventas, productos, clientes y países.
5. Visualización de resultados mediante gráficos y dashboard en Power BI.

📎 Notebook: https://github.com/alarconjamil28-dot/herramientasbasicas-alarcon-jamil/tree/main/data/raw
📎 Dataset CSV: (agregar link aquí)
📎 Dashboard: (agregar link o imagen aquí)

---

## 📊 Dashboard en Power BI

El dashboard presenta los principales indicadores del negocio:

* Ingresos Totales
* Número de Ventas
* Clientes Únicos

Además, incluye visualizaciones como:

* Ventas mensuales
* Ventas por país
* Top productos por ingreso
* Top clientes

Esto permite analizar la información de manera clara e interactiva.

---

## 📊 Principales hallazgos

* Las ventas presentan crecimiento en ciertos periodos del año.
* Existe concentración de ingresos en pocos productos.
* Algunos países dominan la mayor parte de las ventas.
* Un grupo reducido de clientes genera gran parte del ingreso.

---

## 💻 Estructura del repositorio

/data/raw/
/notebooks/
/dashboard/
README.md

---

## 📌 Herramientas utilizadas

* Python (pandas, matplotlib, seaborn)
* Google Colab
* Power BI
* GitHub

---

## 🚀 Conclusión

El análisis permitió comprender el comportamiento de las ventas y detectar patrones clave que pueden ser utilizados para mejorar estrategias comerciales y optimizar la toma de decisiones basada en datos.
