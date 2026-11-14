# Lag0n URLs

Simple static image / asset hosting for **Lag0n**.

Deploy this repo to [Vercel](https://vercel.com) and your images will be available at:

```
https://lag0nurls.vercel.app/assets/your-image.png
```

(or whatever custom domain / project name you choose)

## How to use

1. Drop any images into the `assets/` folder
2. Commit & push
3. Vercel will automatically redeploy
4. Access them at `/assets/filename.ext`

## Example

```
assets/
  logo.png
  banner.webp
  icon.svg
```

→ `https://your-deployment.vercel.app/assets/logo.png`

## Configuration

- Long cache headers for assets (1 year)
- CORS enabled (`Access-Control-Allow-Origin: *`)
- Clean URLs enabled
