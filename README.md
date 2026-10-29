# Navdeep Sahota portfolio

A Next.js portfolio built with React, a Three.js hero scene, and JSON project data. The cherry, old saffron, and gold visual palette carries through the responsive scrapbook-inspired layout.

## Run locally

Install Node.js, then from this folder run:

```bash
npm install
npm run dev
```

Open `http://localhost:3000` in your browser. Use `npm run build` to create the production build and `npm run start` to serve it.

## Add a project

1. Put its MP4 file in `public/assets/project-videos/`.
2. Add an object to `data/projects.json` with `title`, `category`, `duration`, and a `video` path starting with `/assets/project-videos/`.

The project gallery reads this JSON file and renders a card for each entry.

## Files

- `app/page.jsx` — portfolio page and React project cards
- `app/globals.css` — responsive page styling
- `components/HeroScene.jsx` — interactive Three.js car model
- `data/projects.json` — project catalog
- `public/assets/project-videos/` — supplied project previews

The contact section is ready for your preferred email or social link when you want to add one.
