# AI Use Course Outline Builder

A fillable, self-saving tool for documenting AI-use expectations per assignment, built on
Pitt UCTL's developmental model, the AI Assessment Scale (AIAS), and Danny Liu's
two-lane / menu approach. Supports multiple courses side by side, exports/imports as JSON,
and generates a copy-ready or printable summary for a syllabus or assignment sheet.

## Publish this with GitHub Pages (no personal name in the URL)

To avoid your personal GitHub username showing up in the link, host this from an
**Organization** account rather than your personal one:

1. **Create a free Organization** — on github.com, click the **+** in the top right →
   **New organization** → choose the Free plan. Give it a neutral name
   (e.g. `pitt-ai-outline` or similar) — this name becomes part of the URL, so pick
   something you're fine with being public.
2. **Create a new repository inside that organization** — name it anything
   (e.g. `ai-use-outline`). Keep it Public (Pages needs Public on the free tier).
3. **Upload the file** — on the repo's main page, click **Add file → Upload files**,
   drag in `index.html` from this package, and commit.
4. **Turn on Pages** — go to the repo's **Settings → Pages**. Under "Build and
   deployment," set Source to **Deploy from a branch**, Branch to **main** (or
   **master**) and folder to **/ (root)**. Save.
5. **Wait about a minute**, then refresh that Pages settings page — it will show your
   live URL:

   ```
   https://<org-name>.github.io/<repo-name>/
   ```

   That's the link to put in PowerPoint's Insert → Link.

## Updating it later

Any time you want to change the tool, edit `index.html` directly on GitHub (pencil icon
on the file page) or upload a replacement — Pages redeploys automatically within a minute
of a commit to the branch you selected.

## Note on autosave

This tool's autosave (via `window.storage`) only works when opened inside Claude. Hosted
here on GitHub Pages, it behaves like any other static site — use the **Export JSON** /
**Import JSON** buttons in the tool itself to carry your data between visits.
