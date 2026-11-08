# BCA Computer Programming Team Website

The official site for the Bergen County Academies Computer Programming Team, the club that trains students for USACO, ACSL, and other competitive programming contests.

## What's on the site

- **Lessons:** the team's lesson archive, organized by topic
- **Competitions:** upcoming contests and how to prepare
- **News:** team announcements and results
- **Resources:** curated practice problems and references
- **About / Contact:** officers, meeting info, how to join

Content lives in JSON files (`cptsite/public/data/lessons.json`, `events.json`, `news.json`), so officers can update lessons and announcements without touching the code.

## Stack

Next.js (App Router, static export) · TypeScript · Tailwind CSS · Vanta.js animated background · GitHub Actions → GitHub Pages

## Development

```bash
cd cptsite
npm install
npm run dev
```

Pushing to `main` builds and deploys automatically via `.github/workflows/nextjs.yml`.
