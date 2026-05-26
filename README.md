<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://ai.google.dev/static/site-assets/images/share-ais-513315318.png" />
</div>

# Run and deploy your AI Studio app

This contains everything you need to run your app locally.

View your app in AI Studio: https://ai.studio/apps/346daf53-ac49-4427-aa2f-f661b14a7917

## Run Locally

**Prerequisites:**  Node.js

1. Install dependencies:
   `npm install`
2. Set the `GEMINI_API_KEY` in [.env.local](.env.local) to your Gemini API key
3. Run the app:
   `npm run dev`

## Deploy To GitHub Pages

Repository: `https://github.com/yeweilulu/presentation3`

1. Install dependencies:
   `npm install`
2. One-click deploy:
   `npm run deploy`

The deploy flow will automatically:

- run `npm run build`
- publish the `dist` directory to the `gh-pages` branch

Vite is configured with:

- `base: '/presentation3/'`

Published URL:

- `https://yeweilulu.github.io/presentation3`
