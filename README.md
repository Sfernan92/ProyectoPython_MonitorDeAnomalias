# 🌍 PROYECTO 06 – Monitor de Anomalías en Sensores IoT (Calidad del Aire)



## 📌 Descripción del proyecto

Desarrollo de un sistema de análisis y monitorización de datos procedentes de sensores IoT para supervisar la calidad del aire en distintas zonas de una ciudad.

El objetivo es procesar las mediciones de partículas PM2.5, identificar posibles fallos técnicos en los sensores y detectar situaciones de contaminación.

## 🎯 Objetivos

- 🛠️ Identificar y filtrar lecturas inválidas o errores de hardware.
- 📊 Calcular los niveles medios de contaminación (PM2.5) por sensor y zona.
- 🔎 Detectar anomalías en las mediciones ambientales.
- 🚨 Clasificar las alertas según el nivel de contaminación registrado.

## ⚙️ Funcionalidades principales

### 1. 🛠️ Filtrado de datos inválidos

Identificación y eliminación de lecturas incorrectas, como valores `None` o negativos (por ejemplo, `-999.0`).

### 2. 📊 Cálculo de promedios por zona

Cálculo del nivel medio de partículas PM2.5 de cada sensor utilizando exclusivamente las mediciones válidas.

### 3. ⚠️ Detección de anomalías ambientales

Identificación de las horas y zonas donde los niveles de PM2.5 superan el límite de seguridad establecido (`50.0`).

### 4. 🚨 Clasificación de alertas

Diferenciación de los episodios de contaminación mediante dos niveles:

- 🟡 **Alerta moderada:** Superación del límite de seguridad.
- 🔴 **Alerta crítica:** Nivel elevado de contaminación.

## 🧰 Tecnologías utilizadas

- 🐍 Python
- 📊 Análisis y procesamiento de datos
- 🗂️ Estructuras de datos
- 🧮 Operaciones estadísticas y filtrado de información

## 🎓 Nivel del proyecto

**Intermedio**

---

## 💡 Objetivo final

Mejorar la fiabilidad de los datos recogidos por sensores IoT y facilitar la identificación temprana de posibles episodios de contaminación atmosférica.
