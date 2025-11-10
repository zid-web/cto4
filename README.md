# CTO Management

Prototype éducatif pour les techniques CTO — déployable via Vercel/Netlify.

Contenu:
- React + Vite
- react-three-fiber pour animations 3D
- Quiz bilingue FR/EN (importable JSON)
- Admin: export CSV experts / quiz
- CI: GitHub Actions (Vercel + Netlify examples)

## Lancer en local
```bash
npm install
npm run dev
```

## Déploiement
- Vercel recommandé: configurer secrets `VERCEL_TOKEN`, `VERCEL_ORG_ID`, `VERCEL_PROJECT_ID`.
- Netlify optionnel: `NETLIFY_AUTH_TOKEN`, `NETLIFY_SITE_ID`.
