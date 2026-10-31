# Optimisation des stocks et des ventes d'une boutique en ligne

> Réconciliation de données ERP et web, nettoyage et analyse des ventes, des stocks et des marges.

## Contexte

La boutique BottleNeck dispose de trois sources de données à rapprocher : son ERP (produits, prix, stocks), son site web (ventes, descriptions) et une table de correspondance entre les deux codifications de références.

## Démarche

1. **Analyse exploratoire** des trois sources : volumes différents, codifications de références différentes, qualité hétérogène.
2. **Nettoyage** : correction des prix et des stocks négatifs, mise en cohérence des statuts de stock, dédoublonnage de 712 SKU en double.
3. **Fusion** : rapprochement ERP, table de liaison et web. Une première jointure produisait 9 183 lignes au lieu de 825 à cause des doublons, problème résolu en dédoublonnant avant la fusion.
4. **Valeurs aberrantes** : détection des prix atypiques par Z-score et par écart interquartile.
5. **Indicateurs** : taux de marge, rotation et valorisation des stocks, chiffre d'affaires et quantités vendues, corrélations entre stocks, ventes et prix.

## Livrables

| Fichier | Contenu |
|---|---|
| [Notebook](Abderrahmane_Jordan_notebook_032025.ipynb) | Nettoyage, fusion et analyses (Python) |
| [Présentation](Abderrahmane_Jordan_presentation_032025.pptx) | Démarche, difficultés et résultats |

## Outils

Python (Pandas) · Qualité des données · Statistiques descriptives
