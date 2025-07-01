# Análisis de los Premios Grammy 🎤

Este proyecto realiza un análisis exhaustivo de los datos de los Premios Grammy desde 1958 hasta 2024. Utiliza bibliotecas de Python como Pandas, NumPy, Matplotlib y Seaborn para explorar tendencias, patrones y insights interesantes sobre las nominaciones y premiaciones a lo largo de los años.

## Índice 📋

- [Introducción](#introducción)
- [Dataset](#dataset)
- [Análisis Realizado](#análisis-realizado)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Cómo Ejecutar el Proyecto](#cómo-ejecutar-el-proyecto)
- [Resultados Principales](#resultados-principales)
- [Contribuciones](#contribuciones)
- [Licencia](#licencia)

## Introducción

Los Premios Grammy son uno de los eventos más importantes en la industria musical, reconocidos mundialmente por su prestigio y relevancia. Este proyecto tiene como objetivo analizar los datos históricos de los Grammy para responder preguntas clave como:

- ¿Cómo ha evolucionado el número de premios y nominaciones a lo largo del tiempo?
- ¿Cuáles son los artistas más galardonados en la historia?
- ¿Qué géneros musicales tienen más probabilidades de ganar?
- ¿Existen tendencias en la cantidad de premios consecutivos otorgados a ciertos artistas?

## Dataset

El dataset utilizado en este análisis contiene información detallada sobre las nominaciones y premiaciones de los Grammy desde 1958 hasta 2024. Incluye columnas como:

- **Year**: Año de la ceremonia.
- **Ceremony**: Número de la ceremonia.
- **Award ID**: Identificador único del premio.
- **Award Type**: Tipo de premio (por ejemplo, "Work", "Album").
- **Award Name**: Nombre de la categoría del premio.
- **Work**: Detalle del trabajo nominado.
- **Nominee**: Artista o grupo nominado.
- **Winner**: Indica si el nominado ganó el premio (`True` o `False`).

Además, se utiliza un dataset suplementario que incluye información adicional sobre productores destacados.

## Análisis Realizado

El análisis realizado incluye los siguientes puntos clave:

1. **Distribución de premios y nominaciones por año**:
   - Se explora cómo ha cambiado el número total de premios y nominaciones a lo largo de los años.
   - Se busca identificar si hay años con mayor actividad en términos de premiaciones.

2. **Artistas más premiados**:
   - Se identifican los artistas que han obtenido más premios en la historia de los Grammy.
   - Se analizan patrones de dominancia en ciertos géneros o décadas.

3. **Categorías con más nominaciones**:
   - Se determina cuáles categorías tienen más competencia basándose en el número de nominaciones recibidas.
   - Se evalúa si esta distribución ha cambiado con el tiempo.

4. **Género vs Ganadores**:
   - Se clasifica cada premio según su género musical (Rock, Pop, Jazz, Clásico, etc.).
   - Se analiza cuáles géneros tienen más probabilidades de ganar y cómo ha evolucionado esta representación a lo largo del tiempo.

5. **Premios consecutivos**:
   - Se identifican artistas que han ganado premios en años consecutivos.
   - Se estudian patrones de éxito continuo en la carrera de algunos artistas.

## Tecnologías Utilizadas

- **Python**: Lenguaje de programación principal.
- **Pandas**: Para manipulación y análisis de datos.
- **NumPy**: Para operaciones numéricas.
- **Matplotlib**: Para visualización de gráficos.
- **Seaborn**: Para gráficos estéticos y estadísticos.

## Cómo Ejecutar el Proyecto

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/tu-usuario/analisis-grammy.git 
   cd analisis-grammy