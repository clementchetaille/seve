# Sève — Restaurant Franco-Méditerranéen

Site fictif créé pour le portfolio [heyclem.dev](https://heyclem.dev)

## Stack
- React + Vite
- CSS Modules par composant
- Déployable sur GitHub Pages

## Installation

```bash
npm install
npm run dev
```

## Déploiement GitHub Pages

1. Crée un repo GitHub nommé `seve`
2. Dans `vite.config.js`, vérifie que `base: '/seve/'` correspond bien au nom de ton repo
3. Build + push :

```bash
npm run build
# Pousse le dossier dist/ sur la branche gh-pages
```

Ou avec gh-pages :
```bash
npm install --save-dev gh-pages
# Ajoute dans package.json > scripts : "deploy": "gh-pages -d dist"
npm run deploy
```

## Structure

```
src/
├── components/
│   ├── Navbar.jsx / .css
│   ├── Hero.jsx / .css
│   ├── Concept.jsx / .css
│   ├── Menu.jsx / .css
│   ├── Ambiance.jsx / .css
│   ├── Reservation.jsx / .css
│   └── Footer.jsx / .css
├── App.jsx
├── App.css
├── main.jsx
└── index.css
```

## Palette

| Nom | Valeur |
|-----|--------|
| Cream | `#F7F3EE` |
| Warm | `#EDE7DC` |
| Sage | `#7A9B7E` |
| Sage Dark | `#4A6B4F` |
| Terra | `#C4714A` |
| Ink | `#1E2420` |
