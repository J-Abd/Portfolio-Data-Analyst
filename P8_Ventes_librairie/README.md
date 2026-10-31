# Analyse des ventes d'une librairie

> Analyse des ventes, des produits et du comportement des clients d'une librairie en ligne.

## Contexte

Une librairie dispose de trois fichiers (clients, produits, transactions) et souhaite mieux comprendre ses ventes et sa clientèle.

## Démarche

1. **Préparation** : analyse exploratoire de chaque fichier, puis jointure des tables.
2. **Indicateurs de vente** : évolution du chiffre d'affaires avec moyenne mobile, CA mensuel et par catégorie, nombre de clients, de transactions et de produits vendus.
3. **Références produits** : répartition des références par catégorie.
4. **Concentration du CA** : courbe de Lorenz pour mesurer la part du chiffre d'affaires portée par les plus gros clients.
5. **Comportement d'achat** : corrélations entre le genre, l'âge, le montant des achats, la fréquence d'achat, la taille du panier et les catégories de livres.

## Livrables

| Fichier | Contenu |
|---|---|
| [Notebook](Abderrahmane_jordan_1_notebook_062025.ipynb) | Analyses complètes (Python) |

## Outils

Python (Pandas, Plotly, Seaborn, SciPy) · Tests statistiques (Spearman, Khi², ANOVA)
