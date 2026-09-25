# Print TCG

Browser-based tool to lay out trading card images for printing on A4 paper. Upload a folder of card images, pick quantities, choose standard sizes (59×86 mm or 63×88 mm), and print a 3×3 grid per page.

## Live site

After you enable GitHub Pages (see below), the app is served from the repository root as a static site:

- **Project site:** `https://<your-username>.github.io/PrintTCG.github.io/`

## GitHub Pages setup

1. Push this repository to GitHub (include `index.html` at the repo root).
2. Open the repo on GitHub → **Settings** → **Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Choose branch **`main`** (or **`master`**) and folder **`/ (root)`**, then **Save**.
5. Wait a minute for the deployment; refresh **Pages** to see the public URL.

No build step or GitHub Actions workflow is required—GitHub Pages serves `index.html` directly.

## Privacy

Images and your print list are stored only in this browser (IndexedDB and localStorage). Nothing is uploaded to a server when you use the hosted page.
