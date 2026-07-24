# Dominic — Stage Ready 2027

A mobile-first offline bodybuilding tracker built for Dominic's six-day offseason plan starting Monday, July 27, 2026.

## Fastest way to use it

### Computer
Open `index.html` in a browser. Logging and checklists save locally.

### iPhone / iPad home-screen installation
A PWA must be opened from an HTTPS website to install reliably. Upload this folder to Netlify, Vercel, GitHub Pages, or another static host. Then:

1. Open the hosted address in Safari.
2. Tap Share.
3. Tap **Add to Home Screen**.
4. Launch **Stage Ready** from the new icon.

## Data safety
Entries are stored in the browser on that device. Use **Settings → Export data** regularly. The resulting JSON file can be imported later.

## Included
- Six-day workout checklist
- Set-by-set weight, reps, and RIR logging
- Rest timer
- Daily calories, protein, steps, and water
- Bodyweight graph
- Annual phase map
- Offline cache when hosted
- Export/import backup

## Important
This is a training-management tool, not medical care or a guarantee of winning. Contest preparation should be supervised by qualified professionals.


## Dominic's Copy
This build has its own local-storage key and service-worker cache, so Dominic's logs remain separate from Maximus's app even when both are tested on the same device/browser.
