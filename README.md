# Outil Absences – PWA

Cette version est conçue pour être installée sur iPhone/iPad depuis Safari via « Sur l’écran d’accueil ».

## Mise en ligne
1. Créer un dépôt GitHub public.
2. Envoyer TOUS les fichiers de ce dossier à la racine du dépôt.
3. GitHub → Settings → Pages → Deploy from branch → `main` → `/ (root)`.
4. Ouvrir l'adresse GitHub Pages dans Safari sur l'iPhone.
5. Partager → Sur l'écran d'accueil → Ajouter.

## Fonctionnement
- Les paramètres et l'historique sont conservés localement sur l'appareil.
- Export/import JSON pour sauvegarder ou transférer les données.
- Le bouton « Préparer l'e-mail » ouvre le client mail avec destinataire, CC, objet et corps préremplis.
- iOS ne permet pas à une PWA classique de joindre automatiquement un fichier à un mail `mailto:`. Le certificat est donc sélectionné dans le formulaire mais doit être joint manuellement dans le mail.
- Le fonctionnement hors connexion est prévu après le premier chargement grâce au service worker.
