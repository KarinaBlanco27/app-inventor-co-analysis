# app-inventor-co-analysis
Aplicación móvil desarrollada en MIT App Inventor que visualiza tendencias históricas y estacionalidad de contaminación (CO) entre 2010 y 2021 en México.



# 🌍 Air Quality Trends Analyzer (2010-2021)

Esta aplicación móvil permite visualizar el comportamiento histórico de contaminantes atmosféricos, específicamente Monóxido de Carbono (CO), analizando patrones estacionales y tendencias a lo largo de una década, al igual que realiza predicciones de la calidad del aire en años proximos.

## 🚀 Características Principales
* **Visualización de Datos:** Gráficas interactivas que muestran la evolución de la contaminación.
* **Análisis de Estacionalidad:** Identificación de los meses con mayores picos de contaminación.
* **Dataset Procesado:** Uso de datos reales de estaciones de monitoreo, limpiados y optimizados con Python.
* **Retroallimentacion con IA:** Analisis de tendencias para realizar predicciones.


## 🛠️ Tecnologías Utilizadas
* **Frontend:** MIT App Inventor (Interfaz y Lógica de Bloques).
* **Backend / Datos:** Google Sheets & CSV.
* **Procesamiento de Datos:** Python (Pandas) para limpieza, interpolación y detección de outliers.
* **Intelgencia Artificial:**
Ollama para realizar retroalimentacion y analisis de las predicciones realizadas.

## 📊 Sobre los Datos
Los datos provienen de mediciones horarias de estaciones de monitoreo entre 2010 y 2021, el dataset utilizado proviene de Eliana Kai Juarez.
[Mexico Hourly Air Pollution (2010-2021)](https://www.kaggle.com/datasets/elianaj/mexico-air-quality-dataset?resource=download&select=stations_daily.csv).

Se realizó un pre-procesamiento para:
1.  Eliminar errores de medición (outliers > 50 ppm).
2.  Calcular promedios mensuales para suavizar tendencias.
3.  Adaptar la estructura del dataset para ser compatible con componentes gráficos móviles.

## 📸 Capturas de Pantalla

![Inicio](https://github.com/user-attachments/assets/6d8910a2-d163-40c4-bd72-6059941683f8)
![AnalisisSimple](https://github.com/user-attachments/assets/31359a5e-2e7e-4689-b5c2-c1ca19e9b27c)
![Prediction1](https://github.com/user-attachments/assets/07c26d4d-be49-422a-80a5-5a8aecd0686e)
![PrediccionIA](https://github.com/user-attachments/assets/ffff9a5c-f279-4744-8267-5d2dfe63b0be)


## 🔧 Instalación y Uso
1.  Descarga el archivo `.apk` desde la sección de [Releases].
2.  Asegúrate de tener conexión a internet para cargar los datos actualizados.

---
**Autor:** Karina Yael Blanco Morales
