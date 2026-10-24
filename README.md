# Meal-Planner
Meal Planner familial

Tableau de repas hebdomadaire (midi et soir) qui pioche dans une base de recettes locale.

## Utilisation

1. Garder `meal_planner.html` et `recettes.csv` dans le même dossier.
2. Ouvrir `meal_planner.html` avec Chrome ou Edge.
3. Cliquer une fois sur « Choisir recettes.csv » : l'application lit puis met à jour ce fichier automatiquement.

Avec un autre navigateur, la base reste dans le navigateur et se sauvegarde avec « Exporter en CSV ».

## Fonctionnement

- Tirage au sort de la semaine, correction d'un repas à la fois, repas « ficelés » conservés d'un tirage à l'autre.
- Saisonnalité d'après la date de l'ordinateur (modifiable).
- Notes séparées pour le midi et pour le soir : « Valider la semaine » les fait monter, les pouces les ajustent. Plus la note est haute, plus le plat sort.

## Base de données

`recettes.csv` (séparateur `;`, UTF-8) : `id`, `nom`, `ingredients`, `saisons`, `note_midi`, `note_soir`, `nb_midi`, `nb_soir`, `derniere_utilisation`. Il peut être édité dans Excel (fermé dans l'application au moment de valider une semaine) ou depuis le bouton « Recettes ».
