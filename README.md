# Moonhaven website prototype

A responsive, dreamy lavender/pink front-end prototype for Moonhaven, a plural-system-friendly Discord companion concept.

## What's included
- Public Terms of Service page (`terms.html`) — draft requiring operator details and review
- Public Privacy Policy page (`privacy.html`) — draft that must be updated to match real data practices
- Dashboard overview
- About Moonhaven page explaining purpose and principles
- Searchable Bot Commands & Help page with a proposed slash-command blueprint
- Custom headmate profiles and custom fields
- Fronting check-ins and history
- Journal notes
- Boundary/preferences draft
- Best-effort JSON member import/export for PluralKit-style and Moonhaven backups
- Community introduction preview and settings page

## Open it locally
1. Download and unzip the ZIP file.
2. Open the `index.html` file in a browser such as Chrome or Firefox.

No installation or paid software is needed to preview the prototype.

## Important limitations
This is a **static front-end prototype**, not a deployed production website or a working Discord bot. The command list is a **proposed plan**, not a list of implemented Discord commands. The site does not currently have sign-in, server-side storage, Discord OAuth, a connected bot, or secure access controls. Data in the prototype is held in page memory and may be lost on refresh. Visibility labels are descriptive only and do not enforce privacy. Do not enter real sensitive information.

PluralKit import/export is best-effort and focused on member profiles. It does not fully round-trip all system settings, groups, or switch history. Moonhaven-specific custom fields cannot become native PluralKit fields. Keep an independent backup and review files before importing them.

## Free hosting (optional)
You can publish the static prototype using GitHub Pages:
1. Create a GitHub account and a new repository.
2. Upload `index.html`, `terms.html`, and `privacy.html` to the repository root (plus any other website files).
3. In the repository, open **Settings → Pages**.
4. Choose deployment from the main branch and root folder, then save.
5. Wait for GitHub Pages to publish the site.
6. Your public links will follow this pattern (replace `YOUR-USERNAME` and `YOUR-REPOSITORY` with the actual values):
   - `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/terms.html`
   - `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/privacy.html`

For a user/organization site repository named `YOUR-USERNAME.github.io`, the URLs instead look like `https://YOUR-USERNAME.github.io/terms.html` and `https://YOUR-USERNAME.github.io/privacy.html`. These URLs will not work until the site is published.

Do not put API keys, bot tokens, passwords, or private user data in a public repository. A real Moonhaven bot and production website will need a backend, secure authentication/authorization, data deletion/export flows, and privacy review before handling sensitive information.


**Legal page reminder:** the Terms and Privacy Policy pages are starter drafts. Replace all bracketed operator/contact placeholders and ensure the Privacy Policy accurately reflects the live hosting provider, bot permissions, logs, database, retention, and data rights before submitting the URLs to Discord. Consider getting appropriate legal review.
