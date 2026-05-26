# Portfolio — Anthony Cernon

Portfolio personnel en cybersécurité et réseaux, développé en React (JSX) sans bundler — rendu directement dans le navigateur via Babel standalone.

## Structure

```
portefolio/
├── index.html   # Structure HTML, imports CDN
├── styles.css   # CSS de base (reset + overflow)
└── app.jsx      # Application React complète (composants, données, thème)
```

## Stack

- **React 18** — chargé via CDN (UMD)
- **Babel standalone** — transpile le JSX dans le navigateur
- Pas de bundler, pas de dépendances npm

## Lien portefolio

[https://spp4tme.github.io/portefolio/](https://spp4tme.github.io/portefolio/)

## Sections

- **Hero** — intro avec animation CRT au chargement
- **À propos** — présentation et faits clés
- **Parcours** — timeline alternée
- **Compétences** — grille avec barres de progression
- **Certifications** — SecNumAcadémie (ANSSI), Pix
- **Projets** — cylindre holographique 3D cliquable
- **Contact** — formulaire (Formspree) + liens
