# BG IT Solutions — site vitrine

Site web statique (HTML / CSS / JS, sans dépendance de build) pour BG IT Solutions,
société de services informatiques accompagnant les PME et le secteur public :
installation, support bureautique et serveurs, MCO, cybersécurité, infogérance,
ainsi que création de sites web, d'applications et optimisation par l'IA
(grand public ou locale/souveraine).

## Structure

- `index.html` — Accueil
- `services.html` — Détail des services
- `secteurs.html` — PME privées vs secteur public
- `a-propos.html` — Équipe, valeurs, approche
- `contact.html` — Formulaire de contact
- `css/style.css` — Feuille de style unique
- `js/script.js` — Menu mobile, FAQ, formulaire
- `assets/` — Logo et médias

## Aperçu local

Aucune installation requise : ouvrez `index.html` directement dans un navigateur,
ou lancez un petit serveur local :

```bash
python3 -m http.server 8000
```

puis ouvrez `http://localhost:8000`.

## Déploiement

Site 100% statique : compatible avec GitHub Pages, Netlify, Vercel ou tout
hébergement statique classique.
