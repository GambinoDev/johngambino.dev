# johngambino.dev

Static portfolio site. No build step.

## Hosting
Cloudflare Pages, connected to this repo. Every push to `main` deploys automatically (about 30 seconds).

- Live: https://johngambino.dev (also https://johngambino-dev.pages.dev)
- Settings: Cloudflare dashboard → Workers & Pages → johngambino-dev
- Domain: the CNAME for johngambino.dev is managed by Pages (Custom domains tab)

## Editing
- Text: `index.html`
- Colours: the `--` variables at the top of the `<style>` block (light in `:root`, dark in `[data-theme="dark"]`)
- Screenshots: `assets/`
- CV: replace `cv/John-Gambino-CV.pdf` (keep the same name; this public copy has no phone number)
