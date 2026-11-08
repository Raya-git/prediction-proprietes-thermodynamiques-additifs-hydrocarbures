# Dictionnaire du modèle CSV

Le fichier `proprietes_thermodynamiques.csv` contient une observation par ligne. Utiliser l’encodage UTF-8, le point comme séparateur décimal et les unités précisées ci-dessous. Laisser un champ vide lorsque l’information n’est pas disponible ; ne pas saisir zéro pour représenter une donnée manquante.

| Colonne | Description | Consigne |
|---|---|---|
| `id_observation` | Identifiant unique de l’observation | Créer un identifiant stable, par exemple OBS0001. |
| `source_doi` | DOI de l’article ou de la source | Saisir le DOI sans le préfixe `https://doi.org/` si disponible. |
| `reference` | Référence bibliographique ou nom de la base | Permet de retrouver l’origine de la valeur. |
| `nom_substance_1`, `CAS_1` | Premier constituant | Indiquer le nom et le numéro CAS lorsqu’ils sont connus. |
| `nom_substance_2`, `CAS_2` | Deuxième constituant | Laisser vide pour une substance pure. Pour les mélanges à plus de deux constituants, préciser leur composition dans un fichier associé. |
| `fraction_molaire_1` | Fraction molaire du premier constituant | Valeur comprise entre 0 et 1 ; préciser la convention de composition pour les mélanges multicomposants. |
| `propriete` | Propriété thermodynamique considérée | Utiliser un nom explicite et constant dans tout le jeu de données. |
| `valeur`, `unite` | Valeur rapportée et son unité | Ne pas mélanger plusieurs unités pour une même propriété sans documenter la conversion. |
| `temperature_K` | Température | Saisir en kelvins. |
| `pression_kPa` | Pression | Saisir en kilopascals. |
| `type_donnee` | Nature de la valeur | Utiliser `experimentale`, `predite` ou `evaluee` selon la source. |
| `methode` | Méthode expérimentale, modèle ou algorithme | Indiquer le nom et, si nécessaire, la version et les paramètres principaux. |
| `incertitude` | Incertitude rapportée ou estimée | Préciser sa définition et son unité dans `commentaire`. |
| `commentaire` | Informations complémentaires | Ajouter les conditions, conversions ou réserves nécessaires à l’interprétation. |

Avant analyse, vérifier les unités, la cohérence des fractions molaires, les doublons et la correspondance de chaque valeur avec sa source. Ce gabarit ne contient aucune donnée expérimentale réelle.
