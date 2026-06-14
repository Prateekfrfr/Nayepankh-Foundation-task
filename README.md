# Nayepankh

Nayepankh is a responsive Next.js website for a non-profit/charity. It provides pages for causes, donations, volunteering, contact, and impact information.

## Key Features

- Multi-page Next.js app with server-rendered pages and client components.
- Reusable UI components: hero, navigation, cause cards, CTA, footer, and stats.
- Tailwind CSS + PostCSS for styling and responsive layouts.
- Motion + accessible icons via `framer-motion` and `lucide-react`.

## Tech Stack

- Next.js 16 (App Router)
- React 19
- Tailwind CSS
- Framer Motion
- TypeScript

## Local Development

Install dependencies and run the dev server:

```bash
npm install
npm run dev
```

Open http://localhost:3000 in your browser.

Available npm scripts (from `package.json`):

- `dev`: Run Next.js dev server
- `build`: Build for production
- `start`: Start production server
- `lint`: Run ESLint

## Project Structure

- `app/` — Next.js app routes and pages (`page.tsx`, nested folders for pages)
- `components/` — UI components (`Navbar`, `Hero`, `CauseCards`, etc.)
- `lib/` — site data and helpers (`site-data.ts`)
- `public/images/` — static images
- `README.md` — this file

## Deployment

You can deploy to Vercel (recommended) or any hosting that supports Next.js. For Vercel, connect the repository and set the framework to Next.js; Vercel will handle builds and previews.

## Contributing

- Fork the repo and open a pull request for changes.
- Run `npm run lint` and ensure the app builds with `npm run build` before submitting.

## License & Contact

Include your license here (e.g. MIT) and contact info for maintainers or project owners.

---

If you want, I can also: commit this change and attempt to push it to the repository remote. Reply to proceed with commit and push.
