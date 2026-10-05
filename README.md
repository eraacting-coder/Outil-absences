# Outil Absences — version 3 du cache PWA

Cette version contient les corrections suivantes :

- Règle de rendez-vous : si l'heure de départ calculée est avant 07:45, l'e-mail utilise l'heure du rendez-vous.
- Le responsable est affiché directement dans le formulaire d'absence.
- Service Worker v3 : ancien cache supprimé automatiquement.
- La page principale utilise d'abord le réseau afin que les mises à jour GitHub Pages soient prises en compte.

## Installation GitHub Pages

Copier tous les fichiers du dossier dans le dépôt GitHub Pages et remplacer les anciens fichiers.

Fichiers à conserver :
- index.html
- manifest.json
- service-worker.js
- icon-180.png
- icon-192.png
- icon-512.png

Après publication, ouvrir une fois le site dans Safari. Si l'ancienne version apparaît encore, fermer complètement Safari puis rouvrir le site.
