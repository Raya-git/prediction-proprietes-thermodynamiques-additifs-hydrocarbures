# Résultats

Ce dossier contient les résultats légers du projet et les informations nécessaires pour les retrouver et les reproduire. Chaque résultat doit préciser sa date, la méthode, les paramètres, les versions des données et des scripts utilisés, ainsi que les références bibliographiques utiles.

## État initial du projet — 2026-11-08

À la date de cet inventaire, aucun résultat de prédiction thermodynamique n’est encore disponible dans le dépôt. Aucun jeu de données réel n’est présent dans `data/raw/` ou `data/processed/`, et aucun script d’analyse ou de prédiction n’est encore fourni dans `scripts/`. Le fichier `data/templates/proprietes_thermodynamiques.csv` est un gabarit de saisie : son en-tête décrit les champs prévus, mais il ne contient pas d’observations expérimentales.

Ce constat décrit l’état du dépôt ; il ne constitue pas un résultat scientifique. Il est consigné pour distinguer clairement les livrables préparatoires des résultats qui seront produits après l’ajout et la vérification des données.

| Élément | Information consignée |
|---|---|
| Date de l’inventaire | 2026-11-08 |
| Méthode | Vérification de la structure du dépôt et des contenus présents dans `data/raw/`, `data/processed/`, `data/templates/` et `scripts/` |
| Paramètres de calcul | Sans objet : aucun calcul ni modèle n’a été exécuté |
| Données examinées | `data/templates/proprietes_thermodynamiques.csv` (en-tête seulement) ; aucun jeu de données réel examiné |
| Script utilisé | Aucun |
| Référence bibliographique | Aucune source scientifique utilisée pour cet inventaire documentaire |
| Conclusion | Résultats numériques à produire ultérieurement, après sélection et documentation des données, de la propriété et de la méthode de prédiction |

## Fiche à renseigner pour chaque résultat futur

Copier cette fiche dans un nouveau fichier, par exemple `AAAA-MM-JJ_propriete_methode.md`, puis remplacer les champs entre crochets. Ne pas inscrire de valeurs prévisionnelles ou fictives comme si elles avaient été calculées.

```text
Identifiant et titre :
Date de production :
Question ou propriété étudiée :
Substance(s) ou composition(s) :
Méthode / modèle et version :
Paramètres (conditions, réglages, unités) :
Données d’entrée (chemin, version ou empreinte) :
Références des données et DOI :
Script utilisé (chemin, version ou commit Git) :
Environnement et dépendances :
Fichiers de sortie légers (chemins) :
Contrôles / limites :
Fichiers volumineux associés : nom, emplacement, taille et moyen d’accès
```

## Formats et fichiers volumineux

Privilégier les sorties légères et réutilisables : tableaux CSV, notes Markdown et graphiques PNG ou SVG. Nommer les fichiers de façon descriptive, par exemple `AAAA-MM-JJ_propriete_methode.csv`.

Ne pas déposer dans GitHub les fichiers volumineux ou soumis à restriction. Les conserver dans un espace de stockage adapté et accessible au projet (par exemple le stockage institutionnel autorisé), puis documenter ici, dans la fiche correspondante, leur nom, leur emplacement, leur taille, leur date de dépôt et les conditions d’accès. Aucun fichier volumineux n’est actuellement référencé.
