# Prédiction des propriétés thermodynamiques d’additifs pour hydrocarbures

Ce dépôt accompagne un travail de recherche consacré à la prédiction des propriétés thermodynamiques de substances pures et de mélanges utilisés comme additifs pour hydrocarbures. Il sert à organiser la documentation, les données, les scripts et les résultats du projet.

## Objectifs

- Rassembler les données expérimentales et les données extraites de publications en gardant leur provenance.
- Préparer et contrôler les jeux de données avant leur analyse.
- Documenter les méthodes de prédiction et conserver les résultats de façon reproductible.

## Arborescence

```text
Depot_Git_prediction_thermodynamique_additifs/
├── README.md
├── LICENSE
├── .gitignore
├── docs/
│   └── gestion_donnees.md
├── data/
│   ├── README.md
│   ├── raw/README.md
│   ├── processed/
│   │   ├── README.md
│   │   └── yatim_2026_22MEE_enthalpie_exces.csv
│   └── templates/
│       ├── README.md
│       ├── dictionnaire_colonnes.md
│       └── proprietes_thermodynamiques.csv
├── references/
│   ├── README.md
│   └── bibliographie_zotero.ris
├── results/
│   ├── README.md
│   └── enthalpie_exces_max_litterature.csv
└── scripts/README.md
```

## Organisation des données

Les fichiers Excel peuvent être utilisés pour la saisie et le suivi courant. Pour les échanges et les analyses automatisées, une copie tabulaire au format CSV UTF-8 est recommandée. Le fichier `data/templates/proprietes_thermodynamiques.csv` fournit un modèle de colonnes. Les données brutes sont conservées séparément des données nettoyées et transformées.

Chaque valeur doit être accompagnée, autant que possible, de sa référence ou de son DOI, de la substance ou composition concernée, de la propriété, de la température, de la pression, de l’unité, de la méthode et de l’incertitude rapportée. Les données d’exemple ne doivent pas être présentées comme des mesures réelles.

## Utilisation

1. Déposer les données sources dans `data/raw/` après vérification de leurs conditions de réutilisation.
2. Documenter les transformations et enregistrer les données traitées dans `data/processed/`.
3. Placer les scripts d’analyse et de prédiction dans `scripts/`.
4. Ajouter une note de méthode et les paramètres employés dans `docs/`.
5. Enregistrer les résultats reproductibles dans `results/`, avec un lien vers le script et les données correspondants.

Les fichiers volumineux, les fichiers personnels et les données soumises à des restrictions ne doivent pas être ajoutés au dépôt. Les sources des données doivent être citées et leurs licences respectées.

## État du projet

Cette structure est un point de départ à compléter au fur et à mesure de l’avancement du travail. Les substances, propriétés et méthodes retenues seront précisées dans la documentation du projet.

## Licence

La licence MIT s’applique aux scripts et éléments originaux de code de ce dépôt, sous l’attribution `Raya-git` indiquée dans `LICENSE`. Elle ne s’étend pas automatiquement aux données, articles, figures ou contenus provenant de tiers, qui restent soumis à leurs propres conditions de réutilisation.

## Note sur la préparation du dépôt

La structure et les textes de départ ont été préparés avec l’aide d’un assistant d’intelligence artificielle. Ils constituent un cadre de travail : les choix scientifiques, les méthodes, les références et les données devront être vérifiés et complétés par l’autrice du projet avant toute utilisation dans un travail de recherche.
