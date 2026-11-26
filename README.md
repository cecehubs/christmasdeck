# 204.ai · Holiday Party Magic Booth deck

One-page interactive sales deck for 204.ai's Holiday (Christmas / New Year) Magic Booth package, in English and European Portuguese.

- Open `index.html` in a browser. No build step.
- Language switch (EN / PT) is in the top bar. Link straight to Portuguese with `?lang=pt`.
- All images and videos are in `img/`. The page is marked noindex (not for search engines).
- The contact form opens the visitor's email app with a pre-filled message to hello@204.ai.

## Adding it to 204.ai (repo 204-ai/204.ai-web)

Copy `index.html` and the `img/` folder into `public/holidaydeck/` in the website repo, then build and deploy as usual.
It is a standalone static page and does not touch the app. Tested: `npm run build` (incl. check-curated) and `node scripts/media-audit.mjs` pass,
and the page serves at `/holidaydeck/`. Live URL after deploy: https://204.ai/holidaydeck/

© 204.ai · A brand of Dao Llama Labs AG
