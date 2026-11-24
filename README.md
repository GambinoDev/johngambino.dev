# johngambino.dev

Static portfolio site. No build step.

## Deploy (Azure Static Web Apps)
1. Push this folder to a GitHub repo (e.g. GambinoDev/johngambino.dev).
2. Azure portal → Static Web Apps → Create → Free plan → GitHub → pick the repo.
   Build preset: Custom · App location: `/` · Output location: (blank).
3. Custom domains → Add → johngambino.dev (TXT validation) → add the TXT + CNAME records in Cloudflare (proxy off / grey cloud).

## Editing
- Text: `index.html`
- Colours: the `--` variables at the top of the `<style>` block (light in `:root`, dark in `[data-theme="dark"]`)
- Screenshots: `assets/`
- CV: replace `cv/John-Gambino-CV.pdf` (keep the same name)
