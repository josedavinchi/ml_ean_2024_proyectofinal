
# Prueba Final del Proyecto: Predicción de Obesidad a partir de Hábitos de Vida

El objetivo del proyecto es aplicar técnicas de aprendizaje no supervisado para realizar una agrupación, asociación y reducción de dimensionalidad de los datos, con el fin de descubrir patrones y estructuras ocultas sin el uso de etiquetas (como la variable "NObeyesdad"), y adicional, no utilizar las variables de peso y altura para encontrar patrones que nos permitan identificar que otras variables permiten determinar el IMC y el nivel de obesidad de la persona. En un segundo momento utilizaremos aprendizaje supervisado para entrenar nuevamente el modelo, para evaluar la eficiencia y confiabilidad del modelo.

## Tabla de Contenidos
- [Descripción](#descripción)
- [Estructura del proyecto](#Estructura)
- [Tecnologías utilizadas](#tecnologías-utilizadas)
- [Instalación y despliegue](#instalación)
- [Integrantes](#Integrantes)

## Descripción

Este proyecto es una aplicación que demuestra cómo funcionan y se aplican dos conceptos clave dentro de Machine Learning, Aprendizaje Supervisado y No supervisado para determinar el nivel de obesidad de una persona a partir de los datos suministrados y aplicando diferentes técnicas/metodologías como: (Reducción de dimensionalidad, definición de clústeres, evaluación de las variables, selección de modelo, reentrenamiento y visualización).
Algunas de las bibliotecas/librerias que se utilizaron fueron:
- Pandas  
- numpy  
- matplotlib  
- seaborn  
- sklearn  
- xgboost  
- shap

## Estructura del proyecto
### 1. **Cuadernos/**
La carpeta contiene el notebook que se utilizo para la realización del ejercicio, en el se encuentra los experimentos, análisis de datos, visualizaciones y desarrollo de los modelos descritos en el proyecto.
### 2. **Datos/**
En esta carpeta se podrá encontrar los datos del repositorio de ML, el cual se utilizo para en análisis respectivo.
### 3. **Documentacion/**
Contiene información adicional sobre el proyecto, brindando una información mas técnica y descripción de las metodologías aplicadas.
### 4. **README/**
Archivo que contiene una información mas general del proyecto, el cual explica de manera concisa como esta construido el proyecto y como realizar el respectivo despliegue
### 5. **pyproject.toml/**
Archivo de configuración para proyectos de python, su función es especificar las dependencias y configuraciones con las cuales se realizo el despliegue del proyecto.

## Tecnologías utilizadas
- **Python**: Versión 3.11.
- **Poetry**: Gestión de dependencias.
- **Pandas**: Manipulación de datos .
- **Numpy**: Operaciones matemáticas dentro de los datos.
- **matplotlib**: Visualización de datos.
- **seaborn**: Visualización de relaciones estadísticas entre variables.
- **sklearn**: Creacion y evaluacion de modelos de ML para entrenar modelos.
- **xgboost**: Construccion de modelos de manera secuencial para generar modelos de alto rendimiento.
- **shap**: Biblioteca para mostrar los resultados de los modelos de ML e interpretación de modelos complejos

## Instalación
### Prerrequisitos
 Asegurarse de tener instalado:
 - Python 3.11 el cual es la version actualmente mas estable
 - Poetry (Para gestionar dependencias y versionamiento)

### Pasos de instalación
1. Se recomienda la creación de un entorno nuevo para el despliegue del proyecto:
```bash
conda create -n ml_ean_2024
```
2. Activamos el entorno
```bash
conda activate ml_ean_2024
```
3. Si ya tienes instalado la aplicación Git, se debe clonar el repositorio en la carpeta que hayas creado:
```bash
git clone
```

4. Debido a que estamos en un entorno nuevo, debemos instalar el ipykernel(Kernel de python) y el poetry
```bash
pip install ipykernel poetry
```
### Despliegue del proyecto
Dirigirse a la carpeta donde se tiene el proyecto clonado y ejecutar lo siguiente:
```bash
poetry install
```
En caso de que la versión de python del entorno sea diferente al del proyecto ejecutar lo siguiente para solucionar las dependencias:
```bash
poetry lock
```
## Integrantes
- Báez Bermúdez, Cristian David (Estudiante de la especialización en machine learning)
- Rodriguez  Simmonds, Santiago (Estudiante de la especialización en machine learning)
- Rodríguez Díaz, Germán Alonso (Estudiante de la especialización en machine learning)
- Mariño Florez,  David José (Estudiante de la especialización en machine learning)


