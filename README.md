# 📊 Actividad semana 14 - Análisis descriptivo con R

**Autora:** Raquel Martin  
**Fecha:** `r Sys.Date()`

---

## 🧠 Descripción del proyecto

Este proyecto consiste en una actividad de análisis descriptivo realizada en R utilizando el dataset **Davis** del paquete `car`.

El objetivo principal es aplicar técnicas de estadística descriptiva y visualización de datos para estudiar variables numéricas y categóricas, así como detectar valores atípicos (outliers) y comprobar la normalidad de los datos.

---

## 📦 Dataset utilizado

- **Davis dataset** (paquete `car`)
- Contiene variables como:
  - Peso
  - Altura
  - Variables auto-reportadas
  - Variables categóricas asociadas

---

## 🛠️ Tecnologías y librerías utilizadas

El análisis se ha realizado en **R**, utilizando las siguientes librerías:

- `tidyverse` → manipulación de datos
- `ggplot2` → visualización
- `car` → dataset Davis
- `kableExtra` → tablas formateadas
- `plotly` → gráficos interactivos
- `modeest` → medidas estadísticas
- `agricolae` → análisis estadístico
- `gridExtra`, `grid` → organización de gráficos
- `stats` → funciones estadísticas básicas

---

## 📊 Contenido del análisis

El trabajo incluye:

### 🔹 Estadística descriptiva
- Media
- Mediana
- IQR
- Frecuencias para variables categóricas

### 🔹 Detección de outliers
- Método del rango intercuartílico (IQR)
- Representación mediante boxplots

### 🔹 Visualización de datos
- Boxplots interactivos
- Histogramas por variable numérica

### 🔹 Normalidad
- Test de Shapiro-Wilk
- Evaluación de normalidad por variable

---

## 📈 Resultados principales

- Se identifican variables con distribución asimétrica
- Se detectan posibles valores atípicos en variables numéricas
- Se observa que no todas las variables siguen distribución normal

---


---

## 🚀 Cómo reproducir el análisis

1. Abrir el archivo `.Rmd` en RStudio
2. Instalar las librerías necesarias
3. Ejecutar el documento con "Knit"
4. Visualizar resultados en HTML o PDF

---

## 👩‍💻 Autor

Raquel Martin  
Máster en Bioestadística y Bioinformática
