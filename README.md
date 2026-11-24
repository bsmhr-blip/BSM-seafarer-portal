# BSM Helm for Crew — prototype (v9)

Clickable prototype of the BSM Helm for Crew mobile app with a showcase page around it.
All names, vessels, clinics and amounts are sample data.

## Publish with GitHub Pages

1. On github.com, click **New repository**. Name it, for example, `bsm-helm-for-crew`. Choose **Public** (GitHub Pages on a free account needs a public repository; private works on paid plans). Click **Create repository**.
2. On the new repo page, click **uploading an existing file**.
3. Drag in everything from this folder: `index.html`, `404.html`, `standalone.html`, `README.md` and the `assets` folder. Click **Commit changes**.
4. Go to **Settings › Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, branch **main**, folder **/ (root)**, and click **Save**.
5. Wait about a minute and refresh the Pages settings. Your link appears at the top:
   `https://<your-username>.github.io/bsm-helm-for-crew/`

To update later, upload the new `index.html` (and `assets` if changed) to the same repo. Pages republishes automatically on every commit.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The site: showcase page with the live app in a phone frame |
| `assets/bsm-logo.png` | BSM logo used by `index.html` |
| `404.html` | Sends a mistyped link back to the prototype |
| `standalone.html` | Single-file version with the logo built in, for sharing by email |
| `.nojekyll` | Tells GitHub Pages to serve files as they are (optional) |

## Notes

- Google Maps embeds and directions work on the published site without an API key.
- GitHub Pages cannot set the custom security headers that the Netlify version used (`netlify.toml`). That is fine for a prototype with sample data.
- Light/dark mode follows the viewer's device and can be switched with the button in the top bar.
