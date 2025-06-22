#  Prédiction du Prix de Clôture Boursier

Ce projet vise à prédire le **prix de clôture des actions AAPL (Apple Inc.)** à l’aide de modèles de **Machine Learning** et **Deep Learning**.

##  Contenu du projet

- Analyse exploratoire des données (EDA)
- Extraction de features techniques (RSI, moyennes mobiles, etc.)
- Entraînement de modèles :
  - Régression linéaire
  - Random Forest
  - SVM
  - Réseaux de neurones (MLP, Dense NN)
  - LSTM
- Évaluation avec RMSE, MAE, R²
- Prédiction du prix du lendemain

##  Résultat

Le modèle de **régression linéaire** donne les meilleurs résultats :
- RMSE : 3.3784
- MAE : 2.3314
- R² : 0.9891

##  Fichiers inclus

- `Prédiction du Prix de Clôture Boursier.ipynb` : notebook principal
- `dataset_bourse.csv` : données traitées
- `dataset_bourse_yfinance.csv` : données brutes
- `README.md` : description du projet

##  Données utilisées

- Action : AAPL
- Période : 01/01/2010 à 20/06/2025
- Source : [yfinance](https://pypi.org/project/yfinance/)

##  Auteur

Projet réalisé par *Hassan Ibbakh*  et *Youssef Karimi* — Master IASD, Université Mohammed Premier.
