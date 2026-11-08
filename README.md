# hovjsyy.dev

Static site served by GitHub Pages at https://hovjsyy.dev. Plain HTML and one stylesheet, no build step.

| Path | Page |
|---|---|
| `/` | Home, lists projects |
| `/drops-tracker/` | Drops Tracker landing page (Chrome Web Store homepage URL) |
| `/drops-tracker/privacy/` | Drops Tracker privacy policy (Chrome Web Store privacy URL) |

The privacy policy describes what the extension actually does. When the extension changes what it reads, stores or sends, update the policy and its effective date in the same change.

Preview locally: `npx serve .` (or any static server) from this folder. Root-relative links (`/assets/...`) do not work from `file://`.
