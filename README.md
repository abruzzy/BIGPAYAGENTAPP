# BIG PAY Marketing Portal — demo

Two standalone pages, no server needed:

- `app/index.html` — Agent app (phone)
- `dashboard/index.html` — Admin dashboard (Super Admin / Compliance)

## Publish on GitHub Pages

1. Go to github.com → **New repository**. Name it `bigpay-demo`. Keep it **Private** if you only want your team to see it (Pages on private repos needs a paid plan; otherwise make it Public — the link is unlisted).
2. Open the repo → **Add file → Upload files**. Drag the whole `app` folder and the whole `dashboard` folder in (keep the folder structure). Click **Commit changes**.
3. Repo **Settings → Pages**. Under *Build and deployment*: Source = **Deploy from a branch**, Branch = **main**, Folder = **/ (root)**. Save.
4. Wait about a minute, then your links are:
   - App: `https://<your-username>.github.io/bigpay-demo/app/`
   - Dashboard: `https://<your-username>.github.io/bigpay-demo/dashboard/`

Open the app link on a phone for the best demo.

## Updating later

Upload the new `index.html` over the old one (same path) and commit. The link stays the same.

## Notes

- The two pages do not share data. Changes made in the app are not visible in the dashboard, and vice versa. Each page keeps its own sample data.
- Maps need internet access (tiles are loaded from Esri).
