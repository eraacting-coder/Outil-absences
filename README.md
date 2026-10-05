# Outil Absences PWA v5

Correction de la règle de rédaction des rendez-vous.

- Si l’heure de départ calculée est **avant 07:45** :
  `Je vous informe de mon rendez-vous spécialiste prévu le 06.10.2026. Heure du rendez-vous 07:00.`
- Si l’heure de départ calculée est **à 07:45 ou après** :
  `Je vous informe de mon rendez-vous spécialiste prévu le 06.10.2026 à 07:45. Heure de départ : 07:45.`

Le Service Worker passe en cache v5 pour forcer la prise en compte de la nouvelle logique.
