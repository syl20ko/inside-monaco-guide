# Inside Monaco : guide des améliorations

Mini-site privé présenté à M. Simonnet (inside-monaco.com), préparé le 2 octobre 2026.

- `index.html` : version chiffrée (AES-256-GCM), seule version publiée.
- `src/shell.html` : coquille (écran mot de passe + styles), `src/guide-content.html` : contenu, `img/` : captures recadrées. Non publiés.
- `node build.js MOTDEPASSE` : génère `apercu.html` (clair, relecture locale) et `index.html` (chiffré).
