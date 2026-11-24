# Serena Lee Photography

One-page personal site for Serena Lee, a freelance wedding and portrait photographer. Plain HTML and CSS, no build step.

## Structure

- `index.html` is the whole site: hero, portfolio grid, about, contact.
- `images/` holds the portfolio photos.
- `vercel.json` sets caching and security headers for Vercel.

## Add photos

Put the file in `images/`, then replace a placeholder frame in `index.html`:

```html
<div class="frame"><img src="images/your-photo.jpg" alt="Describe the photo" width="1200" height="1500"></div>
```

Frames are 4:5 portrait and crop to fit.

## Edit the text

The tagline, about text and email address (`hello@serenalee.com`) in `index.html` are placeholders. Replace them with Serena's own.

## Deploy on Vercel

1. Import this repo at https://vercel.com/new.
2. Set Framework Preset to **Other**. Leave Build Command and Output Directory empty.
3. Deploy. Every push to `main` redeploys.

Or from the command line: `npx vercel --prod`.

## Preview locally

```
npx serve .
```
