# Faultline 40k Website

This repository contains the source code for the **Faultline 40k** community website, a narrative tabletop gaming group based in the Bay Area, California.

The website is built using [Astro](https://astro.build/) for fast, static site rendering.

## 🚀 Getting Started

To run the project locally, install the dependencies and start the dev server:

```sh
npm install
npm run dev
```

The site will be available at `http://localhost:4321`.

## 🧞 Commands

All commands are run from the root of the project:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |

## 📁 Project Structure

```text
/
├── public/
├── src/
│   ├── assets/       # Images, custom icons, and other assets
│   ├── components/   # Reusable UI components (Header, etc.)
│   ├── layouts/      # Page layout templates
│   └── pages/        # Route pages (Welcome, What is Faultline, Join Us)
├── package.json
└── astro.config.mjs
```
