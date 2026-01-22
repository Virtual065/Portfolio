# Portfolio

Personal portfolio website showcasing my work as a Game Developer & Junior Software Engineer.

**Live site:** [virtual065.github.io/Portfolio](https://virtual065.github.io/Portfolio)

## Tech Stack

- **Astro** - Static site framework
- **TypeScript** - Type-safe JavaScript
- **Tailwind CSS** - Utility-first styling
- **GSAP** - Smooth animations

## Features

- Responsive design (mobile & desktop)
- Dark theme with customizable accent color
- Scroll-triggered animations
- Code samples with syntax display
- Timeline/journey section
- Automatic deployment via GitHub Actions

## Local Development

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build
```

Dev server runs at `http://localhost:4321/Portfolio`

## Customization

### Change accent color

Edit `src/styles/global.css`:

```css
:root {
  --accent: #1e3a5f; /* Change this value */
}
```

### Update personal info

Edit `src/pages/index.astro`:

```js
const config = {
  name: "Your Name",
  tagline: "Your Title",
  email: "your@email.com",
  github: "yourusername",
};
```

## Project Structure

```
src/
├── components/
│   ├── Hero.astro
│   ├── WhatIDo.astro
│   ├── History.astro
│   ├── Languages.astro
│   ├── CodeShowcase.astro
│   ├── Software.astro
│   └── Contact.astro
├── layouts/
│   └── Layout.astro
├── pages/
│   └── index.astro
└── styles/
    └── global.css
```

## Deployment

Automatically deploys to GitHub Pages on push to `master` via GitHub Actions.
