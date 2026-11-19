# Alice Huang Photography

One-page personal website for a wedding and portrait photographer. Plain HTML and CSS with a few lines of JavaScript, no build step.

## Run it

Open `index.html` in a browser, or serve the folder with any static host.

## Deploy to Vercel

This is a static site with no build step, so Vercel serves it as is.

1. In Vercel, choose Add New > Project and import this repository.
2. Leave the framework preset as Other. `vercel.json` already sets no build or install command and serves the repo root.
3. Click Deploy. Every push to `main` redeploys.

With the CLI: `npx vercel` for a preview, `npx vercel --prod` for production.

Images in `images/` are cached for a year. If you replace a photo, give the new file a new name.

## Edit it

- Replace the placeholder frames in the portfolio grid with `<img>` tags (see the comment above the grid in `index.html`). Frames crop to 4:5.
- The email address, about text and captions are sample copy.
