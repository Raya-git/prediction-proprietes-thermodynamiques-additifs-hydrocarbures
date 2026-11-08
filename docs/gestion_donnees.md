# Gestion des données du projet

## Formats et organisation

Les classeurs Excel servent à la saisie et au contrôle manuel. Les exports destinés au traitement informatique seront conservés en CSV UTF-8, avec un point comme séparateur décimal et une ligne par observation. Les scripts pourront utiliser des notebooks Jupyter ou des fichiers Python ; leurs versions et dépendances seront documentées.

Les données sources et les données transformées restent séparées dans `data/raw/` et `data/processed/`. Une transformation doit être décrite avec sa date, son objectif et le script utilisé. Ne pas écraser les fichiers sources.

## Provenance et métadonnées

Pour chaque observation, consigner la référence bibliographique ou le DOI, l’identité des substances (nom et numéro CAS lorsqu’il est disponible), la composition du mélange, la propriété thermodynamique, la valeur, l’unité, la température, la pression, la méthode (expérimentale ou prédictive) et l’incertitude lorsqu’elle est publiée. Les unités doivent être explicites et les conversions documentées.

## Contrôle et sauvegarde

Vérifier les unités, les plages de température et de pression, la cohérence des compositions et la présence des valeurs manquantes. Comparer les données transcrites à la source publiée. Conserver une copie de sauvegarde des classeurs et des fichiers de travail sur un espace sécurisé approuvé par l’établissement. Git sert principalement à versionner les scripts et la documentation, pas à stocker des fichiers de données lourds.

## Partage et droits

Avant tout partage, vérifier les droits associés aux articles et aux bases de données consultées. Partager les données dérivées, scripts et résultats seulement lorsque les conditions de réutilisation le permettent, en citant les sources. Les informations personnelles, confidentielles ou restreintes ne doivent pas être déposées dans ce dépôt.
