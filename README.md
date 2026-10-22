# Mohana Akilan B.V - Portfolio (React + Vite)

Frontend-only React portfolio. No backend.

## Run locally
```bash
npm install
npm run dev        # http://localhost:5173
```

## Production build
```bash
npm run build      # outputs to dist/
npm run preview
```

## Deploy to Vercel

**Option A: GitHub (recommended)**
1. Push this folder to a GitHub repo (do not commit `node_modules`).
2. On vercel.com choose "Add New > Project" and import the repo.
3. Vercel detects **Vite** automatically. Build command `npm run build`, output directory `dist`. Click Deploy.

**Option B: Vercel CLI**
```bash
npm i -g vercel
vercel          # preview
vercel --prod   # production
```

## Edit content
- All text, skills, experience, links: `src/data.js`
- Colors and fonts: variables at the top of `src/index.css`
- Photo and resume: replace files in `public/assets/` (keep the same file names, or update `src/data.js`)
