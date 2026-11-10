MARIELLE EN 90 DAYS — PREMIÈRE VERSION

Contenu :
- index.html : application complète
- manifest.webmanifest : configuration installable (PWA)
- service-worker.js : cache hors connexion
- icon.svg : icône

TEST RAPIDE :
1. Ouvre index.html dans un navigateur pour tester les fonctions principales.
2. Pour installer comme une vraie application Android, héberge le dossier sur un site HTTPS (par exemple GitHub Pages, Netlify ou Vercel).
3. Ouvre l'adresse HTTPS dans Chrome Android puis choisis « Installer l'application » ou « Ajouter à l'écran d'accueil ».

DONNÉES :
Les données sont stockées localement dans le navigateur (localStorage). Utilise « Exporter mes données » régulièrement pour créer une sauvegarde JSON.

NOTIFICATIONS :
La première version utilise les notifications du navigateur lorsque l'application est ouverte à l'heure définie. Les notifications garanties lorsque l'application est fermée nécessitent une infrastructure de notifications push (service distant), qui n'est pas incluse dans cette version.

CONFIDENTIALITÉ :
Aucun compte ni serveur de données n'est utilisé. Évite d'enregistrer des informations très sensibles.
