# Cursor — Landing Page (Static Frontend)

[![version](https://img.shields.io/badge/version-0.0.0-blue.svg)](./package.json) [![license](https://img.shields.io/badge/license-Add%20LICENSE-lightgrey.svg)](./LICENSE)

> A Vite-based static landing page inspired by the Cursor product, delivering a responsive, asset-driven UI and custom typography.

#Live Demo: [Link](https://cohort-assignment-cursor-landing-pa.vercel.app/)
---

## Table of contents
- [What this project does](#what-this-project-does)
- [Why this project is useful](#why-this-project-is-useful)
- [Key features](#key-features)
- [Get started](#get-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Development](#development)
  - [Build & Preview](#build--preview)
- [Project layout](#project-layout)
- [Where to get help](#where-to-get-help)
- [Maintainers & contributing](#maintainers--contributing)

---

## What this project does

**Cursor** is a static, responsive landing page built with Vite and plain HTML/CSS. It demonstrates a product marketing layout (hero, features, logos, reviews, changelog) and includes custom fonts and local assets.

## Why this project is useful

- Quick starting point for front-end experiments and UI composition.
- Demonstrates usage of local assets and custom web fonts.
- Minimal Vite configuration for fast local development and production builds.

## Key features

- Vite-based dev server and build tooling
- Single-page HTML/CSS layout (no JS frameworks required)
- Custom font integration (`CursorGothic`) and local assets under `public/`
- Mobile-friendly layout and reusable components (cards, grid sections)

## Get started

### Prerequisites

- Node.js (16+ recommended)
- npm or yarn

### Installation

1. Clone the repository.
2. Install dependencies:

```bash
npm install
```

### Development

Start the Vite dev server:

```bash
npm run dev
```

Open http://localhost:5173 (or the URL printed by Vite).

### Build & Preview

Produce an optimized build:

```bash
npm run build
```

Preview the production build locally:

```bash
npm run preview
```

## Project layout

- `index.html` — main entry and markup
- `src/style.css` — central stylesheet
- `public/Assest/` — images, logos, and other static assets
- `fonts/` and `CursorGothic-main/` — font files and font info
- `package.json` — scripts and dev dependencies (Vite)

> Tip: Edit `index.html` to change content and `src/style.css` for layout and styling.

## Where to get help

If you need assistance, see [docs/SUPPORT.md](./docs/SUPPORT.md) for recommended support channels and how to report issues.

## Maintainers & contributing

This repository is maintained by the project owners. We welcome contributions — please follow the short contribution notes in [docs/CONTRIBUTING.md](./docs/CONTRIBUTING.md).

If you plan to contribute major features, open an issue first to discuss the approach.

---

> If you want this repo to be published on GitHub, consider adding a `LICENSE` file (e.g., `MIT` or `Apache-2.0`) and CI configuration for automated builds and tests.
