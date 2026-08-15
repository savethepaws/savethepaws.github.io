# Save the Paws — CEPR 125 Course Project Site

A static website for the CEPR 125 course project (Instructor: M.J. Plebon), branded as
**Save the Paws**, a mock pet-rescue non-profit built around the provided logo, color
palette (primary blue #CFD9E5, accent pink #D8A8BB, ink charcoal #2C2A2B, soft slate
#5A5B5F, mist grey #BBC4CE) and fonts (Didot for headers, Avenir Next for body).

**Team:** Ohannes, Habiba, Batool

## Files

- `index.html` — the site
- `assets/logo-mark.jpeg` — the paw-print logo mark used in the header, hero, and Instagram mock-up
- `README.md` — this file

## Still needed: Google Business Profile details

The Google share link couldn't be auto-read (Google's share links block automated
fetching), so the **Location & Hours** and **Rating** fields in the "Visit & Contact Us"
section are placeholders (marked in pink italics). Open `index.html`, search for
`class="todo"`, and replace each placeholder with the real address, phone number,
hours, and rating/review count from the listing.

## How to host this on GitHub Pages

1. Create a new repository on GitHub (e.g. `save-the-paws`).
2. Add `index.html`, the `assets/` folder, and this `README.md` to the repository —
   either by uploading the files directly on github.com, or via git:
   ```bash
   git init
   git add index.html assets README.md
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-repo>.git
   git push -u origin main
   ```
3. On GitHub, go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to `Deploy from a branch`,
   choose the `main` branch and `/ (root)` folder, then click **Save**.
5. After a minute or two, your site will be live at:
   `https://<your-username>.github.io/<your-repo>/`

## Editing the content

Everything is in a single `index.html` file (no build step needed):

- **Contact info** — fill in the `class="todo"` placeholders under "Visit & Contact Us" with real Google Business Profile details.
- **Team section** — edit `<div class="team-grid">` to add roles, photos, or links.
- **Logo** — swap `assets/logo-mark.jpeg` for a higher-resolution or transparent-background version if you have one.
- **Fonts** — the site uses Didot and Avenir Next, which render natively on macOS; on other systems it falls back to similar serif/sans-serif fonts automatically.

Just open `index.html` in any text editor, save, and push the change to GitHub — Pages will redeploy automatically.
