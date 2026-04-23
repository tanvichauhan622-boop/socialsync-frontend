# SocialSync — Frontend

Deployed on **Netlify**. Static HTML/CSS/JS — no build step needed.

## Deploy to Netlify

1. Push this folder to a GitHub repo (e.g. `socialsync-frontend`)
2. Go to netlify.com → "Add new site" → "Import from Git"
3. Select your repo — Netlify auto-detects `netlify.toml`
4. Click **Deploy**

## ⚠️ After deploying the backend to Railway

Open `index.html` and find this line near the top of the `<script>`:

```js
const BASE_URL = 'https://YOUR-RAILWAY-APP.up.railway.app';
```

Replace `YOUR-RAILWAY-APP` with your actual Railway subdomain, then push again.

Example:
```js
const BASE_URL = 'https://socialsync-production.up.railway.app';
```
