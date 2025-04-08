# 🤖 Clustering con K-Means en Datos Sintéticos

Este repositorio contiene un análisis completo de clustering no supervisado utilizando el algoritmo K-Means aplicado sobre un conjunto de datos sintéticos. Se evalúan diferentes valores de k usando el método del codo y la puntuación de silueta, y se visualizan los resultados mediante reducción de dimensionalidad con PCA.
👥 Autor

    David Ricardo Jiménez Núñez

📁 Contenido

    Generación de datos sintéticos con make_blobs

    Normalización de datos con StandardScaler

    Evaluación del número óptimo de clusters:

        Método del Codo (Inercia)

        Puntuación de Silueta

    Aplicación del algoritmo K-Means

    Visualización de clusters y centroides usando PCA

🔧 Requisitos

Este proyecto fue desarrollado en Google Colab y requiere las siguientes bibliotecas:

numpy
matplotlib
scikit-learn

Puedes instalarlas con:

pip install numpy matplotlib scikit-learn

▶️ Cómo ejecutar

    Clona este repositorio:

    git clone https://github.com/tu-usuario/tu-repo.git
    cd tu-repo

    Abre el notebook en Jupyter Notebook o Google Colab.

También puedes acceder directamente desde Colab:
🔗 Abrir en Google Colab
📈 Resultados

    Gráfico del método del codo para determinar k

    Gráfico de puntuación de silueta para evaluar la cohesión de los clusters

    Visualización final de los clusters con los centroides resaltados en rojo (X), tras aplicar PCA para reducción a 2D

📝 Notas

    El número óptimo de clusters se determina automáticamente con base en la mejor puntuación de silueta.

    Este proyecto es útil como base para introducirse en técnicas de clustering no supervisado y evaluación de modelos.

📚 Referencias

    Scikit-learn - KMeans

    Evaluación con Silhouette

    PCA para visualización

📝 Licencia

Este proyecto es de carácter educativo.