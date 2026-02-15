# QuantFX Innovations Website

Simple static marketing website for QuantFX Innovations.

## Local preview

```bash
python3 -m http.server 4173
```

Then open: http://127.0.0.1:4173

## Deploy to Vercel

1. Push this folder to GitHub/GitLab/Bitbucket.
2. In Vercel, click **Add New → Project** and import the repository.
3. Framework preset: **Other** (no build command needed).
4. Deploy.

## Connect custom domain

1. In Vercel project: **Settings → Domains**.
2. Add `quantfxinnovations.com` and `www.quantfxinnovations.com`.
3. At your domain registrar, set DNS records exactly as Vercel shows:
   - Usually `A` record for apex (`@`) to `76.76.21.21`
   - `CNAME` for `www` to `cname.vercel-dns.com`
4. Wait for DNS propagation, then set primary domain in Vercel.

> If you want, I can also help draft SEO metadata, Open Graph image setup, and Thai-language version pages.
