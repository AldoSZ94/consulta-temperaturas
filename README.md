# 🌡️ Visualización de Temperaturas Mensuales en Ciudades Argentinas

Este proyecto permite al usuario explorar visualmente los registros de temperatura máxima y mínima en distintas ciudades de Argentina durante el año 2023. Se realiza una selección interactiva de ciudad y mes, y se genera un gráfico de líneas con las temperaturas correspondientes a cada día del mes.

---

## 📁 Archivos incluidos

- `datos_meteorologicos_arg_2023.csv`: Datos diarios de temperatura por ciudad.
- `proyecto4_consulta_temperaturas.py`: Script interactivo en Python para filtrar y graficar datos climáticos por ciudad y mes.

---

## 🛠 Tecnologías utilizadas

- Python 3  
- Pandas  
- NumPy  
- Matplotlib

---

## 🔍 ¿Qué se hace en el análisis?

### Carga y preparación de datos
- Lectura de archivo `.csv` con datos meteorológicos de distintas ciudades argentinas.
- Limpieza de nombres de columnas y conversión del campo de fecha.
- Generación automática de listas de ciudades y nombres de meses.

### Selección interactiva
- El usuario elige una ciudad y un mes para analizar.
- Se filtran los datos según las elecciones del usuario.

### Visualización
- Se grafican las temperaturas máximas y mínimas por día del mes seleccionado.
- Se incluye título, etiquetas, leyenda y estilo claro.

---

## 🎯 Objetivo

Facilitar la exploración visual de los datos climáticos para identificar patrones de temperatura en ciudades argentinas. Este análisis puede ser útil para estudiantes, investigadores o cualquier persona interesada en el comportamiento del clima en el país durante el año 2023.
