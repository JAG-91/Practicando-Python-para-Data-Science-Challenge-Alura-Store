
# Análisis de Datos de Tiendas - Proyecto de Ciencia de Datos

## Descripcion del Proyecto

Este proyecto realiza un analisis exhaustivo de datos comerciales de cuatro tiendas diferentes con el objetivo de determinar cual representa la mejor oportunidad de negocio para el Sr. Juan. El analisis incluye multiples dimensiones como ingresos, categorias de productos, satisfaccion del cliente, costos de envio y distribucion geografica.

## Objetivo

Determinar cual tienda ofrece el mejor entorno para que el Sr. Juan venda sus productos, basandose en un analisis integral de:
- Ingresos totales
- Ventas por categoria
- Calificacion promedio de clientes
- Productos mas vendidos
- Costos de envio
- Distribucion geografica

## Estructura del Proyecto

challenge-data-science/
|

├── notebooks/

|   └── analisis_completo.ipynb

|

├── src/

|   ├── analisis_ingresos.py

|   ├── analisis_categorias.py

|   ├── analisis_calificaciones.py

|   ├── analisis_productos.py

|   ├── analisis_costos_envio.py

|   └── analisis_geografico.py

|

├── data/

|   ├── tienda_1.csv

|   ├── tienda_2.csv

|   ├── tienda_3.csv

|   └── tienda_4.csv

|

├── visualizaciones/

|   ├── ingresos_por_tienda.png

|   ├── ventas_por_categoria.png

|   ├── calificaciones.png

|   ├── productos_populares.png

|   ├── costos_envio.png

|   └── mapas_calor_geograficos.png

|

├── requirements.txt

├── README.md

└── informe_final.pdf


## Instalacion

### Requisitos Previos
- Python 3.8 o superior
- Jupyter Notebook (opcional)
- Acceso a internet para cargar datos desde GitHub

### Instalacion de Dependencias

# Clonar el repositorio
git clone https://github.com/JAG-91/Practicando-Python-para-Data-Science-Challenge-Alura-Store.git
cd Practicando-Python-para-Data-Science-Challenge-Alura-Store

# Crear entorno virtual (recomendado)
python -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate

# Instalar dependencias
pip install -r requirements.txt

### Dependencias Principales
pandas>=1.5.0
numpy>=1.21.0
matplotlib>=3.5.0
seaborn>=0.11.0
scipy>=1.7.0

## Ejecucion del Proyecto

Jupyter Notebook
# Iniciar Jupyter Notebook
jupyter notebook notebooks/AluraStoreLatam.ipynb

## Analisis Realizados

### 1. Analisis de Ingresos
- Calculo de ingresos totales por tienda
- Generacion de graficos de barras y torta
- Ranking de tiendas por ingresos

### 2. Analisis de Categorias
- Ventas por categoria de productos
- Comparacion cruzada entre tiendas
- Identificacion de categorias lideres

### 3. Analisis de Calificaciones
- Calificacion promedio por tienda
- Comparacion con media general
- Identificacion de tiendas mejor y peor valoradas

### 4. Analisis de Productos
- Productos mas vendidos por tienda
- Top 10 productos generales
- Analisis de desempeno individual

### 5. Analisis de Costos de Envio
- Costo promedio por tienda
- Comparacion con media general
- Identificacion de eficiencia logistica

### 6. Analisis Geografico
- Mapas de calor por tienda
- Distribucion regional de ventas
- Analisis de cobertura geografica

## Visualizaciones Generadas

1. Graficos de Ingresos: Barras, torta y ranking
2. Ventas por Categoria: Grafico de barras agrupadas
3. Calificaciones: Barras con linea de tendencia
4. Productos Populares: Graficos de barras horizontales
5. Costos de Envio: Barras con analisis de variacion
6. Mapas Geograficos: 1 mapa de calor individuales por tienda

## Resultados Clave

### Ingresos Totales
- Tienda 1: $1,150,880,400.00 (Maximo)
- Tienda 2: $1,116,343,500.00
- Tienda 3: $1,098,019,600.00
- Tienda 4: $1,038,375,700.00

### Calificaciones Promedio
- Tienda 3: 4.05/5.00 (Maximo)
- Tienda 2: 4.04/5.00
- Tienda 4: 4.00/5.00
- Tienda 1: 3.98/5.00 (Minimo)

### Recomendacion Final
Tienda 3 es la recomendacion optima debido a su:
- Excelente calificacion de clientes (4.05/5.00)
- Liderazgo en categoria de muebles (499 ventas)
- Eficiencia en costos de envio ($24,805.68)
- Equilibrio entre calidad y desempeno comercial

## Problemas Comunes y Soluciones

### Problema: Datos faltantes en coordenadas geograficas
Solucion: El codigo incluye manejo de errores y visualizacion alternativa

### Problema: Nombres de columnas inconsistentes
Solucion: Implementacion de busqueda flexible de columnas

### Problema: Diferentes escalas de datos
Solucion: Normalizacion automatica en visualizaciones

## Salidas del Proyecto

- Visualizaciones: 6 graficos en formato PNG
- Datos procesados: Archivos CSV con resultados agregados
- Informe ejecutivo: Resumen de hallazgos clave
- Recomendacion tecnica: Justificacion basada en datos

## Contribuidores

- Autor Principal: Julián Alejandro Gomez 
- Revisor: Julián Alejandro Gomez 


## Contacto

Para preguntas o sugerencias:
- Email: julian.alejandro@live.com.ar
- GitHub: JAG-91

Gracias por revisar este proyecto de analisis de datos!
