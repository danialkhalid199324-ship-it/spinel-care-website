# Spinel Care — Website

Premium NDIS provider website for Spinel Care, serving Melbourne, Greater Melbourne and Victoria.

## Type
Static HTML site styled with Tailwind (via CDN). **No build step.** Folder-per-route clean URLs.

## Pages / routes
`/` · `/about` · `/services` · `/ndis-guide` · `/careers` · `/careers-registration` · `/contact` · `/client-referral` · `/privacy-policy` · `/terms-of-service` · `/complaints`

## Local preview
```bash
npm run dev      # serves at http://localhost:3000 via `serve`
```

## Deploy
Hosted on Vercel as a static site (Framework preset: **Other**, no build command needed).
`vercel.json` enables clean URLs.

## Notes
- Forms are **front-end only** (no backend yet) — client-side validation + success message.
- Contact email: info@spinelcare.com.au
- Tailwind is loaded via CDN; for production hardening, consider compiling Tailwind to a static CSS file.
