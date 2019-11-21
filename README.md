
# Proyecto 4 - Topicos Telemática
Proyecto de Big Data para la materia Tópicos Especiales en Telemática de la Universidad Eafit.

## Integrantes
```
- Cesar Augusto Cataño Loaiza - ccatano3@eafit.edu.co 
- Joan Esteban Saldarriaga Ayala - jsalda36@eafit.edu.co
```


La minería o analítica de texto, son un conjunto de modelos, técnicas, algoritmos y
tecnologías que permiten procesar texto de naturaleza NO ESTRUCTURADA.
La minería de texto (text mining) permite transformar el texto en una forma
estructurada, de tal forma que facilite una serie de aplicaciones como Búsqueda en
texto, relevancia de documentos, entendimiento natural del lenguaje (NLP), traducción
automática entre idiomas, análisis de sentimientos, detección de tópicos entre muchas
otras aplicaciones.
Quizás el procesamiento más sencillo de todos, sea el wordcount, el cual consiste en
determinar la frecuencia de la palabra por documento o por todo el dataset.

### Problema

Se tiene un conjunto de noticias en texto libre, sobre el cual se desea realizar:
 Preparación de Datos. Las noticias deben ser pre-procesadas para preparar los datos para la analítica, dentro de las sugerencias de preparación están:
  - Remover caracteres especiales (. , % ( ) ‘ “ ….
  - Remover stop-words
  - Remover palabras de longitud 1

## Data Understanding

En esta etapa se leyó el dataset en un data frame. Posteriormente se analizaron las columnas, es decir, sus tipos de datos y cuales eran las columnas útiles para nuestro caso (id, title, content). También se verificó la cantidad total de noticias y si habían campos nulos en el dataset.


### Data Cleaning

Esta etapa consiste en la limpeza de cada noticia, es decir, en la eliminación de:
Remover caracteres especiales (. , % ( ) ‘ “ ….
Remover stop-words
Remover palabras de longitud 1
Stemming / lemmatization


### DataBricks
En el siguiente link se puede encontrar la solución al problema:
- Solucion: https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/8337759845647473/3945308513270911/2324619140567075/latest.html

