# Résultats

Ce dossier contient les résultats légers du projet et les informations nécessaires pour les retrouver et les reproduire. Chaque résultat doit préciser sa date, la méthode, les paramètres, les versions des données et des scripts utilisés, ainsi que les références bibliographiques utiles.

## Résultats issus de la littérature — 2026-11-08

Le fichier [`enthalpie_exces_max_litterature.csv`](enthalpie_exces_max_litterature.csv) rassemble huit valeurs publiées pour l’enthalpie molaire d’excès de mélanges ternaires d’éthers glycoliques, de 1-butanol et d’éthanol, à 298.15 K et 313.15 K. Ce sont des résultats expérimentaux rapportés dans la littérature, pas des prédictions réalisées dans le présent projet.

**Méthode et conditions rapportées par l’article :** calorimètre à flux quasi-isotherme ; pression de 0.1 MPa ; températures de 298.15 et 313.15 K. L’article indique une incertitude-type sur la composition molaire de 0.0008 et une incertitude relative élargie de 1 % (k = 2) sur l’enthalpie molaire d’excès. Les valeurs du CSV correspondent aux maxima tabulés de \(H_{123}^{E}\) ; la colonne `x2_sur_x3` identifie le rapport de composition de la série expérimentale. Les données originales restent celles des Tableaux 5 et 6 de l’article.

**Référence :** Yatim, F. E. et al. (2026), *Alcohol–Additive Ternary Mixtures for Sustainable Fuel Formulations: Experimental Excess Molar Enthalpy and Thermodynamic Modeling*, *International Journal of Thermophysics*, 47, 32. [Article et PDF éditeur](https://doi.org/10.1007/s10765-025-03682-7). Le tableau 6 a fait l’objet d’une correction publiée le 21 mars 2026 concernant son en-tête d’unité : [notice de correction](https://doi.org/10.1007/s10765-026-03716-8).

**Précaution de transcription :** le texte de l’article donne « 315.15 K » pour les maxima de 22MEE et 2-PhE, alors que les Tableaux 6 et 8 indiquent 313.15 K. Le CSV suit l’en-tête du Tableau 6 et signale cette différence dans les notes. Les compositions détaillées \(x_2\) et \(x_3\) ne sont pas recalculées ici ; la fraction additive \(x_1\) et le rapport \(x_2/x_3\) du tableau sont conservés.

Cette transcription constitue un résumé documentaire reproductible à partir des tableaux publiés. Les données sources de l’article sont publiées sous licence CC BY 4.0 ; consulter la licence et la notice de correction avant toute réutilisation.

## Fiche à renseigner pour chaque résultat futur

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
