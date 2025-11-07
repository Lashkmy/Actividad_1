# 🌍 Actividad 1 — Big Data
**Autores:**  
- Indira Hamdam (Medellín, Antioquia, Colombia)  
- Cristian Vicioso  (Santa Marta, Magdalena, Colombia) 

**Materia:** Big Data  
**Institución:** I. U. Digital de Antioquia  
**Docente:** Andres Felipe Callejas Jaramillo  
**Plataforma utilizada:** Databricks Free Edition

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
Actividad_1/

├── Hamdam_Indira_Vicioso_Cristian_Actividad_1.ipynb # Notebook principal

├── modelo_ERD.png # Diagrama entidad–relación

└── README.md # Este archivo

---

## 📘 Contenido del Notebook

El notebook contiene las siguientes secciones:

1️⃣ **Definición de la problemática y dataset**  
2️⃣ **Diseño del modelo entidad–relación (ERD)**  
3️⃣ **Creación de la base de datos e inserción de datos**  
4️⃣ **Consultas SQL de verificación y análisis**  
5️⃣ **Conclusiones**

Cada sección incluye explicaciones en texto y resultados en código ejecutable.

---

## 📊 Consultas de ejemplo

- `SELECT COUNT(*) FROM Medicion_Ambiental;` — Conteo de registros.  
- `DESCRIBE TABLE Medicion_Ambiental;` — Estructura de columnas.  
- `SELECT * FROM Medicion_Ambiental WHERE id_ciudad = 1;` — Filtro por ciudad (Medellín).

---

## 🔗 Enlace del repositorio

👉 [[https://github.com/Lashkmy/Actividad_1](https://github.com/Lashkmy/Actividad_1.git)]

---

## ✨ Créditos

Proyecto elaborado como parte de la formación en **Big Data**, utilizando herramientas open source y datos públicos de Kaggle.
