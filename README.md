# Educational Technology e-Portfolio — Claudia Casso

This repository contains a simple, responsive e-Portfolio scaffold intended for the Educational Technology program.

Recommended options to publish/edit your portfolio:
- Google Sites — Easiest for non-coders; drag-and-drop editing, simple menus.
- GitHub Pages — Host this repo as a static site; good if you keep this custom site.
- Vercel / Netlify — Simple deploys from GitHub for modern static sites (supports automatic updates).

If you prefer a non-coding approach, use Google Sites and recreate the pages there. If you want to continue with this custom site, here are quick edit instructions:

Edit content
- Replace personal placeholders in `index.html` (name, degree, background) and `profile.html` (LinkedIn URL).
- Replace `assets/profile-placeholder.svg` with your headshot (use same filename or update `index.html`).

Placeholders remaining
- Contact email and phone: please provide the professional email to display or indicate you prefer a contact form.
- LinkedIn URL: add your LinkedIn profile URL to `profile.html`.
- EDTC 6320 project artifacts: add project title, description, and artifact report links on `edtc6320.html` and update the Matrix.

How I updated the site for you
- Inserted your name and a concise About Me on the Home page.
- Added your full profile biography to `profile.html`.

Example content added
- An example EDTC 6320 project and a sample Artifact Report structure were added to `edtc6320.html` to show how to present your work.
- A sample matrix row mapping the example project to program standards was added to `matrix.html`.
- Example leadership items and example contact details were added to make the site read as complete; these are clearly labeled as examples and should be replaced with your real information.
- Set `EDTC 6320: Instructional Technology` as the single course on `courses.html` and created `edtc6320.html` for your course projects.
- Removed example placeholders where possible and left clear instructive comments where I need your input (contact, artifact links, LinkedIn, headshot).

Change accent color
- Edit `--accent` in `css/style.css`.

Preview locally (simple static server)
```bash
# From the repository folder
python -m http.server 8000
# Then open http://localhost:8000 in your browser
```

To deploy via GitHub Pages (repo already pushed):
1. In GitHub repository settings, enable Pages from the `master` branch (or `main` if you rename).

To deploy with Vercel (recommended for automatic builds):
1. Sign in to https://vercel.com and import the GitHub repo. Vercel will detect a static site and deploy automatically.

If you'd like, I can:
- Add a `CNAME` and configure GitHub Pages, or
- Create a `main` branch and set it as default, or
- Add simple edit instructions directly into the site.
