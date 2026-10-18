# Overwatch Tactics — prototype PWA

## Fonctionnalités
- Application responsive PC et Android.
- Galerie de portraits importés depuis `overwatch-hero-icons-main.zip`.
- Images de cartes importées depuis l’archive fournie.
- Fiches de héros, filtres, favoris.
- Cartes avec zoom, marqueurs Position / Regroupement / Danger / Itinéraire.
- Notes sur les marqueurs, suppression, export JSON.
- Compositions, contres, checklist, notes et export texte.
- Guide PDF inclus.
- Manifest PWA et cache hors ligne après le premier chargement.

## Lancer sur PC
Depuis ce dossier, exécuter `python -m http.server 8000`, puis ouvrir `http://localhost:8000`. Le double-clic sur index.html ne suffit pas pour charger les données et activer la PWA.

## Installer sur Android
Héberger le dossier sur un serveur HTTPS, ouvrir l’URL dans Chrome, puis choisir « Installer l’application » ou « Ajouter à l’écran d’accueil ».

Les favoris, annotations et notes sont stockés localement sur l’appareil. Certaines cartes sont historiques et identifiées comme telles. Ce prototype ne se connecte pas aux serveurs Blizzard.
