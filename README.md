# 🌍 Actividad 1 — Big Data
**Autores:**  
- Indira Hamdam (Santa Marta, Magdalena, Colombia)  
- Cristian Vicioso (Medellín, Antioquia, Colombia)  

**Materia:** Big Data  
**Institución:** [Nombre de la universidad o institución educativa]  
**Docente:** [Nombre del profesor si aplica]  
**Plataforma utilizada:** Databricks Community Edition (Free)

---

## 🧠 Descripción del proyecto

Este proyecto corresponde a la **Actividad 1 de la asignatura Big Data**, en la cual se aplican los conceptos de bases de datos analíticas para diseñar, crear y consultar una base de datos relacional a partir de un conjunto de datos real.  

La problemática seleccionada se centra en el **análisis de la calidad del aire y su relación con la salud pública** en diferentes ciudades de Colombia.  

El objetivo principal es construir una base de datos analítica que permita almacenar, consultar y analizar mediciones ambientales (como PM2.5, PM10, NO₂, temperatura y humedad), junto con indicadores de salud asociados, de modo que se pueda observar la relación entre contaminación atmosférica y casos respiratorios reportados en cada ciudad.

---

## 📦 Dataset utilizado

**Fuente:** [Air Quality Data Set — Kaggle](https://www.kaggle.com/datasets/fedesoriano/air-quality-data-set)  
**Autor:** Federico Soriano  
**Descripción:**  
Este conjunto de datos contiene mediciones diarias de calidad del aire (PM2.5, PM10, NO₂, CO, O₃, temperatura, humedad, entre otras) tomadas en distintas estaciones del mundo.  

Para esta actividad se filtraron y adaptaron registros representativos de dos ciudades colombianas: **Medellín (Antioquia)** y **Santa Marta (Magdalena)**.

---

## 🧩 Modelo Entidad–Relación (ERD)

El modelo está compuesto por dos entidades principales:  
1. **Ciudad** — almacena información de las ciudades.  
2. **Medición_Ambiental** — contiene los valores medidos de contaminantes y variables climáticas asociadas a cada ciudad.

**Relación:**  
Una ciudad puede tener muchas mediciones ambientales → relación **1:N (uno a muchos)**.

📊 *Diagrama ER incluido en el notebook como imagen (`modelo_ERD.png`).*

---

## ⚙️ Tecnologías y herramientas

- 🧠 **Databricks Community Edition (Free)**
- 🧮 **Apache Spark SQL**
- 🐍 **Python (pandas, matplotlib)**
- 🧱 **SQLite / Spark DataFrame**
- 🖼️ **Draw.io / Mermaid** (para el diagrama ERD)

---

## 💻 Estructura del repositorio
