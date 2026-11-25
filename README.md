# FAST-GOOD CONSTRUCTION BTP — Site vitrine multipage

Site statique français composé de cinq pages HTML indépendantes :
- `index.html` — Accueil avec scène 3D interactive Three.js
- `apropos.html` — Présentation, engagements et zones d'intervention
- `services.html` — Cinq domaines de services
- `realisations.html` — Galerie de visuels architecturaux
- `contact.html` — Coordonnées et formulaire qui prépare un email

## Démarrer localement
Ouvrir `index.html` dans un navigateur récent. Pour un fonctionnement optimal, servir le dossier via un serveur HTTP local (par exemple `python -m http.server 8000`) puis ouvrir `http://localhost:8000`.

## Déploiement
Le dossier peut être publié sur GitHub Pages, Netlify, Vercel ou tout hébergement statique. Aucun backend n'est inclus. Le formulaire utilise `mailto:` et WhatsApp ouvre une conversation au numéro fourni.

## Technologies
HTML5, CSS3, JavaScript, Three.js (scène architecturale WebGL), GSAP (animation d'entrée) et IntersectionObserver (révélations au scroll). Les bibliothèques Three.js et GSAP sont chargées depuis des CDN ; une connexion internet est requise pour ces effets.

## À valider avant publication client
- Les visuels de la galerie sont extraits du PDF transmis et présentés comme références / illustrations, pas comme chantiers réalisés par FAST-GOOD. Remplacer ou légender avec les réalisations réellement attribuables à l'entreprise après validation.
- Confirmer les deux numéros, l'adresse email et l'adresse postale.
- Ajouter l'URL Facebook officielle lorsqu'elle sera fournie.
- Connecter un service de formulaire (Formspree, backend ou CRM) si l'on souhaite recevoir les demandes sans passer par le client email.
- Faire tester les pages, les performances et l'accessibilité sur les appareils cibles avant mise en production.

## Identité
Logo et palette cyan / bleu profond fournis par le client. Aucune référence à PRO'ROL-BTP n'est incluse.
