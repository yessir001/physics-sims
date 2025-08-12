# Physics Sims Starter

A tiny, static site for hosting your HTML simulations. Perfect for GitHub Pages, Netlify, or Vercel.

## Quick Deploy (GitHub Pages)

1. Create a **public** GitHub repo (e.g., `physics-sims`).
2. Upload these files to the repo (make sure `index.html` is at the root).
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
5. Choose branch **main**, folder **/** (root). Save.
6. After 1–2 minutes, your site will be live at:
   `https://<your-username>.github.io/<repo-name>/`

> Tip: The included file `.nojekyll` helps avoid Jekyll processing issues on GitHub Pages.

## Add more simulations

- Copy the `sims/pendulum/` folder, rename it (e.g., `sims/torque/`), and place your `index.html` inside.
- Edit the root `index.html` to add a new card linking to your new sim path.

## Alternatives

- **Netlify Drop**: drag the folder onto https://app.netlify.com/drop and get a link.
- **Vercel**: connect your GitHub repo and deploy with one click.

## Classroom tips

- Share direct links (e.g., `.../sims/pendulum/`) in Google Classroom/WhatsApp.
- Test on mobile; keep touch targets big and text high-contrast.
- Avoid external trackers; your sims are static and private by default.
