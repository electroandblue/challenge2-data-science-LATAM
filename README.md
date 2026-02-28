# Challenge 2 Data Science LATAM - Telecom X
# 📊 Telecom X - Análisis de Evasión de Clientes (Churn)

🚧 **Estado del Proyecto:** En Desarrollo 🚧

## 📝 Descripción del Proyecto
Este proyecto forma parte del desafío de **Telecom X**, una empresa de telecomunicaciones que enfrenta una alta tasa de cancelación de clientes (Churn). El objetivo es aplicar procesos de ETL y un Análisis Exploratorio de Datos (EDA) para identificar los factores clave de esta evasión y ayudar al equipo de Data Science a crear modelos predictivos.

## 🛠️ Dependencias
Para ejecutar este proyecto, necesitarás las siguientes herramientas y bibliotecas de Python:
- **Python 3.x**
- **Pandas** (Manipulación y limpieza de datos)
- **NumPy** (Operaciones numéricas)
- **Matplotlib / Seaborn** (Visualización de datos - *en desarrollo*)
- **Entorno:** Google Colab o Jupyter Notebook

## 🚀 Instalación y Cómo ejecutar el proyecto
1. Clona este repositorio en tu máquina local ejecutando en tu terminal:
   `git clone https://github.com/electroandblue/challenge2-data-science-LATAM.git`
2. Abre el archivo principal `TelecomX_LATAM.ipynb` en tu entorno preferido (se recomienda Google Colab).
3. **Paso crucial:** El código requiere el archivo de datos crudos. Asegúrate de tener el archivo `TelecomX_Data.json` a la mano.
4. Ejecuta las celdas en orden. En la sección de Extracción, el sistema te pedirá subir el archivo JSON.

## ⚠️ Posibles problemas y soluciones
- **Error `FileNotFoundError` al iniciar:** Esto ocurre si Google Colab se reinicia y pierde el archivo de datos temporales. **Solución:** Vuelve a ejecutar la celda de la fase de Extracción que activa el botón de "Elegir archivos" y vuelve a cargar el `TelecomX_Data.json`.

## 📂 Estructura del Análisis
1. **Extracción:** Carga de datos desde formato JSON.
2. **Transformación:** Limpieza de nulos, eliminación de espacios vacíos en variables clave (`Churn`), estandarización de columnas y creación de la variable calculada `Cuentas_Diarias`.
3. **Carga y Análisis:** (En proceso)
4. **Informe Final y Conclusiones:** (Pendiente)
