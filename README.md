# 🌎 Análisis de Movilidad Urbana y Economía en Latinoamérica

## 📌 Descripción del proyecto

Este proyecto analiza indicadores de **movilidad urbana y variables económicas en 15 ciudades latinoamericanas durante 2024**.

El objetivo es explorar las diferencias de movilidad entre ciudades y analizar si existe una relación entre los niveles de congestión y algunos indicadores económicos y demográficos.

El análisis se realizó con **Python**, utilizando un dataset consolidado con información de movilidad y economía.

---

## 🎯 Objetivo

Responder la siguiente pregunta:

> **¿Existe una relación clara entre los niveles de congestión urbana y los indicadores económicos de las ciudades analizadas?**

El análisis es exploratorio y correlacional, por lo que las relaciones encontradas **no implican causalidad**.

---

## 🛠️ Herramientas utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- GitHub

---

## 📊 Datos analizados

El dataset final contiene información de **15 ciudades latinoamericanas correspondiente a 2024**.

Las variables analizadas se dividen principalmente en dos grupos:

### 🚗 Movilidad urbana

- Retrasos asociados a la congestión (`jams_delay`)
- Índice de tráfico (`traffic_index_live`)
- Longitud de congestionamientos
- Cantidad de congestionamientos
- Minutos de retraso
- Tiempo de viaje por cada 10 km

### 💰 Economía y población

- PIB per cápita
- Tasa de desempleo
- Población

Las fuentes utilizadas en el proyecto original corresponden a información de **TomTom Traffic Index** y **OECD Cities**.

---

## 🔎 Metodología

El proyecto incluyó:

1. Revisión y validación de la calidad de los datos.
2. Análisis descriptivo de las variables.
3. Comparación de los niveles de congestión entre ciudades.
4. Análisis del tiempo de viaje por cada 10 km.
5. Exploración de la relación entre movilidad, PIB per cápita, desempleo y población.
6. Cálculo de correlaciones.
7. Visualización de los principales patrones.
8. Interpretación de resultados y elaboración de recomendaciones.

---

## 💡 Principales hallazgos

### 1. La congestión se concentra en algunas grandes ciudades

**Ciudad de México, São Paulo, Bogotá y Lima** se encuentran entre las ciudades con mayores valores de `jams_delay` dentro del dataset analizado.

Esto muestra que los niveles de congestión presentan diferencias importantes entre las ciudades latinoamericanas estudiadas.

### 2. El PIB per cápita no explica claramente la congestión

La correlación entre **PIB per cápita y `jams_delay` es aproximadamente 0.28**, lo que representa una asociación positiva, pero débil.

Por lo tanto, en esta muestra no se observa evidencia de una relación fuerte entre un mayor PIB per cápita y mayores niveles de congestión.

### 3. Una sola métrica no es suficiente para evaluar la movilidad

Ciudades como **Lima y Bogotá** destacan por sus tiempos de viaje por cada 10 km, mientras que **Ciudad de México y São Paulo** presentan valores elevados en otras métricas de congestión.

Esto indica que es conveniente analizar diferentes indicadores antes de evaluar el desempeño de movilidad de una ciudad.

---

## 📈 Conclusiones

El análisis muestra diferencias importantes en los patrones de movilidad de las ciudades latinoamericanas estudiadas.

Sin embargo, **no se encontró una relación fuerte y directa entre el PIB per cápita y los niveles de congestión**.

Los resultados sugieren que la movilidad urbana probablemente depende de múltiples factores adicionales, como infraestructura vial, disponibilidad de transporte público, densidad urbana y uso del automóvil.

---

## 🚀 Recomendaciones

Para futuros análisis sería recomendable:

- Incorporar información sobre infraestructura y transporte público.
- Analizar la densidad poblacional y el uso del automóvil.
- Ampliar el número de ciudades estudiadas.
- Incorporar varios años para analizar la evolución de la movilidad.
- Utilizar diferentes indicadores de congestión en lugar de depender de una sola métrica.

---

## ⚠️ Limitaciones

El dataset contiene únicamente **15 ciudades y datos correspondientes a 2024**.

Las correlaciones muestran asociaciones entre variables, pero **no permiten establecer relaciones de causa y efecto**.

---

## 📁 Archivos del repositorio

- `Movilidad_Urbana_Economia_Latinoamerica.ipynb` — Notebook con el análisis completo.
- `ladb_mobility_economy_2024_clean.csv` — Dataset consolidado utilizado para el análisis.

---

## 👩‍💻 Autora

**Lidia Pineda**

Proyecto desarrollado como parte de mi portafolio de **Análisis de Datos**, enfocado en demostrar habilidades de limpieza, exploración, visualización e interpretación de datos con Python.
