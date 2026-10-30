# TalcoWatcher

Application mobile (PWA) pour lire des vidéos Cloudinary et Google Drive.

## Mettre en ligne (GitHub Pages)
1. Envoie tous les fichiers de ce dossier à la racine d'un dépôt GitHub.
2. Settings → Pages → Branch `main` → Save.
3. Ouvre le lien `https://TON-PSEUDO.github.io/TON-DEPOT/`.

## Installer sur le téléphone
- **iPhone (Safari)** : Partager → Sur l'écran d'accueil.
- **Android (Chrome)** : menu ⋮ → Installer l'application.

## Ajouter une vidéo
Dans `index.html`, copie une ligne dans `VIDEOS` et change `nom`, `createur`, `lien`.

## Mettre à jour l'appli
Après une modification, change `talcowatcher-v3` en `talcowatcher-v4` dans `sw.js`.

## Si l'installation n'apparaît pas
- Il faut ouvrir le lien HTTPS dans **Chrome** (Android) ou **Safari** (iPhone), pas dans une appli (Discord, Instagram, Claude...).
- Dézippe avant d'envoyer sur GitHub (ne pas envoyer le .zip tel quel). `index.html` suffit pour installer ; `sw.js` ajoute le mode hors-ligne.
- Le bas de la page d'accueil affiche « TalcoWatcher v3 » : si tu vois autre chose, tu ouvres une ancienne version.
- Un bouton « Installer » apparaît en haut de la page quand l'installation est possible.
