# Dataset

Los datos utilizados en este proyecto provienen de una encuesta propia realizada mediante Microsoft Forms sobre TDAH y situación laboral en personas adultas de Latinoamérica.

## Disponibilidad de los datos

El archivo original de respuestas no se publica en este repositorio por motivos de privacidad.

El dataset original contiene información autorreportada y respuestas abiertas que fueron sometidas a un proceso de anonimización antes del análisis.

## Características generales

- 64 participantes.
- 17 variables originales.
- 10 variables conservadas después del proceso de anonimización.
- Países representados: México, Argentina y Guatemala.
- La muestra presenta una fuerte concentración geográfica en México.

Las variables analizadas incluyen información relacionada con:

- país;
- edad;
- escolaridad;
- diagnóstico formal de TDAH;
- edad de diagnóstico;
- tipo de TDAH;
- situación laboral;
- modalidad de trabajo;
- dificultades laborales;
- apoyos o adaptaciones laborales.

## Privacidad y anonimización

Antes del análisis se eliminaron identificadores directos y metadatos que no eran necesarios para los objetivos del proyecto.

Las variables originales necesarias para el análisis se conservaron siempre que fue posible para mantener la trazabilidad del proceso de transformación.

Las respuestas abiertas fueron utilizadas únicamente para generar variables derivadas y categorías temáticas necesarias para el análisis.

## Reproducción del análisis

El notebook `tdah_laboral_latam_eda.ipynb` solicita al usuario cargar manualmente el archivo Excel correspondiente al ejecutar el proyecto en Google Colab.

Debido a que los datos originales no se distribuyen públicamente, el notebook documenta el flujo completo de limpieza, transformación, validación y análisis, pero no incluye el archivo fuente.
