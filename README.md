# Clasificación de Textos fastText
Se presenta el flujo de trabajo para la calsificaciòn de textos no sipervisada usando fastText.

## 1. Extracción de Datos. 
Se hace por medio de la API de Twitter.
## 2. Procesamiento de texto. 
Se debe limpiar los tweets para obtener el texto de Interés.
## 3. Entrenamiento del modelo. 
Se entrena el modelo fastText con el texto anterior.
## 4. Clasificación del texto. 
Con los embeddings encontrados se reduce su dimensión y se clasifica cada tweet.
