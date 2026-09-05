# WhatWatchNext funnel domain setup

**Funnel brand:** WhatWatchNext  
**Product brand:** NextBinge  
**Tagline:** Quick picks for what to watch — powered by NextBinge  
**Play Store:** https://play.google.com/store/apps/details?id=com.nextbinge.app

This Netlify site (`next-binge-static`) is the funnel landing page. Primary CTAs already point at the Play listing.

## 1. Register the domain

Buy **`whatwatchnext.com`** (preferred).

Fallbacks if taken:

- `watchpicktonight.com`
- `nextbinge.app` (brand-first; weaker SEO phrase)

## 2. Attach domain in Netlify

1. Deploy / push this repo so Netlify has the latest site.
2. Netlify → **Domain management** → **Add custom domain** → `whatwatchnext.com`.
3. Follow Netlify DNS instructions (nameservers or CNAME/`www` + apex).
4. Wait for HTTPS certificate to become active.

Until the custom domain is live, use your Netlify URL (e.g. `https://<site>.netlify.app`) as the temporary website.

## 3. Play Console — Website field

1. Play Console → **Store presence** → **Store settings** / **App content** (support links).
2. Set **Website** to `https://whatwatchnext.com` (or temporary Netlify URL).
3. Set **Privacy policy** to `https://whatwatchnext.com/privacy/` (trailing slash is fine for this static site).

## 4. Quick checklist

- [x] Site uses real NextBinge logo + wordmark + phone screenshots
- [ ] Domain purchased
- [ ] Netlify custom domain + HTTPS OK
- [ ] Landing page CTA opens Play listing
- [ ] Privacy policy URL works on the custom domain
- [ ] Play Console Website + Privacy fields updated
- [ ] Play Console category = Entertainment + listing copy from `STORE_LISTING.md`
- [ ] Play Console phone screenshots uploaded from `images/screen-*.png` / `.jpg`
