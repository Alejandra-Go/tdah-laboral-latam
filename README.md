# TDAH laboral LATAM: análisis de datos con Python

Proyecto de análisis exploratorio de datos sobre **TDAH (Trastorno por Déficit de Atención e Hiperactividad) y situación laboral en personas adultas**, desarrollado con Python a partir de datos recopilados mediante una encuesta en Microsoft Forms.

El proyecto forma parte de mi portafolio de análisis de datos y tiene como objetivo demostrar un flujo práctico de **extracción, limpieza, transformación, análisis exploratorio y visualización de datos**.

> **Nota sobre la muestra:** la encuesta cuenta con 64 participantes de México, Argentina y Guatemala, con una participación mayoritaria de México. Por esta razón, los resultados son descriptivos de la muestra y no pretenden ser representativos de toda la población latinoamericana.

---

## Objetivos

- Recopilar datos mediante una encuesta propia.
- Preparar y limpiar los datos para su análisis.
- Transformar variables para facilitar su procesamiento.
- Realizar un análisis exploratorio de datos (EDA).
- Generar visualizaciones para identificar patrones y tendencias.
- Preparar los datos para su posterior análisis mediante otras herramientas, como SQL.

---

## Tecnologías utilizadas

- Python
- pandas
- matplotlib
- seaborn
- Google Colab
- Microsoft Forms
- GitHub

---

## Proceso ETL

El proyecto sigue un proceso de **ETL (Extract, Transform, Load)** para preparar los datos antes del análisis.

### 1. Extracción (Extract)

Los datos fueron recopilados mediante una encuesta creada en **Microsoft Forms** sobre TDAH y situación laboral.

Las respuestas obtenidas se exportaron para posteriormente ser procesadas con Python en Google Colab.

### 2. Transformación (Transform)

La preparación y limpieza de los datos se realizó utilizando **Python y pandas**.

Entre las tareas realizadas se encuentran:

- Revisión inicial de la estructura del dataset.
- Identificación y tratamiento de valores nulos.
- Revisión de registros duplicados.
- Revisión y adecuación de tipos de datos.
- Estandarización y preparación de variables para el análisis.
- Anonimización de los datos para evitar utilizar información personal identificable.
- Creación de datasets derivados para facilitar análisis posteriores.

Después de la limpieza y transformación, los datos quedaron preparados para realizar el análisis exploratorio y las visualizaciones.

### 3. Carga (Load)

Los datos procesados se utilizaron directamente en el notebook para realizar el **análisis exploratorio de datos (EDA)** y generar visualizaciones.

Adicionalmente, a partir de los datos preparados se generaron tres datasets estructurados:

- `participantes.csv`
- `diagnostico_tdah.csv`
- `situacion_laboral.csv`

Estos datasets fueron posteriormente utilizados en un proyecto independiente de **PostgreSQL y SQL**, permitiendo continuar el análisis mediante un modelo de datos relacional.

---

## Análisis exploratorio de datos (EDA)

El análisis realizado en Python permite explorar características de la muestra relacionadas con:

- Perfil general de los participantes.
- Diagnóstico de TDAH.
- Tipo de TDAH reportado.
- Edad de diagnóstico.
- Situación laboral.
- Dificultades experimentadas en el entorno laboral.
- Apoyos o adaptaciones laborales.

Las visualizaciones permiten identificar patrones dentro de la muestra y facilitar la interpretación de los resultados.

---

## Notebook

El análisis completo se encuentra disponible en:

[`TDAH_LATAM_project_con_Python.ipynb`](TDAH_LATAM_project_con_Python.ipynb)

El notebook contiene el procesamiento de los datos, análisis exploratorio y visualizaciones desarrolladas con Python.

---

## Estructura del repositorio

```text
TDAH-laboral-LATAM/
│
├── .gitignore
├── README.md
└── TDAH_LATAM_project_con_Python.ipynb

```

---

## Continuación del proyecto: análisis con SQL

Como extensión de este proyecto, los datos procesados fueron estructurados en una base de datos relacional utilizando **PostgreSQL**.

En este segundo proyecto se aplican:

- Diseño de tablas relacionales.
- Claves primarias y foráneas.
- Consultas SQL.
- Filtros y agregaciones.
- `GROUP BY`.
- `JOIN`.
- Subconsultas.

El proyecto SQL se encuentra documentado en un repositorio independiente:

[SQL análisis TDAH: PostgreSQL y SQL](https://github.com/Alejandra-Go/sql-analisis-tdah)

---

## Consideraciones y limitaciones

- La muestra contiene 64 participantes.
- La mayoría de las respuestas provienen de México.
- Los resultados corresponden únicamente a las personas participantes de la encuesta.
- El análisis es exploratorio y descriptivo.
- Los resultados no deben interpretarse como representativos de toda la población latinoamericana ni como conclusiones clínicas sobre el TDAH.

---

## Habilidades demostradas

Este proyecto demuestra experiencia práctica en:

- Extracción y preparación de datos.
- Python para análisis de datos.
- Manipulación de datos con pandas.
- Limpieza y transformación de datasets.
- Tratamiento de valores nulos y duplicados.
- Análisis exploratorio de datos (EDA).
- Visualización de datos con matplotlib y seaborn.
- Documentación de un proceso ETL.
- Preparación de datos para análisis posterior con SQL.
- Git y GitHub para documentación de proyectos.

---

## Autora

**Alejandra González Madrid**

Estudiante de Ingeniería en Sistemas Computacionales con interés en análisis de datos, SQL, automatización y Business Intelligence.
