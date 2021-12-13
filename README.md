# Classification supervisée basée `pixels`

Pour ce travail on a utilisé une image satellitaire Sentinel-2 de la région Nador au nord du Maroc, issue du site de l’USGS, les bandes spectrales des channels R, G, B et NIR sont utilisées.

L'idée de base est de prendre les valeurs radiométriques des differentes bandes de l'image satellitaire, les aplatir puis entrainer le fameux `KNN` de sklearn.