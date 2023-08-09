# Segmentez des clients d'un site e-commerce

Projet portant sur la segmentation des clients à partir d'une base de données.

Un nettoyage et une analyse de données ont été menées. Ensuite, j'ai effectué un k-means pour un certains nombre de variables (RFM seules, ajout de variables pertinentes). Le nombre de centroïdes ont été choisi grâce au score Davies-Bouldin, au score Silhouette, à l'inertie et une CAH.

Pour chaque nombre de centroïdes choisi, un radar a été traçé pour déterminer si des clients-types ressortent ou non de la segmentation choisie.

La dernière étape a consisté à déterminer la fréquence à laquelle il est nécessaire de faire une maintenance de la segmentation. Pour cela, le score ARI a été choisi comme métrique et j'ai déterminé l'évolution du score ARI avec le temps.
