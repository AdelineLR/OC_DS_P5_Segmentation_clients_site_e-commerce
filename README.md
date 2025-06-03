# Segmentation des clients d'un site de e-commerce

_Projet réalisé dans le cadre de la formation Data Scientist d'OpenClassrooms (Projet n°5 - Mars 2024)_

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![pandas]!(https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white) ![sqlite](https://img.shields.io/badge/Sqlite-003B57?style=for-the-badge&logo=sqlite&logoColor=white) ![sklearn](https://img.shields.io/badge/scikitlearn-F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![plotly](https://img.shields.io/badge/Plotly-239120?style=for-the-badge&logo=plotly&logoColor=white)


## Compétences acquises
* Évaluer les performances des modèles d’apprentissage non supervisé : K-means, DBSCAN, CAH
* Sélectionner et entraîner des modèles d’apprentissage non-supervisé

## Contexte et problématiques
Olist est une entreprise brésilienne qui propose une solution de vente sur les marketplaces en ligne.
Elle souhaite comprendre les différents types d'utilisateurs grâce à leur comportement et à leurs données personnelles. 
L'objectif de la mission est de fournir une segmentation de clients qu’elles pourront utiliser au quotidien pour leurs campagnes de communication, ainsi qu’une proposition de contrat de maintenance basée sur une analyse de la stabilité des segments au cours du temps.

## Données
* https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce : base de données anonymisée comportant des informations sur l’historique des commandes, les produits achetés, les commentaires de satisfaction, et la localisation des clients depuis janvier 2017.
  
## Livrables
* LeRay_Adeline_1_Script_SQL_032024.ipynb : Requêtes SQL pour répondre à des demandes métier
* LeRay_Adeline_2_Notebook_Analyse_Exploratoire_032024.html : Analyse exploratoire à partir des bases de données SQL, requêtes SQLite avec la bibliothèque python sqlite3
* LeRay_Adeline_3_Notebook_Essais_Clustering_032024.html : Essais de segmentation des clients avec des approches RFM (Recency - Frequency - Monetary) et des algorithmes de clustering K-means, DBSCAN, CAH (Classification Hiérarchique Ascendante)
* LeRay_Adeline_4_Notebook_Simulation_Maintenance_032024.ipynb : Simulation pour déterminer la fréquence nécessaire de mise à jour du modèle de segmentation, afin que celui-ci reste pertinent
* LeRay_Adeline_5_Presentation_032024.pdf : Présentation des résultats du projet
