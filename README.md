# Sico Games website

A general studio site, with one folder per game. Plain HTML, no build step.

- `index.html`: Sico Games home page with the list of games
- `privacy.html`: links to each game's privacy policy
- `unlatch/index.html` and `unlatch/privacy.html`: the Unlatch page and its policy
- `app-ads.txt`: for AdMob; it must stay at the site root and covers all games

## Before publishing

Replace these placeholders in `unlatch/privacy.html` (VS Code: Ctrl+Shift+H):

| Placeholder | Example |
|-------------|---------|
| `{{YOUR_LEGAL_NAME}}` | Your full legal name (Sico Games is shown as the brand) |
| `{{COUNTRY}}` | Romania |
| `{{CONTACT_ADDRESS}}` | The same postal address you give Google Play as a trader |
| `{{EFFECTIVE_DATE}}` | The day you publish, e.g. 1 November 2026 |

In `app-ads.txt`, put in your AdMob publisher ID.

The game is called Unlatch and the developer brand is Sico Games.

## Publishing on GitHub Pages (free)

`app-ads.txt` must be at the root of the site, so use a *user site*:

1. On GitHub, create a new **public** repository named exactly `sico112.github.io`.
2. Upload the contents of this folder (not the folder itself) to it.
3. In the repository, open Settings › Pages and set Source to "Deploy from a branch", branch `main`, folder `/ (root)`.
4. After a minute the site is live at https://sico112.github.io.
5. Play Console developer account website: https://sico112.github.io
6. Unlatch store listing privacy policy URL: https://sico112.github.io/unlatch/privacy.html

A new game gets its own folder (copy `unlatch/`) and a card on the home page.

Optional: buy a domain such as sicogames.com and set it under Settings › Pages ›
Custom domain. app-ads.txt then has to be reachable at that domain's root.
