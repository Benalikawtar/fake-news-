# 📊 Détection de Fake News par Apprentissage Automatique

## Introduction
Ce projet vise à développer un modèle de classification permettant de détecter automatiquement les fake news en analysant le texte des articles. L'objectif est d'utiliser des techniques d'apprentissage automatique pour distinguer les informations vérifiées des informations trompeuses.

## Dataset
Le dataset **WELFake** est composé de **72 134 articles**, répartis comme suit :
- `1` : Article véridique
- `0` : Fake news

Les données proviennent de plusieurs sources fiables telles que **Kaggle, McIntire, Reuters et BuzzFeed** afin d'améliorer la généralisation du modèle.

## Méthodologie
1. **Préparation des données** :
   - Suppression des caractères inutiles, normalisation des textes et suppression des stop words.
   - Vectorisation des textes à l'aide de **TF-IDF**.
2. **Modélisation** :
   - Test de plusieurs algorithmes : **SVM, Random Forest, Naïve Bayes, MLP, KNN**.
3. **Évaluation des modèles** :
   - Comparaison des performances en utilisant des métriques comme la précision, le rappel et le score F1.

## Résultats
- **Meilleur modèle** : **SVM**, avec une précision de **96,67%**.
- **Autres modèles testés** : MLP, Random Forest, Naïve Bayes, KNN.
- **Optimisation** : Amélioration des performances grâce à l'ajustement des hyperparamètres.

## Références
- **Dataset WELFake** : [Lien Kaggle](https://www.kaggle.com/datasets/saurabhshahane/fake-news-classification)
- **Méthodes utilisées** : TF-IDF, SVM, Random Forest, etc.

## Avertissement
Ce projet est à but **académique** et ne remplace pas une vérification journalistique des informations.

