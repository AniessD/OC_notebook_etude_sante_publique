# Etude de santé publique : Analyse de la sous-nutrition dans le monde (2013-2017)

## Objectif du projet
Ce projet a été réalisé dans le cadre de ma formation OpenClassrooms. Il consiste à analyser la sous-nutrition dans le monde entre 2013 et 2017, dans le cadre d'une mission simulée au sein de la FAO.
L'objectif est de comprendre : 
- la disponibilité alimentaire mondiale,
- l'utilisation des ressources,
- la répartition des ressources entre les pays,
- le rôle de l'aide alimentaire

L'analyse a été réalisée en Python, dans un notebook Jupyter, en utilisant les librairies Pandas, NumPy, Matplotlib et Seaborn.

## Données utilisées
Les données proviennent de la FAO et couvrent plusieurs thématiques : 
- population.csv : Population par pays et par année
- dispo_alimentaire.csv : Disponibilité alimentaire par produit et par pays
- aide_alimentaire.csv :	Quantité d’aide alimentaire reçue par pays
- sous_nutrition.csv : Nombre de personnes en sous‑nutrition

## Méthodologie
1. Importation et nettoyage
   - Chargement des fichiers CSV
   - Harmonisation des unités
   - Correction des noms de pays
   - Remplacement des valeurs manquantes
   - Conversion des périodes en années exploitables

2. Fusion des datasets
   - Jointures entre population, sous-nutrition et disponibilité alimentaire
   - Agrégations par pays et par année
   - Calculs globaux (kcal disponibles, disponibilité intérieure, ...)

3. Analyses principales
   - Nombre total de personnes en sous-nutrition en 2017
   - Nombre théorique de personnes pouvant être nourries
   - Répartition de la disponibilité intérieure
   - Analyse spécifique des céréales
   - Analyse de l'aide alimentaire
   - Etude de cas : manioc en Thaïlande

4. Visualisations
   - Diagrammes circulaires
   - Barplots
   - Courbes temporalles
   - Comparaisons entre pays

## Principaux résultats
- **535.7 millions** de personnes en sous-nutrition, soit **7.1%** de la population mondiale
- La disponibilité alimentaire mondiale aurait permis de nourrir **7.2 milliards** de personnes
- Les pays recevant **le plus d'aide** ne sont pas ceux ayant le plus fort taux de sous-nutrition

## Compétences
- Nettoyage et préparation des données
- Jointures, agrégations, filtrages
- Manipulations de Pandas
- Visualisations (Matplotlib, Seaborn)
