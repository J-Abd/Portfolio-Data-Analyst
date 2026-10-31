# Création et requêtage d'une base de données SQL

> Conception d'une base de données MySQL pour un assureur habitation, de la modélisation aux requêtes d'analyse.

## Contexte

Un assureur habitation dispose de deux fichiers CSV (contrats clients et régions) et d'un dictionnaire de données incomplet. Il a besoin d'une base de données relationnelle exploitable.

## Démarche

1. **Analyse des données** : exploration des fichiers pour identifier les types de données et compléter le dictionnaire de données (variables, contraintes).
2. **Modélisation** : finalisation du schéma relationnel dans SQL Power Architect, puis génération du code SQL de création des tables.
3. **Création et chargement** : création de la base `assurance_habitation` sous MySQL et import des données, avec correction des caractères problématiques (apostrophes dans les noms de régions, par exemple).
4. **Requêtes** : réponses aux questions métier par des requêtes SQL, vérifiées pas à pas dans le terminal.

## Livrables

| Fichier | Contenu |
|---|---|
| [Document technique](Abderrahmane_Jordan_document_technique_112024.pdf) | Dictionnaire de données, schéma relationnel, création de la base, requêtes |
| [Méthodologie](Abderrahmane_Jordan_methodologie_112024.pdf) | Démarche suivie, étape par étape |
| [Liste des requêtes](Abderrahmane_Jordan_liste_112024.docx) | Requêtes SQL et leurs résultats |

## Outils

MySQL · SQL Power Architect · Modélisation relationnelle
