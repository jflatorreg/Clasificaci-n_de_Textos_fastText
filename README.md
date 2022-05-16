# Clasificación de Textos fastText
Se presenta el flujo de trabajo para la calsificaciòn de textos no sipervisada usando fastText.

## Extracción de Datos. 
Se hace por medio de la API de Twitter.
## Procesamiento de texto. 
Se debe limpiar los tweets para obtener el texto de Interés.
## Entrenamiento del modelo. 
Se entrena el modelo fastText con el texto anterior.
## Clasificación del texto. 
Con los embeddings encontrados se reduce su dimensión y se clasifica cada tweet.
