# Lag0n URLs

Simple static image / asset hosting for **Lag0n**.

Live site after deploy:
```
https://lag0nurls.vercel.app
```

Individual images:
```
https://lag0nurls.vercel.app/assets/your-image.png
```

## How to add images

1. Put the file in the `assets/` folder  
2. Add the filename to `assets.json` (example below)  
3. Commit & push → Vercel auto-deploys

### Example `assets.json`
```json
[
  "logo.png",
  "banner.webp",
  "icon.svg"
]
```

The homepage will automatically show a searchable gallery with Open + Copy buttons for every entry.

## Structure
```
├── index.html      ← gallery page
├── assets.json     ← list of filenames (keeps the gallery updated)
├── assets/         ← put your images here
├── vercel.json     ← cache + CORS headers
└── README.md
```
