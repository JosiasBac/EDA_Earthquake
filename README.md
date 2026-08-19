# 🌊 Análisis Exploratorio: Factores de Riesgo en la Generación de Tsunamis

## 🎯 Objetivo del Proyecto
Analizar un conjunto de datos sísmicos globales (782 eventos de alta intensidad) para identificar qué características físicas y geográficas determinan la generación de un tsunami. El objetivo es sentar las bases analíticas para un futuro sistema predictivo de alerta temprana, superando el enfoque tradicional basado únicamente en la magnitud.

## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** Python
* **Librerías de Análisis:** Pandas, NumPy
* **Librerías de Visualización:** Matplotlib, Seaborn
* **Entorno de Trabajo:** VS Code / Jupyter Notebooks

## 💡 Principales Hallazgos (Key Insights)
1. **La paradoja de la magnitud:** Terremotos de igual magnitud (mediana de 6.9) tienen probabilidades similares de generar o no un tsunami; usar solo la escala de Richter genera falsos positivos.
2. **Puntos ciegos de detección:** Existe una fuerte correlación negativa (-0.60) entre la alerta de tsunami y el número de estaciones sísmicas terrestres, indicando que los eventos más peligrosos ocurren en fosas oceánicas con baja cobertura de sensores.
3. **Umbral de profundidad:** El riesgo de tsunami es drásticamente mayor en sismos superficiales (profundidad inferior a 100 km), donde la energía deforma el lecho marino directamente.

## 📈 Próximos Pasos Estratégicos
* Desarrollar un modelo de *Machine Learning* de clasificación binaria (ej. Regresión Logística o Random Forest) que evalúe el riesgo en tiempo real.
* Integrar datos batimétricos y de boyas oceánicas para complementar el déficit de las estaciones terrestres.

## 🚀 Cómo Ejecutar este Proyecto
1. Clonar el repositorio: `git clone https://github.com/JosiasBac/EDA_Earthquake`
2. Instalar dependencias: `pip install -r requirements.txt`
3. Ejecutar el análisis: Abrir `notebooks/01_eda_limpieza_analisis.ipynb` en tu entorno preferido.