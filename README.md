#  Prédiction du Prix de Clôture Boursier

Ce projet vise à prédire le **prix de clôture des actions AAPL (Apple Inc.)** à l’aide de modèles de **Machine Learning** et **Deep Learning**, en suivant un pipeline complet : de la collecte automatique des données jusqu’à la prédiction future.

##  Contenu du projet

-  **Collecte automatique des données** via l’API [yfinance](https://pypi.org/project/yfinance/)
-  Prétraitement et nettoyage des données
-  Analyse exploratoire (EDA)
-  Extraction de variables financières (indicateurs techniques : RSI, moyennes mobiles, etc.)
-  Entraînement de plusieurs modèles :
  - Régression Linéaire
  - Random Forest
  - SVM (Support Vector Machine)
  - Réseaux de Neurones (MLP, Dense)
  - LSTM (Long Short-Term Memory)
-  Prédiction du prix de clôture du lendemain
-  Évaluation des performances (RMSE, MAE, R²)
-  Export et visualisation des résultats

##  Résultat principal

Le modèle de **régression linéaire** a obtenu les meilleures performances :

- **RMSE** : 3.3784  
- **MAE** : 2.3314  
- **R²** : 0.9891

##  Fichiers inclus

- `Prédiction du Prix de Clôture Boursier.ipynb` : notebook principal avec tout le pipeline
- `dataset_bourse.csv` : données transformées et prêtes pour le ML
- `dataset_bourse_yfinance.csv` : données brutes extraites via API
- `README.md` : description du projet

##  Données utilisées

- Titre : **Apple Inc. (AAPL)**
- Période : **du 01/01/2010 au 20/06/2025**
- Source : [API yfinance](https://pypi.org/project/yfinance/)

##  Auteurs

Projet réalisé par :
- *Hassan Ibbakh*
- *Youssef Karimi*  
Master IASD, Université Mohammed Premier.
