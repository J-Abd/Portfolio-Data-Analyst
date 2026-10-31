# Détection de faux billets par Machine Learning ⭐

> Modèle de classification des billets en vrais ou faux, intégré dans une application de détection.

## Contexte

L'Organisation nationale de lutte contre le faux-monnayage (ONCFM) veut identifier rapidement et avec précision les contrefaçons, à partir des dimensions géométriques des billets.

Le jeu de données compte 1 500 billets (1 000 vrais, 500 faux), décrits par 6 dimensions géométriques, avec 37 valeurs manquantes sur la variable `margin_low`.

## Démarche

1. **Benchmark 1, reconstitution des données manquantes** : comparaison de trois approches par régression et d'une approche par clustering k-means. Le k-means a été retenu comme modèle optimal.
2. **Benchmark 2, classification** : analyse du pouvoir discriminant des variables (`length` et `margin_low` sont les plus déterminantes), puis comparaison de quatre algorithmes : régression logistique, KNN, Random Forest et k-means, sur 268 configurations.
3. **Sécurisation** : validation croisée et double contrôle. Les deux meilleurs modèles (régression logistique et KNN) sont combinés : un billet est déclaré faux si l'un des deux le détecte, pour minimiser les faux billets non repérés.
4. **Application** : transposition du modèle final en un outil de détection prêt à l'emploi.

## Livrables

| Fichier | Contenu |
|---|---|
| [Notebook d'analyse](Abderrahmane_jordan_1_Notebook_analyse_102025.ipynb) | Benchmarks 1 et 2 (Python) |
| [Notebook application](Abderrahmane_jordan_2_Notebook_application_102025.ipynb) | Application de détection |
| [Présentation](Abderrahmane_jordan_3_presentation_102025.pptx) | Démarche et résultats |

## Outils

Python (scikit-learn) · Régression · Classification · Validation croisée
