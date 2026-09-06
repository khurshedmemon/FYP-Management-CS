# FYP Portal

Responsive Final Year Projects portal built with React + Vite, designed for GitHub Pages.

## Features
- Search by title, abstract, supervisor, category, and members
- Batch, supervisor, category and status filters
- Clickable project detail pages
- Abstract, supervisor, batch, status, members and technologies
- Resource center for PDF/DOCX/XLSX/PPTX and other files
- Responsive desktop/tablet/mobile design
- GitHub Pages deployment workflow
- Optional Node.js/Express starter for future database-backed API

## Run
```bash
npm install
npm run dev
```

## Add data
Edit `src/data/fyps.js`.

## Add resources
Put real files in `public/resources/` and update the `resources` array in `src/App.jsx`.

## GitHub Pages
Push to `main`, then enable **Settings → Pages → GitHub Actions**. The included workflow builds and deploys `dist/`.
