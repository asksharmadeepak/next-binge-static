# Play Console checklist — D labs cross-promo

Code on the three marketing sites now links sibling apps. Confirm these **Store listing → Store settings / App content** fields so Play and the web properties stay consistent.

## App website URLs

| App | Package | Website (recommended) | Privacy |
|-----|---------|------------------------|---------|
| MyBinge | `com.mybinge.app` | `https://offlinemedialibrary.com` | Listing privacy URL (or site privacy page) |
| NextBinge | `com.nextbinge.app` | `https://whatwatchnext.com` when live; until then your Netlify URL for `next-binge-static` | `https://whatwatchnext.com/privacy/` (or Netlify `/privacy/`) |
| Homework Buddy | `com.homeworkbuddy.app` | `https://easyhomeworkactivity.com` | Site privacy page |

## Developer account

- **Visit website:** `https://easyhomeworkactivity.com` (highest traffic) or a dedicated D labs page if you add one later.
- **Developer page** (already lists all apps):  
  https://play.google.com/store/apps/dev?id=8759041902208147900

Users who open any D labs listing already see **More by D labs** — that is free cross-discovery; keep all three apps published under the same developer account.

## After deploy

1. Open each site footer → click MyBinge / NextBinge / Homework Buddy / All D labs apps.
2. Confirm Play URLs include `utm_campaign=dlabs_cross_promo` where expected.
3. In Play Console analytics / Google Analytics, filter `utm_campaign=dlabs_cross_promo` after a few weeks to see referral installs.
