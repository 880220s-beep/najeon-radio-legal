# Najeon Radio — Legal static site

Minimal static pages for Google OAuth consent-screen hosting.

## Files

| File | Role |
|------|------|
| `index.html` | Homepage — Najeon Radio publishing tool for YouTube uploads |
| `privacy.html` | Bilingual (EN + KR) privacy policy |
| `README.md` | This file |

## Filled values

- **Effective / last updated:** 2026-10-07
- **Channel:** [@najeonradio](https://www.youtube.com/@najeonradio) (`UChP2lvgu_-BSqdff9Mh3Ukw`)
- **GCP project:** `najeon-radio`
- **Hosting provider note in policy:** GitHub Pages (when published)

## Still needs a real value

Replace every **`[PLACEHOLDER: contact email]`** in `privacy.html` (and the source markdown if you keep it in sync) with the operator email for 손영태 / Najeon Radio before submitting OAuth for production.

Example: `you@example.com` — do not leave the yellow placeholder marker in a production-submitted URL.

## Intended URLs after GitHub Pages

Once the repo is public and Pages is enabled from this folder (or repo root with these files):

- Homepage: `https://<github-user>.github.io/najeon-radio-legal/`
- Privacy: `https://<github-user>.github.io/najeon-radio-legal/privacy.html`

Paste the live privacy HTTPS URL into Google Cloud → OAuth consent screen → Application privacy policy link.

## Local preview

Open `index.html` in a browser, or serve the directory:

```bash
python3 -m http.server 8080 --directory .
```
