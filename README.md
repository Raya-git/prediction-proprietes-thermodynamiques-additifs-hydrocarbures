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

## État du projet

Cette structure est un point de départ à compléter au fur et à mesure de l’avancement du travail. Les substances, propriétés et méthodes retenues seront précisées dans la documentation du projet.

## Licence

La licence MIT s’applique aux scripts et éléments originaux de code de ce dépôt, sous l’attribution `Raya-git` indiquée dans `LICENSE`. Elle ne s’étend pas automatiquement aux données, articles, figures ou contenus provenant de tiers, qui restent soumis à leurs propres conditions de réutilisation.
