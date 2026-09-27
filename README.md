# Sarthak Tiwari — research website

A responsive academic website for GitHub Pages. Plain HTML and CSS, with no package installation, JavaScript, or build step required.

## Preview

Open `index.html` directly in your browser, or run this command from the repository folder:

```powershell
python -m http.server 8000 --bind 127.0.0.1
```

Then open http://127.0.0.1:8000. Stop the server with Ctrl+C.

## Edit your content

- **Research blurb:** edit the introduction marked `EDIT` in `index.html`. This is draft copy based on your public interests, to revise with your own research statement.
- **Name and affiliation:** edit the `hero-copy` block in `index.html`.
- **Portrait:** put your picture in `assets/` and replace the image's `src` and `alt` in the block marked `PHOTO`. The frame uses a 4:5 crop; adjust `object-position` in `styles.css` to position your face.
- **Publications:** copy an existing `<article class="publication">` block, use a unique heading ID, and update the title, authors, venue, links, and citation. Keep papers newest first.
- **Colors and fonts:** edit the variables at the top of `styles.css`. The default palette uses charcoal, warm off-white, and muted copper. Print styles use dark text on white paper.
- **Professional profiles:** Google Scholar, GitHub, and LinkedIn links are in the `profile-links` block in `index.html`.
- **Email or CV:** add these when you have the details or assets you want to make public. No contact information or CV link has been invented.
- **Search previews:** update the description and Open Graph metadata in the HTML head when revising your research statement.

Publication entries are maintained locally. Google Scholar links point to your live profile; the site does not automatically synchronize with Scholar.

## Work with Codex

Use this repository folder as a local project in Codex. The workflow for this site is: make changes on `main`, preview locally, review the diff, then commit and push when ready.

For a fresh clone on another computer with Git installed:

```powershell
git clone https://github.com/Sarthak-Ti/Sarthak-Ti.github.io.git
cd Sarthak-Ti.github.io
```

The fresh clone opens on `main`, where the website is maintained. No pull request is required for this workflow.

## Publish on GitHub Pages

1. Preview and review your changes. The draft biography and portrait placeholder can be replaced whenever you are ready.
2. Commit the reviewed files on `main` and run `git push origin main`.
3. In the repository's **Settings → Pages**, verify that the publishing source is the desired branch and `/ (root)` folder if using branch-based publishing.
4. Wait for the Pages deployment to finish, then check the published site.

The existing `CNAME` file contains `rthak.tech` and was preserved. Confirm that you still own and intend to use that domain before publishing; its DNS configuration has not been verified. If you want only the default `sarthak-ti.github.io` address, remove the custom domain from Pages settings and the `CNAME` file as part of that change.

GitHub instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Sources and editorial notes

Verified on September 27, 2026:

- Name, affiliation, interests, and the four listed publications: https://scholar.google.com/citations?user=kIlwZwQAAAAJ&hl=en
- 2025 Comment: https://www.nature.com/articles/s41576-025-00887-2 and https://pubmed.ncbi.nlm.nih.gov/40957944/
- 2024 spectroscopy paper: https://pubmed.ncbi.nlm.nih.gov/38841076/
- 2024 3D models paper: https://pubmed.ncbi.nlm.nih.gov/38458505/
- 2021 paper: https://pubmed.ncbi.nlm.nih.gov/34729970/ and the Google Scholar record.

The portrait is a neutral vector placeholder, not a photograph. Citation counts are omitted because they change over time.
