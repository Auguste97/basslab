# BassLab V1 — Dark Studio

## Contenu
- `index.html` : application complète (interface, navigation, séances, répertoire, suivi, stockage local).
- `manifest.webmanifest` : métadonnées PWA.
- `sw.js` : cache hors connexion.
- `icon.svg`, `icon-192.png`, `icon-512.png` : icônes.

## Fonctionnalités V1
- Dashboard et navigation mobile-first.
- Première séance guidée de 15 minutes sur les arpèges majeurs et mineurs.
- Validation des 4 étapes et sauvegarde locale.
- Historique des séances.
- Répertoire personnel avec ajout/suppression de chansons.
- Export JSON des données.
- Parcours pédagogique initial.
- Cache PWA pour les visites suivantes.

## Données et confidentialité
Les données sont conservées dans le `localStorage` du navigateur sur cet appareil. Elles ne sont pas synchronisées entre appareils. Utiliser « Exporter mes données » pour conserver une sauvegarde JSON.

## Tester sur ordinateur
Ouvrir `index.html` dans un navigateur. La navigation et le stockage local fonctionnent. Le mode PWA/offline nécessite un hébergement HTTPS (ou localhost).

## Installer sur iPhone X
1. Héberger tous les fichiers du dossier sur un site HTTPS (par exemple GitHub Pages).
2. Ouvrir l'URL dans Safari sur l'iPhone.
3. Appuyer sur Partager, puis « Sur l'écran d'accueil ».
4. Ajouter BassLab.

Pour tester le mode hors connexion, ouvrir une première fois l'application en ligne, puis la relancer après chargement.

## Limites assumées de cette V1
- Pas de compte utilisateur ni synchronisation cloud.
- Pas encore de notifications quotidiennes.
- Pas encore d'analyse audio automatique.
- Le suivi des compétences reste volontairement indicatif : la validation pédagogique réelle sera développée dans les versions suivantes.
