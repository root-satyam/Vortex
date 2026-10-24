# root — Discord Bot Legal Pages

A static GitHub Pages website for the root Discord bot.

## IMPORTANT: verify before publishing

Search every HTML file for `[VERIFY`, `[CONFIRM`, and `[ADD`, then replace the placeholders. Specifically confirm:

- Which Discord IDs, message content, events, logs, and settings root actually accesses and stores.
- Whether logging includes edited/deleted message content, and who can view it.
- Storage type/provider, database location where relevant, and security safeguards.
- Retention periods or criteria for each type of data; deletion after leaving a server.
- Third-party services, data sharing, and any cross-border transfers.
- The procedure for access/deletion requests and a usable operator contact.
- Whether the bot offers paid features, subscriptions, or other functionality needing additional terms.
- Effective and last-updated dates and applicable legal obligations.

These are templates, not a legal review. Do not publish unverified claims.

## Publish to GitHub Pages

1. Sign in to GitHub and create a **public** repository named `root-bot-legal` (or another name).
2. Upload all four files (`index.html`, `privacy.html`, `terms.html`, `style.css`) to the repository root. Optionally upload this README.
3. Open **Settings → Pages → Build and deployment**.
4. Select **Deploy from a branch**, branch **main**, folder **/(root)**, then **Save**.
5. Wait for the deployment. Your URLs will usually be:
   - `https://YOUR_USERNAME.github.io/root-bot-legal/privacy.html`
   - `https://YOUR_USERNAME.github.io/root-bot-legal/terms.html`
6. Open both links in a private/incognito browser window to confirm they are public.
7. In Discord Developer Portal → Applications → root → General Information, enter the corresponding Privacy Policy URL and Terms of Service URL.

If your repository name differs, change the URLs accordingly. These pages do not themselves guarantee Discord bot verification.
