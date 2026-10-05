# Outil Absences PWA — v6

Cette version applique la règle 08:30 dans le texte d'information et dans le choix entre l'heure du rendez-vous et l'heure de départ.

- Départ avant 08:30 : « Je vous informe de mon rendez-vous spécialiste prévu le 06.10.2026. Heure du rendez-vous 07:00. »
- Départ à partir de 08:30 : « Je vous informe de mon rendez-vous spécialiste prévu le 06.10.2026 à 10:30. Heure de départ : 08:30. »

Le cache du service worker est passé en v6.


Version 7 : règle rendez-vous 10:30. Avant 10:30, affichage « Heure du rendez-vous » sur une ligne séparée. À partir de 10:30, affichage « Heure de départ » sur une ligne séparée, sans heure après la date.
