UAX BIOLOGIE — SITE INTERACTIF V3.1

UTILISATION SIMPLE
1. Décompressez le ZIP.
2. Ouvrez index.html dans Chrome, Edge, Firefox ou Safari.
3. Le site fonctionne hors ligne. La progression est enregistrée localement dans le navigateur.
4. Utilisez régulièrement « Exporter » pour créer une sauvegarde JSON.

NOUVEAUTÉS V3.1
- Accueil simplifié : séance du jour, maîtrise globale, prochain objectif et 5 priorités.
- Planning adaptatif : les séances en retard peuvent être transformées en rattrapages ciblés de 30 min maximum et replacées sur des créneaux libres.
- Reporter une séance cherche automatiquement le prochain créneau libre au lieu d’empiler les séances.
- Maîtrise par notion plus précise : cours, flashcards, QCM et stabilité dans le temps sont séparés.
- Contraste renforcé pour tous les états de réponses QCM en modes clair et sombre.
- Compatibilité avec la progression V3 et import des sauvegardes précédentes.

FONCTIONS CONSERVÉES
- 10 chapitres, 719 flashcards, 410 QCM dont 10 visuels.
- Répétition espacée, QCM adaptatifs, FR/ES, recherche, carnet d’erreurs, statistiques et concours blanc 30 min.
- PWA lorsqu’il est servi via HTTP/HTTPS.

DATE DU CONCOURS
Le 15 décembre 2026 reste une date indicative modifiable dans Planning tant que la date exacte n’est pas renseignée.

# UAX — référence uniquement

Ce dossier contient le projet UAX utilisé comme référence fonctionnelle.

Il sert notamment à comprendre :

- le moteur de planning ;
- la génération des séances ;
- les statuts fait / reporter / ignorer ;
- la logique de rattrapage ;
- la vue Aujourd’hui / Cette semaine / Jusqu’au concours ;
- l’adaptation des séances.

Lorsqu’une tâche concerne le planning, inspecter en priorité la logique JavaScript responsable :

- de la génération des séances ;
- du calcul des dates ;
- des statuts ;
- du report ;
- du rattrapage ;
- de la sélection des activités ;
- de l’affichage des différentes vues.

IMPORTANT :

- ne pas modifier ces fichiers ;
- considérer ce dossier comme strictement en lecture seule ;
- ne pas importer directement les données UAX dans le site SVT ;
- ne pas créer de dépendance runtime vers ce dossier ;
- ne pas copier aveuglément l’architecture ou le code UAX ;
- réimplémenter uniquement les principes utiles dans l’architecture propre du site SVT ;
- ne pas inclure ce dossier dans le build ou la publication du site ;
- si une logique UAX est réutilisée conceptuellement, l’adapter aux contraintes spécifiques de la Terminale.
