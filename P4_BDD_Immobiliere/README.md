# Base de données immobilière

> Conception d'une base de données normalisée (3FN) pour un réseau national d'agences immobilières.

## Contexte

Laplace Immo, un réseau national d'agences immobilières, lance un projet de modélisation prédictive des prix. Il faut d'abord centraliser des sources hétérogènes dans une base de données fiable :

- **Demandes de valeurs foncières (DVF)** : l'historique des transactions immobilières
- **Référentiel géographique** : régions, départements et communes
- **Données INSEE** : population des communes

## Démarche

1. **Dictionnaire de données** : description de chaque variable pour faciliter la compréhension et l'analyse.
2. **Schéma relationnel** : modèle respectant les 3 formes normales, pour éviter la redondance et garantir l'intégrité.
3. **Préparation des données** : suppression des ventes sans valeur ou négatives, contrôle des surfaces incohérentes, uniformisation des dates.
4. **Contrôles d'intégrité** : chaque bien rattaché à une commune valide, chaque commune à une région, chaque vente à un bien existant.
5. **Conformité RGPD** : analyse des données traitées (aucune donnée personnelle dans le périmètre du projet).
6. **Requêtes d'analyse** : ventes par région, répartition par nombre de pièces, prix moyen au m² par département…

## Livrables

| Fichier | Contenu |
|---|---|
| [Dictionnaire de données](Abderrahmane_Jordan_1_dictionnaire_de_donnees_022025.xlsx) | Description des variables (Excel) |
| [Présentation](Abderrahmane_Jordan_2_support_presentation_022025.pptx) | Schéma relationnel, contrôles et requêtes SQL |

## Outils

SQL · Modélisation relationnelle (3FN) · Dictionnaire de données · RGPD
