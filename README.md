# analisis_conectatel
Análisis de usuario para empresa de telecomunicaciones

El proyecto inició con la integración y saneamiento de datos provenientes de tres diferentes datasets, aplicando procesos de validación y estandarización de tipos para garantizar la integridad de la muestra. Posteriormente, se realizó un análisis exploratorio (EDA) para construir perfiles estadísticos de consumo y detectar comportamientos atípicos mediante técnicas visuales y analíticas. Finalmente, se ejecutó una segmentación avanzada de clientes basada en criterios demográficos y patrones de uso, lo que permitió visualizar disparidades entre grupos y extraer insights estratégicos orientados a la toma de decisiones comerciales.
# Guía de Reproducción - Análisis ConnectaTel

## Requisitos
- Python 3.8+
- pandas 1.3+
- matplotlib 3.5+
- seaborn 0.11+
- numpy 1.21+

## Datos necesarios
- Archivo: `connectatel_users.csv`
- Ubicación: carpeta `data/`
- Formato: CSV con columnas user_id, edad, minutos_llamadas, etc.

## Pasos de ejecución
1. Ejecutar celdas 1-10: Importación de librerías y carga de datos
2. Ejecutar celdas 11-30: Análisis exploratorio inicial
3. Ejecutar celdas 31-50: Limpieza y transformación de datos
4. Ejecutar celdas 51-70: Creación de variables categóricas
5. Ejecutar celdas 71-80: Visualizaciones finales

## Tiempo estimado: 5-10 minutos

## Ejecutar en Google Colab

1. Ve a: https://colab.research.google.com/
2. Haz clic en "Archivo" → "Abrir notebook"
3. Selecciona la pestaña "Subir" 
4. Arrastra tu archivo .ipynb o haz clic en "Elegir archivos"
5. Una vez abierto, ejecuta las celdas con Shift + Enter
