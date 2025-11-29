# Netflix Data Cleaning & Analysis

Ce projet est un exercice de data engineering / data analysis à partir du dataset **Netflix Titles**.

## Objectifs

- Charger le fichier `netflix_titles.csv` (gestion d’encodage).
- Nettoyer et préparer les données :
  - suppression de colonnes inutiles,
  - typage de `date_added`,
  - séparation de la colonne `duration` en minutes (films) et saisons (séries),
  - création de tables annexes : pays, catégories, acteurs (via `explode`),
  - création de colonnes temporelles (année, mois, jour de la semaine d’ajout).

- Répondre à plusieurs questions d’analyse :
  - répartition `Movie` / `TV Show`,
  - ajouts par année et par jour de la semaine,
  - top catégories,
  - top acteurs aux États-Unis,
  - pays produisant le plus de documentaires,
  - distribution des durées de films,
  - nombre de shows dont la description contient le mot **"drug"**.

## Stack

- Python
- pandas, numpy
- Jupyter Notebook

## Fichiers

- `netflix_cleaning_analysis.ipynb` : notebook principal (cleaning + analyses).
- `netflix_titles.csv` : dataset Netflix (version pédagogique).
