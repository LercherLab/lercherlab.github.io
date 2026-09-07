# Lercher Lab Website

This repository hosts the public homepage for the **Lercher Lab** (CIID, Heidelberg University), live via GitHub Pages.

🔗 **Live site:** https://[your-github-username].github.io/[repository-name]/

---

## 📁 What's in this repository

- `index.html` — the entire website (structure, styling, and content in one file)
- `images/` — folder containing all photos and logos used on the site

---

## ✏️ How to edit the text

No coding experience needed!

1. Open `index.html` in any plain text editor (e.g., Notepad, TextEdit, VS Code, or even GitHub's built-in web editor).
2. Use **Find** (Ctrl+F / Cmd+F) to locate the section you want to change. Content is grouped under these sections:
   - **Home** — title, tagline, intro sentence
   - **Research** — "The Problem," "The Approach," "The Questions"
   - **Team** — member names, roles, and bios
   - **Publications** — paper listings
   - **Funding** — funding body logos
   - **Affiliation** — institutional logos
   - **Contact** — email and address
3. Edit the visible text between the HTML tags (leave the tags like `<h2>` or `<p>` untouched).
4. Save the file.

---

## 🖼️ How to swap images

Keep the same filenames so the site keeps working — just replace the file contents:

| Filename | Used for |
|---|---|
| `images/banner.png` | Homepage banner photo |
| `images/alexander-lercher.jpg` | Team photo |
| `images/hannah-simonis.jpg` | Team photo |
| `images/technical-assistant.jpg` | Team photo (placeholder) |
| `images/PhD-student.jpg` | Team photo (placeholder) |
| `images/logo-chs.png` | CHS Stiftung funding logo |
| `images/logo-synthimmune.png` | SynthImmune Cluster logo |
| `images/logo-heidelberg.png` | Heidelberg University logo |
| `images/logo-ukhd.png` | UKHD logo |
| `images/logo-ciid.png` | CIID logo |

**Recommended image shapes/sizes:**
- Banner: ~2.3:1 landscape
- Team photos: 1:1 square (~300×300px), close-up headshot
- Funding/affiliation logos: ~2:1 landscape, transparent or white background preferred

If an image file is missing or misnamed, a placeholder graphic will automatically appear instead — so the site won't break, but the correct photo won't show either.

---

## ➕ How to add a new team member

1. In `index.html`, find the **Team** section.
2. Copy one complete team member block (starts with `<article class="card-lift...` and ends with the matching `</article>`).
3. Paste the copied block right after the last team member's block.
4. Edit the name, role, and bio text in your new block.
5. Update the `src="images/..."` filename to point to your new team member's photo, and add that photo to the `images/` folder.

---

## 🚀 How to publish changes

1. Make your edits to `index.html` (and/or update files in `images/`).
2. Go to this repository on GitHub.
3. Commit and push your changes (or use "Upload files" in the GitHub web interface if you're not using git directly).
4. GitHub Pages will automatically update the live site within a minute or two.

**First-time setup only:** if the site isn't live yet, go to **Settings → Pages**, set the source to the `main` branch and `/ (root)` folder, then save.

---

## 📧 Contact email

The lab contact email is written in plain text directly in `index.html` (inside a small script near the Contact section), so it displays normally and works as a clickable mailto link. To change it, search for `alexander.lercher` and `uni-heidelberg.de` and edit those two values.

---

## ❓ Questions

If something looks broken after an edit, double-check that you haven't accidentally deleted a `<` or `>` symbol. When in doubt, undo your last change (or re-copy from a backup of this file) and try again.
