# 📊 Telecom X - Análisis de Evasión de Clientes (Churn)

¡Desafío de Data Science completado! 🚀 Este proyecto analiza los factores que influyen en la pérdida de clientes de una empresa de telecomunicaciones, utilizando técnicas de ETL y Análisis Exploratorio de Datos (EDA).

## 📝 Resumen de Hallazgos (Insights Clave)
A través del análisis con Python y Seaborn, identificamos puntos críticos para el negocio:
* **Contrato Crítico:** El **42.71%** de los clientes con contrato mensual abandonan la empresa.
* **Fuga en Fibra Óptica:** Es el servicio con mayor deserción (**41.89%**), sugiriendo una revisión de calidad o precio.
* **Sensibilidad al Precio:** Los clientes que se van pagan, en promedio, **$74.44**, un 21% más que los clientes leales ($61.27).
* **Retención Temprana:** La mayoría de las cancelaciones ocurren antes de los 18 meses de antigüedad.

## 🛠️ Tecnologías Utilizadas
- **Python 3.12**
- **Pandas & NumPy** (Procesamiento de datos)
- **Matplotlib & Seaborn** (Visualización estadística)
- **Git & GitHub** (Control de versiones)
- **Google Colab** (Entorno de desarrollo)

## 📂 Estructura del Proyecto
1. **Extracción:** Carga de datos desde JSON anidado.
2. **Transformación:** Limpieza de nulos, estandarización de tipos y creación de la variable `Cuentas_Diarias`.
3. **Análisis Exploratorio (EDA):**
   - ✅ Análisis descriptivo y distribución de Churn.
   - ✅ Impacto de variables categóricas (Contrato, Género, Pago).
   - ✅ Impacto de variables numéricas (Cargos Mensuales, Antigüedad).
   - ✅ **Extra:** Matriz de correlación térmica.
4. **Informe Final:** Conclusiones estratégicas y recomendaciones para reducir la evasión.

## 🚀 Cómo ver el proyecto
Puedes abrir el archivo `.ipynb` directamente en este repositorio para ver los gráficos y las celdas de código ejecutadas.
