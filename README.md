# NLP & DeepLearning Modulo III Stopwords Entrega
# Práctica: Implementación y Evaluación de Eliminación de Stopwords con spaCy

Este notebook Jupyter demuestra el proceso de preprocesamiento de texto, específicamente la **eliminación de stopwords**, utilizando la biblioteca `spaCy` en español. Aborda la importancia de esta técnica en el Procesamiento del Lenguaje Natural (PLN) para limpiar datos textuales y prepararlos para análisis posteriores.

## Contenido del Notebook

El notebook está estructurado en los siguientes pasos:

1.  **Instalación y Carga de Modelo**: Configuración del entorno, instalación de `spaCy` y carga del modelo de lenguaje español `es_core_news_sm`.
2.  **Carga y Preparación de Datos**: Descarga de un dataset de reseñas de Amazon utilizando `kagglehub` y carga de los datos en un DataFrame de pandas. Se realiza una inspección inicial del texto.
3.  **Tokenización Básica**: Aplicación de la tokenización de spaCy para segmentar el texto de una reseña de ejemplo en unidades más pequeñas (tokens).
4.  **Eliminación de Stopwords Estándar**: Filtrado de tokens utilizando la lista predefinida de stopwords de `spaCy` para el español.
5.  **Personalización de Stopwords**: Modificación de la lista de stopwords para adaptarla a un contexto específico. Se añaden y eliminan palabras para demostrar la flexibilidad del proceso.
6.  **Comparación de Frecuencias**: Análisis de cómo la frecuencia de los términos más comunes cambia después de aplicar la eliminación de stopwords estándar y personalizada. Se utilizan `Counter` para mostrar las 10 palabras más frecuentes en cada etapa.
7.  **Reflexión Final: Impacto de la Limpieza**: Discusión sobre la importancia y el impacto de la eliminación de stopwords en el preprocesamiento de texto para tareas de PLN, como la reducción de ruido y la mejora del enfoque en términos clave.

## Cómo Ejecutar el Notebook

Para ejecutar este notebook, necesitarás tener instalado Jupyter o Google Colab. Sigue estos pasos:

1.  Clona este repositorio.
2.  Abre el notebook en tu entorno preferido (Jupyter Lab, Jupyter Notebook, Google Colab).
3.  Ejecuta las celdas en orden. Asegúrate de que las instalaciones de `spaCy` y la descarga del modelo de español se completen correctamente.

## Requisitos

*   Python 3.x
*   `pandas`
*   `spacy`
*   `kagglehub` (para la descarga automática del dataset)

## Autor
Riveros Loboso Rodolfo Gabriel

[Especifica la licencia si aplica, por ejemplo, MIT License]
