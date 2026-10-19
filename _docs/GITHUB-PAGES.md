# Publish everything from ONE GitHub repo

1. Create a repo (e.g. `ar-private-ltd`, Public). Tip: in an organization named
   `ar-private-ltd`, a repo called `ar-private-ltd.github.io` gives the root address
   https://ar-private-ltd.github.io/
2. Upload the contents of this folder (index.html, clients, _template, _docs, images).
3. Settings > Pages > Deploy from a branch > main > / (root) > Save.
4. Live addresses (after 1-2 minutes):
   - Company site:  https://USERNAME.github.io/REPO/
   - Client sites:  https://USERNAME.github.io/REPO/clients/CLIENT-NAME/

## Add a new client
1. Copy `_template` to `clients/client-name` (lowercase, no spaces, use hyphens).
2. Fill the {{TOKENS}} in its index.html. Put photos in its own images/ folder.
3. Commit. The site is live at /clients/client-name/ in about a minute.

## Rules
- Folders starting with _ (_template, _docs) stay in the repo but are NOT published.
- Each client keeps images in its own folder, referenced as images/photo.jpg.
- File names are case-sensitive.
- Everything is public in a public repo. Never store private client data.
- One repo = one custom domain. If a client needs their own domain
  (e.g. srisaitailors.in), give that client a separate repo.
