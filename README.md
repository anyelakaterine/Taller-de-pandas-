<img width="148" height="148" alt="image" src="https://github.com/user-attachments/assets/0ad97c2e-ee17-49a2-84a6-35837771d9e3" />


INTELIGENCIA ARTIFICIAL

TALLER DE LIBRERÍA PANDAS

CORTE II

Integrantes:

* Kelly Jhoana Mosquera Urbano
* Anyela Katerine Rentería Cuama
## Acceso al Taller de Pandas en Google Colab: https://colab.research.google.com/github/Kelly23mosquera/INVESTIGACION_PANDA-/blob/main/taller_pandas/taller.ipynb
Programa: Ingeniería de Sistemas

Universidad del Pacífico

2026



# Taller de Pandas – Análisis de Datos en Python

##  Descripción del proyecto

Este proyecto consiste en el desarrollo de un taller práctico utilizando la librería **Pandas** en Python para la manipulación, limpieza y análisis de datos.

A lo largo del notebook se realizaron diferentes procesos de transformación y exploración de datos, incluyendo la creación de nuevas columnas, cálculos matemáticos y estadísticos, así como el análisis descriptivo de la información contenida en el conjunto de datos.

El dataset utilizado contiene información relacionada con productos tecnológicos, precios, cantidades, costos de envío y categorías, permitiendo aplicar operaciones de análisis de datos de forma práctica.


# Objetivos

## Objetivo General

Aplicar técnicas de manipulación, análisis y procesamiento de datos utilizando la librería Pandas en Python para desarrollar soluciones basadas en DataFrames.

## Objetivos Específicos

- Crear y manipular DataFrames utilizando Pandas.
- Realizar exploración y análisis de conjuntos de datos.
- Aplicar operaciones matemáticas entre columnas.
- Implementar estadísticas descriptivas sobre variables numéricas.
- Realizar procesos de filtrado y organización de datos.
- Exportar resultados procesados a archivos Excel.
- 
##  Herramientas utilizadas

- Python 
- Google Colab
- Pandas 
- GitHub

## Librerías Utilizadas

**import pandas as pd**

**Descripción de la Librería**
Pandas es una biblioteca especializada en la manipulación y análisis de datos estructurados mediante DataFrames.

**Funciones Utilizadas**

* Lectura de archivos CSV
* Creación de DataFrames
* Operaciones matemáticas
* Estadística descriptiva
* Filtrado de información
* Exportación de datos



  # Dataset Utilizado
El dataset utilizado corresponde a un conjunto de datos compuesto por productos tecnológicos.

## Variables del Dataset

 **Variable**     
 
* PRODUCTO: Nombre del producto tecnológico 
* PRECIO : Precio unitario del producto 
* CANTIDAD : Cantidad disponible 
* COSTO DE ENVIO : Valor asociado al envío 
* CATEGORIA  : Clasificación del producto 


## Características del Dataset
- 60 registros
- Productos tecnológicos
- Variables numéricas y categóricas



##  Contenido del taller

En este taller se desarrollan los siguientes temas:

- Carga y exploración de datos
- Limpieza y tratamiento de datos
- Filtrado de información
- Ordenamiento de datos
- Creación de nuevas columnas
- Análisis básico de datos
- Visualización básica (si aplica)

   ## 1. Creación y Exploración del DataFrame

Durante esta etapa se realizó:

- Lectura del archivo Excel
- Creación del DataFrame
- Exploración inicial
- Identificación de tipos de datos
- Descripción estadística

## Funciones Utilizadas

**df.head()**
Muestra las primeras 5 filas del DataFrame, permitiendo visualizar la estructura inicial del conjunto de datos.

**df.tail()**
Muestra las últimas 5 filas del DataFrame para verificar la información final del conjunto de datos.

**df.shape**
Permite conocer la cantidad de filas y columnas presentes en el DataFrame.

**df.describe()**
Genera un resumen estadístico de las variables numéricas, incluyendo medidas como media, desviación estándar, valores mínimos y máximos.

**df.dtypes**
Muestra el tipo de dato de cada columna del DataFrame, facilitando la identificación de variables numéricas y categóricas.


## 2. Operaciones Matemáticas

Se generaron nuevas variables:

**Total_Venta**
Total_Venta = Precio × Cantidad

**Costo_Total**
Costo_Total = Total_Venta + Costo_Envio


## 3. Análisis Porcentual

Se calcularon:

- IVA
- Ganancia estimada
- Pérdida estimada
- Participación porcentual de ventas

## 4. Estadística Descriptiva

Se calcularon:

- Media
- Mediana
- Moda
- Desviación estándar
- Valores máximos
- Valores mínimos

  ## 5. Filtrado y Organización

Se realizaron procesos de:

- Filtrado por categoría
- Ordenamiento por ventas
- Selección de productos

## Procesos Realizados

**Limpieza de Datos**
Se eliminaron espacios innecesarios en los nombres de las columnas y se transformaron variables monetarias a formato numérico para facilitar los cálculos matemáticos.

**Transformación de Datos**
Se crearon nuevas columnas mediante operaciones aritméticas para calcular ventas totales, costos e indicadores relacionados con el análisis del dataset.

## Resultados esperados

- Comprensión del manejo de DataFrames en Pandas
- Aplicación de filtros y condiciones
- Organización y limpieza de datos
- Interpretación de resultados obtenidos

## Cómo Ejecutar el Proyecto

* Abrir el notebook en Google Colab.
* Ejecutar las celdas en orden.
* Verificar la carga correcta del dataset desde Google Sheets.
* Analizar los resultados generados en cada sección.

 ## Conclusiones
 
La librería Pandas demuestra ser una herramienta eficiente para manipular y analizar grandes volúmenes de información estructurada.

Las operaciones matemáticas permiten generar nuevas variables que enriquecen el análisis y facilitan la toma de decisiones.

La estadística descriptiva aporta indicadores clave para interpretar el comportamiento de los datos y comprender su variabilidad.

El uso de DataFrames simplifica procesos de organización, filtrado y procesamiento, haciendo más ágil el trabajo con conjuntos de datos.

Finalmente, Python ofrece un ecosistema robusto que, junto con Pandas, se convierte en un recurso esencial para proyectos de análisis de datos e inteligencia artificial.

# Integrantes

### Kelly Jhoana Mosquera Urbano
### Anyela Katerine Rentería Cuama



