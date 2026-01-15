# 🌍 Analyse Stratégique du Marché Airbnb Europe
> **Analyse exploratoire (EDA) et recommandations stratégiques pour l'investissement locatif.**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Tableau Style](https://img.shields.io/badge/Style-Tableau%20Public-orange?style=for-the-badge)

## 📌 Présentation du Projet
Ce projet a été réalisé dans le cadre d'un module de **Data Analysis**. L'objectif est d'analyser un dataset de plus de 30 000 lignes regroupant les offres Airbnb dans 6 capitales européennes afin d'orienter une prise de décision stratégique pour un investisseur.



## 📊 Problématique
> *Quels facteurs influencent réellement le prix et la satisfaction client, et où se situent les meilleures opportunités de rendement en Europe ?*

## 🛠️ Méthodologie & Nettoyage
Le projet suit les étapes suivantes :
1. **Extraction :** Importation des données depuis 10 fichiers CSV sources.
2. **Cleaning :** Gestion des doublons, traitement des outliers (> 1000€) et normalisation des prix par personne.
3. **Feature Engineering :** Création d'indices de distance et de catégories de logements.

## 📈 Visualisations Clés
### 1. Cartographie des Prix
Une analyse géographique permettant de visualiser la densité des offres et les zones de prix élevés.

![Carte Europe](images/map_europe.png)  
*(Note : Importe ici l'image de la carte que tu as générée dans Colab)*

### 2. Corrélation Propreté vs Satisfaction
Le graphique montre que la propreté est le levier n°1 de la notation globale.



## 💡 Insights Stratégiques
* **Zone d'Or (3-5km) :** Les prix ne chutent pas linéairement avec la distance ; les biens en périphérie proche conservent une forte valeur.
* **Paradoxe du Superhost :** Les Superhosts affichent des prix 8% inférieurs à la moyenne mais un taux de remplissage et une satisfaction bien plus élevés.
* **Impact Propreté :** Une note de propreté parfaite est indispensable pour maintenir un score > 90/100.

## 🚀 Comment utiliser ce repo ?
1. Clonez le projet : `git clone https://github.com/TON_PSEUDO/Airbnb-Analysis.git`
2. Installez les dépendances : `pip install -r requirements.txt`
3. Ouvrez le notebook dans `notebooks/Analyse.ipynb`.

---
© 2026 - DIOP Issa - Data Analyst
