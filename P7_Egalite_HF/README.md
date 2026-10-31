# Diagnostic d'égalité professionnelle femmes-hommes

> Calcul de l'index d'égalité professionnelle d'une entreprise de 256 salariés, avec un workflow automatisé et réutilisable.

## Contexte

Une entreprise de 256 salariés doit publier son index d'égalité professionnelle. Elle souhaite aussi s'en servir pour renforcer sa marque employeur.

## Démarche

1. **Données** : trois extractions du SIRH, anonymisées (suppression des données identifiantes, analyse sur données agrégées uniquement) pour respecter le RGPD.
2. **Préparation** : contrôle des jointures, normalisation des temps de travail en ETP, traitement des valeurs aberrantes.
3. **Indicateurs** : rémunération, répartition par service, temps de travail, types de contrat, tranches d'âge, présence des femmes parmi les 10 plus hauts salaires et ancienneté (à titre indicatif).
4. **Automatisation** : workflow KNIME documenté et réutilisable, avec export vers Tableau.

## Résultats

- **Score global** : 80,6 / 100
- **Points forts** : âge, contrats et temps de travail au maximum, rémunération à 90 % (écart salarial moyen de 3,4 %)
- **Axes de progrès** : mixité des services, notamment l'informatique, et accès des femmes aux plus hauts salaires (une seule femme dans le top 10)
- **Plan d'actions** : objectifs chiffrés et calendrier de suivi (tableaux de bord trimestriels, revue semestrielle, publication annuelle)

## Livrables

| Fichier | Contenu |
|---|---|
| [Présentation](Abderrahmane_jordan_3_support_presentation_062025.pptx) | Méthodologie, résultats et recommandations |

## Outils

KNIME · Tableau · RGPD
