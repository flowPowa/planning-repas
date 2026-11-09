# Planning des repas

Planifiez un repas par jour par glisser-déposer et obtenez automatiquement la liste de courses de la semaine, classée par rayon.

- Fonctionne dans le navigateur, sur ordinateur et sur téléphone.
- S'installe comme une application (écran d'accueil) et marche sans connexion.
- Les données restent sur l'appareil de chaque personne. Pensez à exporter une sauvegarde de temps en temps (section « Sauvegarde » en bas de la page).

## Fichiers

| Fichier | Rôle |
|---|---|
| `index.html` | L'application entière : page, styles, plats et logique |
| `manifest.webmanifest` | Nom, icône et couleurs de l'application installée |
| `sw.js` | Garde l'application disponible hors connexion |
| `icons/` | Icônes de l'application |

## Mettre à jour le site

Remplacez le fichier modifié dans le dépôt (Add file → Upload files → Commit changes). Le site se met à jour en quelques minutes ; l'application installée reçoit la nouvelle version à sa prochaine ouverture avec connexion.
