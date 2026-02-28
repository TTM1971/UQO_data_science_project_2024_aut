<<<<<<< HEAD
# Analyse Prédictive du Diabète - Projet de Science des Données

## Description du Projet

Ce projet de science des données vise à collecter, traiter et analyser des données médicales pour identifier les variables qui impactent le risque de diabète. L'analyse combine des techniques statistiques avancées, des visualisations et un modèle de machine learning pour prédire la probabilité de développer un diabète.

## Objectifs

1. **Collecte et traitement** : Nettoyage et préparation des données médicales
2. **Analyse statistique** : Identification des facteurs critiques liés au diabète
3. **Visualisations** : Représentations graphiques des relations entre variables
4. **Modélisation** : Création d'un modèle de machine learning prédictif
5. **Évaluation** : Mesure de la performance du modèle

## Technologies Utilisées

- **Python** : Langage de programmation principal
- **Pandas** : Manipulation et analyse des données
- **NumPy** : Calculs numériques
- **Scikit-learn** : Modèles de machine learning
- **Matplotlib/Seaborn** : Visualisations
- **Jupyter Notebook** : Environnement de développement

## Données

- **Type** : Données médicales sur le diabète
- **Variables** : Âge, IMC, hypertension, consommation (veggies, alcool), assurance, sexe, etc.
- **Variable cible** : Présence de diabète (binaire)
- **Nature des données** : Principalement binaires (oui/non)

## Méthodologie

### 1. Collecte et Traitement
- Nettoyage des données
- Gestion des valeurs manquantes
- Vérification de la qualité des données

### 2. Analyse Statistique
- Identification des facteurs critiques :
  - **Âge** : Facteur significatif
  - **Indice de Masse Corporelle (IMC)** : Fort impact
  - **Hypertension** : Variable importante
- Exclusion des variables à faible impact :
  - Consommation de légumes
  - Consommation d'alcool
  - Assurance
  - Sexe
  *(Score d'information mutuelle bas)*

### 3. Visualisations
- Graphiques de distribution
- Matrices de corrélation
- Visualisations des relations entre variables

### 4. Modélisation
- Sélection des features pertinentes
- Entraînement d'un modèle de machine learning
- Optimisation des hyperparamètres

### 5. Évaluation
- Score de performance : **75%**
- Métriques : Accuracy, Precision, Recall, F1-Score

## Résultats Principaux

### Facteurs Critiques Identifiés
- **Âge** : Impact significatif sur le risque de diabète
- **IMC** : Forte corrélation avec le diabète
- **Hypertension** : Facteur de risque important

### Variables Exclues
- Consommation de légumes (score d'information mutuelle bas)
- Consommation d'alcool
- Assurance
- Sexe

### Performance du Modèle
- **Score** : 75% d'accuracy
- **Limitation** : Nature binaire des données peut masquer certaines informations

## Structure du Projet

```
├── README.md
└── uqo_ds_project_2024.ipynb    # Notebook principal avec l'analyse complète
```

## Utilisation

1. Installer les dépendances :
```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

2. Charger les données dans le notebook

3. Exécuter les cellules dans l'ordre pour :
   - Traiter les données
   - Effectuer l'analyse statistique
   - Créer les visualisations
   - Entraîner et évaluer le modèle

## Applications

Ce modèle peut être utilisé pour :
- Dépistage précoce du diabète
- Identification des populations à risque
- Aide à la décision médicale
- Recherche en santé publique

## Limitations et Améliorations Futures

### Limitations Actuelles
- Nature binaire des données (masque certaines informations)
- Score de 75% peut être amélioré
- Variables continues manquantes

### Améliorations Possibles
- Incorporation de variables continues
- Élargissement de l'ensemble de données
- Utilisation de modèles plus avancés (Deep Learning)
- Analyse plus approfondie des relations non-linéaires

## Notes Techniques

- **Information mutuelle** : Utilisée pour sélectionner les features
- **Modèle de base** : Performance raisonnable mais perfectible
- **Données binaires** : Limitation pour comprendre les relations complexes

## Contexte

Projet réalisé dans le cadre du cours de science des données de l'UQO (Automne 2024).
=======
# UQO_data_science_project1_2024_aut

Notre objectif était de collecter et traiter les données, deectuer une analyse
statistique, des visualisations afin de repérer les variables qui impactent sur la maladie. A
travers lanalyse statistique, nous avons pu identifier des facteurs critiques liés au diabète tels
que l'âge, lindice de masse corporelle et lhypertension.
Les facteurs tels que les “veggies”, la consommation dalcool, lassurance, le sex ont été
exclus lors de l'entraînement du modèle afin de réduire le bruit car ils avaient un score
dinformation mutuelle bas.
Nous avons par la suite créé et entraîné un modèle de machine learning basique qui
sest avéré raisonnablement performant avec un score de 75%.
Cependant, la majorité de nos données était sous une forme binaire(oui ou non). Cette
nature binaire des données peut masquer certaines informations sur la relation entre les
variables. Des analyses futures pourraient bénéficier de l'incorporation de variables continues
ou de l'élargissement de l'ensemble des données pour inclure des réponses plus détaillées, ce
qui permettrait une compréhension plus riche des facteurs influençant le risque de diabète.
>>>>>>> 670ce3176ed594aa8ee567e12a9ccdb35733d5ae
