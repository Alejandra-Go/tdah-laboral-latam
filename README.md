# TDAH laboral LATAM: análisis exploratorio de datos con Python

Análisis exploratorio de la relación entre el TDAH y la situación laboral a partir de una encuesta realizada a 64 participantes de Latinoamérica.

El proyecto abarca el proceso completo de preparación y análisis de los datos: anonimización, Data Profiling, limpieza, transformación, validación de calidad, análisis exploratorio y visualización de resultados con Python.

> **Nota:** Los resultados corresponden únicamente a la muestra analizada y no son representativos de toda la población latinoamericana.

## Objetivo

Explorar la relación entre variables relacionadas con el TDAH y la situación laboral en una muestra de personas adultas de Latinoamérica, identificando patrones descriptivos relacionados con diagnóstico, tipo de TDAH, situación laboral, dificultades experimentadas y apoyos laborales.

## Preguntas de análisis

1. ¿Qué proporción de participantes reporta diagnóstico formal de TDAH?
2. ¿Qué tipos de TDAH aparecen con mayor frecuencia?
3. ¿Cuál es la distribución de la situación laboral?
4. ¿Qué dificultades laborales se reportan con mayor frecuencia?
5. ¿Qué proporción recibe apoyos o adaptaciones laborales?
6. ¿Qué patrones descriptivos se observan al relacionar el diagnóstico y el tipo de TDAH con la situación laboral, las dificultades y los apoyos laborales?

## Dataset

Los datos provienen de una encuesta propia realizada mediante Microsoft Forms.

- **Participantes:** 64
- **Países representados:** México, Argentina y Guatemala
- **Variables originales:** 17
- **Variables después de la anonimización:** 10
- **Tipo de información:** datos demográficos, información relacionada con TDAH, situación laboral, dificultades laborales y apoyos o adaptaciones.

La muestra presenta una fuerte concentración geográfica en México (93.8 %), por lo que los resultados no deben interpretarse como representativos de Latinoamérica.

### Privacidad de los datos

Por motivos de privacidad, el archivo original con las respuestas de los participantes **no se publica en este repositorio**.

Antes del análisis se eliminaron identificadores directos, metadatos de la encuesta y respuestas que pudieran contener información personal. Las variables originales necesarias para el análisis se conservaron siempre que fue posible para mantener la trazabilidad de las transformaciones realizadas.

## Metodología

El análisis se desarrolló en las siguientes etapas:

1. **Extracción de datos:** carga del archivo original en formato Excel.
2. **Estandarización y anonimización:** eliminación de información identificable y conservación de las variables necesarias para el análisis.
3. **Data Profiling:** revisión de dimensiones, tipos de datos, valores faltantes, duplicados y cardinalidad.
4. **Limpieza y preparación:** normalización de variables categóricas, conversión de variables numéricas y tratamiento de respuestas no estructuradas.
5. **Ingeniería de variables:** creación de variables derivadas para facilitar el análisis sin modificar las respuestas originales.
6. **Codificación temática:** clasificación exploratoria de las dificultades laborales reportadas mediante respuestas abiertas.
7. **Validación de calidad:** revisión de valores faltantes, tipos de datos y consistencia de las variables transformadas.
8. **Análisis exploratorio de datos (EDA):** análisis univariado y exploración descriptiva de relaciones entre variables.
9. **Visualización:** elaboración de gráficas para comunicar los principales patrones encontrados.

## Tecnologías utilizadas

- Python
- pandas
- Matplotlib
- Google Colab
- Microsoft Excel
- Microsoft Forms

## Principales hallazgos

- **60.9 %** de los participantes reportó contar con un diagnóstico formal de TDAH.
- **79.7 %** fue clasificado dentro del grupo que se encontraba trabajando al momento de responder la encuesta.
- **90.6 %** reportó haber experimentado alguna dificultad laboral.
- Entre las 37 respuestas con suficiente detalle para realizar una clasificación temática, las dificultades identificadas con mayor frecuencia fueron:
  - gestión del tiempo y puntualidad: **32.4 %**
  - atención y concentración: **24.3 %**
  - organización y planificación: **21.6 %**
- **43.2 %** de las 37 respuestas con detalle temático presentó dificultades correspondientes a dos o más categorías.
- Solo **4.7 %** de los participantes reportó recibir algún apoyo o adaptación laboral.

Los análisis entre variables mostraron diferencias descriptivas entre algunos grupos; sin embargo, debido al tamaño reducido y desigual de las categorías, **no es posible establecer relaciones causales ni concluir que un diagnóstico o tipo determinado de TDAH esté asociado con una mayor o menor probabilidad de encontrarse trabajando**.

## Limitaciones

El análisis presenta varias limitaciones que deben considerarse al interpretar los resultados:

- La muestra está conformada por únicamente 64 participantes.
- Existe una fuerte concentración geográfica en México.
- La información fue autorreportada.
- Algunos grupos utilizados en las comparaciones contienen pocos participantes.
- La clasificación temática de las dificultades laborales se realizó de manera exploratoria a partir de respuestas abiertas y no corresponde a una escala clínica validada.

Por estas razones, los resultados permiten identificar patrones dentro de la muestra, pero no pueden generalizarse a toda la población adulta con TDAH en Latinoamérica.

## Trabajo futuro

Como continuación del proyecto sería recomendable:

- ampliar el tamaño y diversidad geográfica de la muestra;
- incorporar variables relacionadas con las condiciones laborales;
- utilizar instrumentos estandarizados para evaluar las dificultades asociadas con el TDAH;
- profundizar en el conocimiento, acceso y utilización de apoyos y adaptaciones laborales;
- explorar las estrategias utilizadas para gestionar dificultades relacionadas con atención, organización y gestión del tiempo.

## Notebook

El análisis completo se encuentra en:

`tdah_laboral_latam_eda.ipynb`

El notebook documenta las decisiones de limpieza y transformación, las validaciones realizadas, el análisis exploratorio, las visualizaciones y la interpretación de los resultados.

## Autora

**Alejandra González Madrid**

Estudiante de Ingeniería en Sistemas Computacionales con interés en análisis de datos, calidad de datos y automatización.

Proyecto desarrollado como parte de mi portafolio profesional.
