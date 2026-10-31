# Étude de marché à l'export ⭐

> Identification des pays les plus prometteurs à l'export pour un producteur de volailles bio.

## Contexte

La Poule qui Chante, un producteur français de volailles bio, souhaite se développer à l'international. Il faut identifier les groupes de pays les plus intéressants à cibler.

## Démarche

1. **Préparation des données** : repérage des doublons, nettoyage, standardisation des noms de pays à l'aide d'un fichier de référence, jointure des sources, puis validation et export du jeu de données final.
2. **Réduction de dimension** : standardisation, puis analyse en composantes principales (ACP), avec cercle des corrélations, interprétation des composantes et projection des pays.
3. **Segmentation** : regroupement des pays par classification ascendante hiérarchique (CAH) et par k-means, avec un nombre de groupes évalué par le score de silhouette.
4. **Recommandation** : sélection des groupes de pays à cibler en priorité.

## Livrables

| Fichier | Contenu |
|---|---|
| [Notebook 1 : préparation](Abderrahmane_Jordan_1_preparation_nettoyage_analyse_exploratoire_092025.ipynb) | Nettoyage, standardisation et analyse exploratoire |
| [Notebook 2 : ACP et clustering](Abderrahmane_Jordan_2_clustering_visualisations_092025.ipynb) | ACP, CAH, k-means et visualisations |

## Outils

Python (Pandas, scikit-learn, SciPy, Plotly) · ACP · Clustering (CAH, k-means)
