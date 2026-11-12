# KAMAL — Portfolio (English)

Static portfolio site for KAMAL (design engineer / creative technologist, Nara, Japan).
No build step, no dependencies — plain HTML files. All card screenshots are embedded
in `index.html` as data URIs, so the page renders identically anywhere.

## Files
- `index.html` — the portfolio (hero with the interactive isometric canal city)
- `glass-jelly-card.html` — linked tool page (Glass Jelly Card)
- `jelly-piano.html` — linked tool page (Jelly Piano)
- `vercel.json` — clean URLs only; everything else is Vercel defaults

## Deploy (GitHub + Vercel)
1. Push this folder to a GitHub repository (it is already a git repo — just add your remote and push).
2. In Vercel: **Add New → Project → Import** the repository.
3. Framework Preset: **Other**. Build Command: *(none)*. Output Directory: *(root)*.
4. Deploy. Every later `git push` redeploys automatically.

## Alternative: attach to an existing site as /en
Put the three HTML files into an `en/` folder of that project instead —
all internal links are relative, so both layouts work.
