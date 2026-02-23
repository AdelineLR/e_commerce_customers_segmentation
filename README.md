# Segmentation des clients d'un site de e-commerce

_Projet réalisé dans le cadre de la formation Data Scientist d'OpenClassrooms (Projet n°5 - Mars 2024)_

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white) ![sqlite](https://img.shields.io/badge/Sqlite-003B57?style=for-the-badge&logo=sqlite&logoColor=white) ![sklearn](https://img.shields.io/badge/scikitlearn-F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![plotly](https://img.shields.io/badge/Plotly-239120?style=for-the-badge&logo=plotly&logoColor=white)

## Contexte
Olist est une entreprise brésilienne de e-commerce qui propose une solution de vente sur les marketplaces en ligne. Olist souhaite mieux cibler ses actions marketing en segmentant ses clients.

## Mission
Identifier des segments clients pertinents à partir des données d'achat et recommander une fréquence de mise à jour.

## Actions
1. Création des indicateurs RFM (Récence, Fréquence, Montant) à partir de requêtes SQL sur une base SQLite.
2. Application de méthodes de clustering non supervisées (K-means, classification hiérarchique - CAH, DBSCAN) pour segmenter les clients.
3. Analyse de la stabilité des segments dans le temps pour évaluer la fréquence optimale de mise à jour.

## Résultat 
Évaluation complète de la faisabilité technique et recommandations pour automatiser la classification, améliorant la scalabilité et la qualité de l’attribution des catégories.

## Données
* https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce : Base de données anonymisée comportant des informations sur l’historique des commandes, les produits achetés, les commentaires de satisfaction, et la localisation des clients depuis janvier 2017.
  
## Livrables
* LeRay_Adeline_1_Script_SQL_032024.ipynb : *Requêtes SQL pour répondre à des demandes métier*
* LeRay_Adeline_2_Notebook_Analyse_Exploratoire_032024.ipynb : *Analyse exploratoire à partir des bases de données SQL, requêtes SQLite avec la bibliothèque python sqlite3*
* LeRay_Adeline_3_Notebook_Essais_Clustering_032024.ipynb : *Essais de segmentation des clients avec des approches RFM (Recency - Frequency - Monetary) et des algorithmes de clustering K-means, DBSCAN, CAH (Classification Hiérarchique Ascendante)*
* LeRay_Adeline_4_Notebook_Simulation_Maintenance_032024.ipynb : *Simulation pour déterminer la fréquence nécessaire de mise à jour du modèle de segmentation, afin que celui-ci reste pertinent*
* LeRay_Adeline_5_Presentation_032024.pdf : *Présentation des résultats du projet*
