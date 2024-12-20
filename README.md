# EvaluacionDocente
Aplicación de NLP (Análisis de Sentimiento y Clustering)

Este proyecto realiza un análisis sobre la evaluación docente utilizando diferentes técnicas de procesamiento de datos. A continuación se encuentran los pasos para ejecutar el código y entender la estructura de los archivos.

## Requerimientos

1. Clona este repositorio a tu máquina local.
2. Para instalar los requerimientos necesarios, ejecuta el siguiente comando:

   ```bash
   pip install -r requirements.txt


Modelos adicionales que se deben instalar en la terminal:
   ```bash
   nltk.download('vader_lexicon')
   nltk.download('stopwords')
   nltk.download('wordnet')
   nltk.download('omw-1.4')

   python -m spacy download es_core_news_sm
   ```

## Archivos en el repositorio
- EvaluacionDocente.ipynb: Este es el archivo principal que contiene el código para el análisis. Abre este archivo en un entorno Jupyter Notebook o cualquier plataforma compatible para ejecutar el código.
- Dirty_Evaluation_Data.csv: Conjunto de datos principal utilizado para realizar el análisis.
- es.txt: Diccionario complementario en español de la fuente lorenbrichter/Words.
- evaluacion_docente.pbix: Archivo que contiene la construcción del dashboard a partir del output generado por el código.
- real_comments_with_pca_and_clusters.csv: Archivo generado por el código que contiene los resultados del análisis, utilizado para la creación del dashboard.

## Dashboard Interactivo

El resultado final del análisis está disponible en un dashboard interactivo de Power BI. Puedes verlo en el siguiente enlace: https://app.powerbi.com/view?r=eyJrIjoiNWZlMWU0MDUtYzczMC00Yzk5LWI3YmYtOWZkZTVmMmM4MzU2IiwidCI6ImFlNTI1NzU3LTg5YmEtNGQzMC1hMmY3LTQ5Nzk2ZWY4YzYwNCIsImMiOjR9


## Cómo ejecutar el código
Asegúrate de tener todos los requerimientos instalados con pip install -r requirements.txt y los modelos adicionales.
Ejecuta el notebook EvaluacionDocente.ipynb en tu entorno preferido.
El código generará un archivo CSV con los resultados procesados: real_comments_with_pca_and_clusters.csv.
Abre el archivo evaluacion_docente.pbix en Power BI Desktop para crear el dashboard interactivo.

