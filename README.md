# Laboratorio 2 - Inteligencia Artificial

Este repositorio contiene una colección de scripts en Python para diversos ejercicios de estadística y aprendizaje automático, incluyendo simulaciones de lanzamiento de moneda, análisis de distribuciones de probabilidad, pruebas de la Ley de Benford y reconstrucción de imágenes usando PCA.

## Autores
- Fabiola Contreras
- Diego Duarte
- Maria Jose Villafuerte

## Dependencias
```python
numpy
matplotlib
seaborn
scipy
pandas
scikit-learn
Pillow
```

## Estructura del Proyecto

El proyecto consta de seis secciones principales:

### 1. Simulación de Lanzamiento de Moneda
- Implementa simulación de distribución geométrica para lanzamientos de moneda
- Visualiza distribuciones de probabilidad para diferentes probabilidades de éxito (p = 0.2, 0.5, 0.8)
- Funciones:
  - `throw_coin(p)`: Simula lanzamientos de moneda con probabilidad dada
  - `plot_density(data, p, ax)`: Grafica la distribución de densidad de probabilidad

### 2. Comparación de Muestras
- Implementa la función de distribución acumulada empírica (ECDF)
- Compara dos muestras usando varios gráficos estadísticos:
  - Gráficos de densidad
  - Gráficos de función de distribución acumulada
  - Gráficos PP (Probabilidad-Probabilidad)
  - Gráficos QQ (Cuantil-Cuantil)
- Incluye prueba de Kolmogorov-Smirnov para comparación de distribuciones

### 3. Análisis de la Ley de Benford
- Analiza datos de áreas geográficas contra la Ley de Benford
- Características:
  - Comparación de distribución teórica vs real
  - Análisis de función de densidad
  - Análisis de función de distribución
  - Gráficos PP (Probabilidad-Probabilidad)
  - Gráficos QQ (Cuantil-Cuantil)
  - Pruebas estadísticas usando Kolmogorov-Smirnov
- Utiliza datos de 'areas.csv'

### 4. Distribución Gaussiana Multivariada
- Implementa distribución gaussiana n-dimensional (d ≥ 4)
- Características:
  - Vector de medias y matriz de covarianza definidos por el usuario
  - Generación y visualización de muestras
  - Comparación de estadísticas teóricas vs muestrales

### 5. Comparación de Estaciones Meteorológicas
- Analiza datos de estaciones meteorológicas usando Análisis de Componentes Principales (PCA)
- Características:
  - Normalización de datos
  - Aplicación de PCA
  - Visualización de biplot
- Utiliza datos de 'weather.csv'

### 6. Reconstrucción de Imágenes con PCA
- Implementa compresión y reconstrucción de imágenes usando PCA
- Características:
  - Procesamiento de imágenes en escala de grises
  - Descomposición en Valores Singulares (SVD)
  - Compresión con componentes variables
  - Visualización de mapa de errores
- Funciones:
  - `cargar_y_preparar_imagen(ruta_imagen)`: Carga y prepara la imagen
  - `comprimir_imagen_pca(imagen, k)`: Realiza la compresión PCA

## Archivos de Datos Requeridos
- `areas.csv`: Contiene datos de áreas geográficas
- `weather.csv`: Contiene datos de estaciones meteorológicas
- Archivos de imagen:
  - `mariposa-monarca.jpg`
  - `cerezo-japones.jpg`
  - `monja_blanca.jpg`


