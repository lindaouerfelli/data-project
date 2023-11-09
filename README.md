# data-project
traitement et analyse des données

# Analyse des Séries Temporelles - Projet Énergie Allemagne

## Introduction

Ce projet a pour objectif d'analyser les séries temporelles des données de consommation d'énergie électrique, de production d'énergie solaire et éolienne en Allemagne sur la période de 2006 à 2017.

## Données

Les données ont été extraites du fichier CSV disponible [ici](https://raw.githubusercontent.com/jenfly/opsd/master/opsd_germany_daily.csv). Le jeu de données comprend les colonnes suivantes :
- Date : index temporel
- Consumption : consommation d'énergie électrique
- Wind : production d'énergie éolienne
- Solar : production d'énergie solaire
- Wind+Solar : production totale d'énergie éolienne et solaire combinée

## Prétraitement des données

Les étapes de prétraitement incluent la conversion de la colonne 'Date' en format datetime, la gestion des valeurs manquantes, et la création de nouvelles fonctionnalités telles que l'année, le mois, le jour de la semaine, et une indication du week-end.

## Analyse exploratoire

L'analyse exploratoire comprend des visualisations telles que des séries temporelles de la consommation d'énergie, des boxplots par mois et jour de la semaine, ainsi que des statistiques descriptives.

## Visualisations

Plusieurs visualisations ont été créées, notamment des scatter plots et des line plots, pour examiner la consommation d'énergie, la production d'énergie solaire et éolienne au fil du temps.

## Conclusion

Cette analyse des séries temporelles nous a permis de comprendre les tendances, la saisonnalité et les variations de la consommation d'énergie en Allemagne de 2006 à 2017. Les visualisations fournissent des insights sur les modèles de consommation et de production d'énergie.
