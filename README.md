# Game website

The game's home page (`index.html`), privacy policy (`privacy.html`) and
`app-ads.txt` for AdMob. Plain HTML, no build step.

## Before publishing

Replace these placeholders in `index.html` and `privacy.html` (VS Code: Ctrl+Shift+H):

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
4. After a minute the site is live at https://sico112.github.io, and the policy at
   https://sico112.github.io/privacy.html.
5. In Play Console, use https://sico112.github.io as the website and
   https://sico112.github.io/privacy.html as the privacy policy URL.
