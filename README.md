# Segmentation des clients d'un site de e-commerce

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white) ![sqlite](https://img.shields.io/badge/Sqlite-003B57?style=for-the-badge&logo=sqlite&logoColor=white) ![sklearn](https://img.shields.io/badge/scikitlearn-F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![plotly](https://img.shields.io/badge/Plotly-239120?style=for-the-badge&logo=plotly&logoColor=white)

## Contexte
Olist est une entreprise brésilienne de e-commerce qui propose une solution de vente sur les marketplaces en ligne. Olist souhaite mieux cibler ses actions marketing en segmentant ses clients.
<img width="1330" height="597" alt="image" src="https://github.com/user-attachments/assets/f53ce0c1-eb78-4487-bb40-6988f655e1c5" />

## Mission
Identifier des segments clients pertinents à partir des données d'achat et recommander une fréquence de mise à jour. 

## Actions
1. Implémentation de requêtes SQL pour la construction du Dashboard pour les équipes Customer Experience.
2. Analyse exploratoire et création des indicateurs RFM (Récence, Fréquence, Montant) à partir de requêtes SQL sur une base SQLite.
3. Segmentation des clients : Application de la méthode RFM et de méthodes de clustering non supervisées (K-means, classification hiérarchique - CAH, DBSCAN) pour segmenter les clients.
4. Analyse de la stabilité des segments dans le temps pour évaluer la fréquence optimale de mise à jour.
<img width="1310" height="707" alt="image" src="https://github.com/user-attachments/assets/7f283e28-2e9e-49d4-9e35-f8fde8c76f8b" />
<img width="1346" height="586" alt="image" src="https://github.com/user-attachments/assets/1c8dbe47-edce-4a5f-9bdd-eb2aee21e36e" />

## Résultat 
Évaluation complète de la faisabilité technique et recommandations pour automatiser la classification, améliorant la scalabilité et la qualité de l’attribution des catégories.
<img width="1355" height="753" alt="image" src="https://github.com/user-attachments/assets/03f49104-8c6b-4d15-bf94-b9997130e5c8" />
<img width="1324" height="737" alt="image" src="https://github.com/user-attachments/assets/0ba07931-0f87-42ad-9972-82857819f37d" />
<img width="1320" height="597" alt="image" src="https://github.com/user-attachments/assets/04db30ed-3d89-44b7-a74a-ee7a16c773fc" />


## Données
* https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce : Base de données anonymisée comportant des informations sur l’historique des commandes, les produits achetés, les commentaires de satisfaction, et la localisation des clients depuis janvier 2017.
<img width="2486" height="1496" alt="database" src="https://github.com/user-attachments/assets/fb6b1e46-d75f-4943-9b17-fac8fd61075c" />

## Contenu du dossier code
* 1_Script_SQL.ipynb : *Requêtes SQL pour répondre à des demandes métier*
* 2_Notebook_Analyse_Exploratoire.ipynb : *Analyse exploratoire à partir des bases de données SQL, requêtes SQLite avec la bibliothèque python sqlite3*
* 3_Notebook_Essais_Clustering.ipynb : *Essais de segmentation des clients avec des approches RFM (Recency - Frequency - Monetary) et des algorithmes de clustering K-means, DBSCAN, CAH (Classification Hiérarchique Ascendante)*
* 4_Notebook_Simulation_Maintenance.ipynb : *Simulation pour déterminer la fréquence nécessaire de mise à jour du modèle de segmentation, afin que celui-ci reste pertinent*
* 5_Presentation_projet.pdf : *Présentation des résultats du projet*

_Projet réalisé dans le cadre de la formation Data Scientist d'OpenClassrooms (Projet n°5 - Mars 2024)_
