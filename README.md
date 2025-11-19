# Clasificación automática de aves europeas por su canto mediante aprendizaje automático

<img width="800" height="300" alt="Clasificación de aves por su canto" src="https://github.com/user-attachments/assets/2cc4e706-cf52-4f10-b51d-7e1c8b2d2b19" />

# Autores
Juan David León Delgado, Alejandro Velandia Gelvez, Jonathan Parra

# Objetivo
Desarrollar modelos de aprendizaje automático que permitan clasificar especies de aves europeas a partir de sus cantos, utilizando características acústicas extraídas como MFCC y contraste espectral, con el fin de apoyar la biología, la preservación ambiental y el monitoreo de ecosistemas.

# Datasets Utilizados
## European Male Bird Song Dataset Refined
El dataset se encuentra disponible en [European Male Bird Song Dataset Refined](https://www.kaggle.com/datasets/radgeni/european-male-bird-song-dataset-refined) y recopila grabaciones de cantos de aves europeas (Este dataset es una versión más limpia y utilizable de [European Male Bird Song Dataset](https://www.kaggle.com/datasets/sete39/european-male-bird-song-dataset/data). El conjunto incluye aproximadamente 13,800 audios en formato `.mp3` correspondientes a 32 especies, con un marcado desbalance en la cantidad de registros por especie.

Los audios en este dataset fueron segmentados en fragmentos de 10 segundos y cada fragmento conserva la metadata original. Además, fueron procesados para extraer características acústicas como **MFCC** y **Spectral Contrast**, que se almacenan en un archivo `.csv`.
 

# Modelos Utilizados
Random Forest Classifier:
Uso: Se utilizó para probar su rendimiento en la clasificación de la gravedad del accidente.
Explicación: Es un clasificador de ensamble que construye múltiples árboles de decisión durante el entrenamiento y genera una salida que es la moda de las clases (clasificación) o la predicción promedio (regresión) de los árboles individuales.
Redes Neuronales Secuenciales (TensorFlow/Keras):
Uso: Se utilizaron varias configuraciones de redes neuronales para la clasificación de la gravedad del accidente.
Explicación: Son modelos de aprendizaje profundo compuestos por capas apiladas. Las capas densas (Dense) conectan cada neurona de una capa con cada neurona de la siguiente capa. Se utilizan funciones de activación (relu, softmax) para introducir no linealidad.
Técnicas Utilizadas:
Se utilizaron técnicas de acceso a datos, carga y visualización, análisis de desbalanceo y preprocesamiento que incluyó eliminación de columnas, imputación, codificación y manejo del desbalanceo con SMOTE. Se realizó reducción de dimensionalidad con PCA, división de datos, normalización, codificación de la variable objetivo y se aplicaron técnicas de regularización y pesos de clase para el entrenamiento de modelos evaluados con classification reports.

# Enlaces
Video YouTube: https://youtu.be/Oka2kSBKbQg
Notebook Funcional: https://colab.research.google.com/drive/15WYAKmIiJDjzWOy6NtofHEFof_Xmf7NL?usp=drive_link
Presentación en Canva: https://www.canva.com/design/DAGpTEDHoOI/U_g7GzT2dzVxaH0xHIAIMQ/edit?utm_content=DAGpTEDHoOI&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
