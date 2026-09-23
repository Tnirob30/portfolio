# Touhid Hasan Nirob — Academic Portfolio

Version 2: a fully dark, futuristic, responsive research portfolio for GitHub Pages. Plain HTML, CSS, and JavaScript; no build tools or dependencies are required.

## Start here

1. Extract all files. Open `index.html` in Chrome or Edge.
2. Open `START-HERE.html` for the complete publishing, editing, and troubleshooting guide.
3. Open `editor.html` to edit text, publications, projects, certificates, and photographs through forms.
4. Preview, download `content.js`, and replace the file in this folder.

## Publish

Upload the folder's **contents** (not the ZIP or enclosing folder) into your GitHub repository. `index.html`, `content.js`, `editor.html`, and `assets/` must be at the same level.

In **Settings → Pages**, choose **Deploy from a branch → main → /(root) → Save**.

For a user site, name the repository `YOUR-USERNAME.github.io`. For a project site, any repository name works; all website paths are relative.

## Update

The editor generates a downloadable `content.js`; it does not publish automatically. Upload the downloaded file to the repository root and commit. Visitors cannot edit your live website through this editor. Only repository collaborators with write access can publish changes.

Photos added through the editor are resized and embedded in the content file. Larger galleries can use assets/ file paths. Certificate scans and gallery photos open in a keyboard-accessible image viewer.

## Content notes

The original CV PDF is included unchanged. The website distinguishes published work from submitted/under-revision manuscripts. GPA remains explicitly qualified as through the seventh semester. Review the source notes in START-HERE.html for degree dates, RA dates, current manuscript status, and the missing NEURO-PULM project-post link. No portrait or gallery photos were supplied.

## Technology

- Native responsive CSS, sticky desktop navigation, mobile menu, print styles.
- Escaped text and restricted link/image URLs.
- Local editor with import/export, draft saving, image resizing, and preview.
- The base portfolio needs no database, GitHub token, login, or external font/CDN. The optional shared counter uses the included Worker and D1 service.
- The downloaded CV is independent of the editable website text.

Official GitHub guide: https://docs.github.com/en/pages/quickstart

## Version 2 features

Click **Manage content** in the website footer to reveal Add/Edit controls in every section. The gallery preserves full image proportions and includes arrows, swipe, captions, thumbnails, timed advancement, a progress indicator, and a pause/play control.

A shared repeat-visit counter is implemented in `counter-service/`. Follow its README to deploy it in your Cloudflare account, then enter its HTTPS URL in **Editor → Display settings & counter**. The frontend remains on GitHub Pages. Counting is inactive until you connect that service.

To install this redesign, replace all website files (back up first), not just content.js. Routine later content edits still use content.js only.
