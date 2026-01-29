# Series_de_tiempo
# 📈 Introducción a Series de Tiempo

Este repositorio contiene material introductorio y aplicado sobre **análisis de series de tiempo**, con énfasis en modelos clásicos, criterios de selección y aplicaciones financieras.

El objetivo es entender **cómo modelar, analizar y predecir series de tiempo** utilizando herramientas estadísticas y econométricas, partiendo desde los conceptos básicos hasta modelos más avanzados como ARIMA y GARCH.

---

## 📌 Contenido del curso

### 1. ¿Qué es una serie de tiempo?
- Definición de serie de tiempo
- Componentes de una serie de tiempo:
  - Tendencia
  - Estacionalidad
  - Ciclo
  - Ruido
- Ejemplos de series de tiempo reales

---

### 2. Procesos estocásticos
- Concepto de proceso estocástico
- Series estacionarias vs no estacionarias
- Media, varianza y autocovarianza
- Estacionariedad débil

---

### 3. Autocorrelación
- Función de autocorrelación (**ACF**)
- Función de autocorrelación parcial (**PACF**)
- Interpretación de ACF y PACF
- Uso de ACF y PACF para identificación de modelos

---

### 4. Modelos ARIMA
Modelos **ARIMA(p, d, q)**:
- **AR(p)**: modelo autorregresivo
- **I(d)**: diferenciación para estacionariedad
- **MA(q)**: media móvil
- Interpretación de parámetros
- Identificación del orden del modelo
- Ajuste y validación

---

### 5. Modelos SARIMA
Modelos **SARIMA(p, d, q)(P, D, Q)\_s**:
- Estacionalidad en series de tiempo
- Diferenciación estacional
- Interpretación de los parámetros estacionales
- Rol del periodo estacional \(s\)
- Comparación ARIMA vs SARIMA

---

### 6. Estimación y evaluación del modelo
- Método de **máxima verosimilitud**
- Log-verosimilitud
- Criterios de información:
  - **AIC (Akaike Information Criterion)**
  - **BIC (Bayesian Information Criterion)**
- Selección óptima del modelo
- Diagnóstico de residuos

---

### 7. Series de tiempo financieras
- Características de series financieras:
  - Volatilidad
  - Clustering
  - No normalidad
- Retornos financieros
- Limitaciones de ARIMA en finanzas

---

### 8. Modelos de volatilidad
- Introducción a modelos **ARCH** y **GARCH**
- Modelo **GARCH(1,1)**
- Interpretación económica
- Aplicaciones en mercados financieros
- Comparación con modelos tradicionales

---

## 🛠 Herramientas utilizadas
- Python / R (según aplique)
- Librerías estadísticas y econométricas
- Visualización de datos
- Ajuste y validación de modelos

---

## 🎯 Objetivo del repositorio
Este repositorio busca:
- Construir intuición sobre series de tiempo
- Entender la lógica detrás de los modelos ARIMA y GARCH
- Aplicar modelos a datos reales
- Desarrollar criterio para selección y evaluación de modelos

---

## 📚 Aplicaciones
- Series macroeconómicas
- Series financieras
- Pronósticos
- Análisis de riesgo y volatilidad

---

## ✨ Nota
Este repositorio corresponde a un curso de **Introducción a Series de Tiempo**, por lo que el enfoque es **conceptual, práctico y aplicado**, priorizando la comprensión económica y estadística de los modelos.

