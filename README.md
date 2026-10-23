# Outil Absences PWA — v6

Cette version applique la règle 08:30 dans le texte d'information et dans le choix entre l'heure du rendez-vous et l'heure de départ.

- Départ avant 08:30 : « Je vous informe de mon rendez-vous spécialiste prévu le 06.10.2026. Heure du rendez-vous 07:00. »
- Départ à partir de 08:30 : « Je vous informe de mon rendez-vous spécialiste prévu le 06.10.2026 à 10:30. Heure de départ : 08:30. »

Le cache du service worker est passé en v6.


Version 7 : règle rendez-vous 10:30. Avant 10:30, affichage « Heure du rendez-vous » sur une ligne séparée. À partir de 10:30, affichage « Heure de départ » sur une ligne séparée, sans heure après la date.


Version 8 : conversion automatique des listes d’adresses séparées par des points-virgules en listes séparées par des virgules lors de la préparation du mail, pour compatibilité iOS. Les paramètres existants peuvent rester inchangés. Cache PWA v8.


Version 9 : remplace le motif « Rendez-vous administratif » par « Congé » (migration automatique des paramètres existants). Le motif Congé affiche une période de congé et le choix « Vacances » / « Heures mobiles ». Le mail est adapté pour une date unique ou une période, puis indique le compte utilisé. Les autres fonctions de la v8 sont conservées. Cache PWA v9.
