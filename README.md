# TAAD
Técnicas Avanzadas de Análisis de Datos -  Sistemas recomendadores

En el proyecto se incluyen varios ficheros. 

El archivo con extensión .pynb es el código implementado en la platadorma de Google Colab. Se ha decidido emplear Colab debido a la facilidad que supone disponer de un entorno de desarrollo en la nube. Al utilizar Colab, e incluir todo el código en un mismo archivo, la ejecución es secuencial. Cada ejecución que se hace va realizando acciones (carga de datos, preprocesado, cálculo de campos, etc. ) que son necesarias para pasos posteriores. Todo el código desarrollado está descrito y comentado en los archivos .ipynb y .pdf.

El archivo PDF es una descripción completa del proyecto, donde se explica el procedimiento, los pasos realizados y la conclusión obtenida. 

Los dos archivos .txt incluyen la colección de documentos a recomendar (data.txt) y el documento seleccionado como favorito por parte del usuario (favorito.txt). Este último documento, incluido en favorito.txt, es el que se introduce al final de la colección, y el cual es comparado con el coseno de similitud para conocer los documentos recomendables de la colección.
