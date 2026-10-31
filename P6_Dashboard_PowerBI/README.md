# Tableau de bord Power BI multi-niveaux ⭐

> Suivi de projets IT et marketing internationaux, avec une vue adaptée à chaque niveau de direction.

## Contexte

Sanitoral, une entreprise présente dans 4 grandes régions du monde, dispose de nombreuses données sur ses projets IT et marketing sans savoir les exploiter. Son service PMO veut un tableau de bord pour piloter le portefeuille de projets.

Trois profils d'utilisateurs, avec des besoins différents :

- **Directeur général** : suivre la performance globale et décider de la poursuite ou de l'arrêt des projets
- **Directeurs régionaux** : être alertés sur les projets de leur région
- **Directeurs pays** : suivre les indicateurs de leur pays pour prendre des mesures correctives

## Démarche

1. **Cadrage** : note de cadrage rédigée à partir de la réunion avec la cheffe de projet PMO.
2. **Indicateurs** : coûts, respect des délais et livrables produits, avec une alerte dès que l'écart entre le prévisionnel et le réel dépasse 15 %.
3. **Mesures DAX** : calcul des écarts et comptage des projets en alerte.
4. **Sécurité par niveau (RLS)** : chaque directeur ne voit que le périmètre qui le concerne.
5. **Visualisations** : carte du monde des retards par pays, graphiques variés et infobulles détaillées.

## Livrables

| Fichier | Contenu |
|---|---|
| [Tableau de bord](Abderrahmane_jordan_tableau_de_bord_052025.pbix) | Fichier Power BI |
| [Note de cadrage](Note_de_cadrage_Sanitoral.pdf) | Besoins, utilisateurs et spécifications fonctionnelles |
| [Documentation technique](<Documentation technique.pdf>) | Modèle de données, mesures et sécurité |

## Outils

Power BI · DAX · Row-Level Security (RLS)
