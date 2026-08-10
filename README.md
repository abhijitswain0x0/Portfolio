# Abhijit Swain — Portfolio

Personal portfolio website for **Abhijit Swain**, Software Engineer based in Odisha, India and founder of **Team Origin Logic**.

Built with [Astro](https://astro.build) and styled with a retro terminal / pixel-art aesthetic — boot screen, blinking cursor, and pixel logo included.

## ✨ Features

- Terminal-style boot screen animation
- Pixel-art logo and pixel-styled typography
- Sections: Hero, About, Skills, Projects, Contact
- Scroll-reveal animations
- Fully responsive

## 🚀 Project Structure

```text
/
├── public/
│   ├── favicon.svg
│   └── scripts/
│       └── reveal.js
├── src/
│   ├── components/
│   │   ├── Nav.astro
│   │   ├── Hero.astro
│   │   ├── About.astro
│   │   ├── Skills.astro
│   │   ├── Projects.astro
│   │   ├── ProjectCard.astro
│   │   ├── Contact.astro
│   │   ├── Footer.astro
│   │   └── Boot.astro
│   ├── layouts/
│   │   └── BaseLayout.astro
│   ├── pages/
│   │   └── index.astro
│   └── styles/
│       └── global.css
├── astro.config.mjs
├── netlify.toml
└── package.json
```

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command           | Action                                           |
| :---------------- | :----------------------------------------------- |
| `pnpm install`    | Installs dependencies                            |
| `pnpm dev`        | Starts local dev server at `localhost:4321`      |
| `pnpm build`      | Build your production site to `./dist/`          |
| `pnpm preview`    | Preview your build locally, before deploying     |
| `pnpm astro ...`  | Run CLI commands like `astro add`, `astro check` |

## 📦 Requirements

- Node.js `>=22.12.0`
- pnpm

## 🚢 Deployment

Configured for deployment to Netlify via `netlify.toml`.

## 👀 Want to learn more?

Check the [Astro documentation](https://docs.astro.build) or jump into the [Astro Discord server](https://astro.build/chat).
