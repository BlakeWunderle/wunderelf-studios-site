# wunderelfstudios.com

The Wunderelf Studios website: the studio's games and apps (Parting Shadows, Wunderelf Sports and Wunderelf
Workshop), the About page, the press kit and the contact form. Built with Astro and Tailwind CSS.

## Running it

Needs Node 22.12 or later.

```sh
npm install
npm run dev      # http://localhost:4321
npm run build    # static site in ./dist
npm run preview  # serve ./dist locally
```

## Where things live

- **Pages:** `src/pages/`, one `.astro` file per route. Copy is written in the pages.
- **Navigation:** `src/data/nav.ts`, used by both the navbar and the footer.
- **Images and video:** `public/images/` and `public/videos/`. The press kit downloads are in `public/press/`.

## Deploying

Netlify builds and publishes the site. `public/_redirects` holds the redirects, and the contact form uses
Netlify Forms.
