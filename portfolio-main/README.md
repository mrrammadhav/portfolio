# Ram Madhav · Portfolio

Live website: https://mrrammadhav.github.io/portfolio/

Made with Portfolio Generator. Design code: `split.slate.classic.pill.tilt`

## What's in this folder

| File | What it is |
|---|---|
| `index.html` | The whole one-page website |
| `css/style.css` | Colours, fonts, layout and animations |
| `js/main.js` | Menu, dark mode, scroll effects, contact form, problems-solved popup |
| `assets/resume/Ram_Madhav_Resume.pdf` | One-page ATS resume (the Download Resume button) |

| `404.html` | Friendly page for broken links |

## Publish it free on GitHub Pages

1. Create a **public** repository named `portfolio`.
2. Click **uploading an existing file** and upload everything in this folder. `index.html` must sit at the top level.
3. Click **Commit changes**.
4. Go to **Settings → Pages**, choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
5. After 1–2 minutes your site is live at https://mrrammadhav.github.io/portfolio/

## Updating later

1. Open Portfolio Generator and use **Import backup** with your saved `portfolio-data-….json` file.
2. Edit your details, then download a new ZIP from Step 4.
3. In this repository click **Add file → Upload files**, drop in the new files (same names replace the old ones) and **Commit changes**.

Tip: keep your backup JSON file private. It is not part of this website.

## Updating your Problems Solved count

In `index.html`, find `id="solvedMenu"`. For each site, change `data-count="0"` to your solved count and (for LeetCode) replace `YOUR_LEETCODE_USERNAME` in the link. The total next to Projects / Certifications / Skills is calculated automatically. If a link still contains `YOUR_`, that row is hidden, and with only one site the number opens that site directly.
