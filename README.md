# Clasificación de aves europeas por su canto mediante aprendizaje automático

<img width="800" height="300" alt="Clasificación de aves por su canto" src="https://github.com/user-attachments/assets/2cc4e706-cf52-4f10-b51d-7e1c8b2d2b19" />

# Autores
Juan David León Delgado, Alejandro Velandia Gelvez, Jonathan Philippe Parra Duran

# Objetivo
Desarrollar modelos de aprendizaje automático que permitan clasificar especies de aves europeas a partir de sus cantos, utilizando características acústicas extraídas como MFCC y contraste espectral, con el fin de apoyar la biología, la preservación ambiental y el monitoreo de ecosistemas.

# Datasets Utilizados
**European Male Bird Song Dataset Refined**

El dataset se encuentra disponible en [European Male Bird Song Dataset Refined](https://www.kaggle.com/datasets/radgeni/european-male-bird-song-dataset-refined) y recopila grabaciones de cantos de aves europeas (Este dataset es una versión más limpia y utilizable de [European Male Bird Song Dataset](https://www.kaggle.com/datasets/sete39/european-male-bird-song-dataset/data)). El conjunto incluye aproximadamente 13,800 audios en formato `.mp3` correspondientes a 32 especies, con un marcado desbalance en la cantidad de registros por especie.

Los audios en este dataset fueron segmentados en fragmentos de 10 segundos y cada fragmento conserva la metadata original. Además, fueron procesados para extraer características acústicas como **MFCC** y **Spectral Contrast**, que se almacenan en un archivo `.csv`.
 

# Modelos Utilizados
**Supervisados:**
- Decision Tree (DT)
- Gaussian Naive Bayes (GNB)
- Random Forest (RF)
- Support Vector Machine (SVM)
- Deep Neural Networks (DNN)

**No Supervisados:**

**Clustering**
- KMeans
- DBSCAN

**Reducción de dimensionalidad**
- PCA
- t-SNE

# Enlaces
- Video: [YouTube](https://youtu.be/WoPHjOwUyJ8)
- Notebook Funcional: [Google Colab](https://colab.research.google.com/drive/1G8ajsx4lW8sxGhX07YWeG1_n2t07iMZW?usp=sharing)
- Presentación: [Diapositivas](https://www.canva.com/design/DAGzFRH-Qrw/RVNDT-cal2OIqldD3bCVLg/view?utm_content=DAGzFRH-Qrw&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h9955d1c294)
- Repositorio: [github](https://github.com/JuanLeon04/ClasificacionDeAves)
