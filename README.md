# Sukhdeep Singh Gill · Cosmology

Personal research website, served by GitHub Pages at **https://sukhdeepsinghgill.github.io**.

It is plain HTML and CSS: no build step and no framework. Edit a page, commit, and GitHub Pages republishes it within a minute or two.

## Pages

| File | Page |
| --- | --- |
| `index.html` | Home |
| `research.html` | Research |
| `publications.html` | Publications |
| `code.html` | Code and data |
| `reports.html` | Reports |
| `resources.html` | Reading list and surveys |
| `contact.html` | Contact |
| `404.html` | Shown for any missing page |

Shared styles live in `assets/style.css`. The header and footer are repeated in each page, so a change to the menu needs to be made in every file.

## Adding images

Put these files in the `images/` folder and they appear automatically. Any that are missing are simply hidden, so the site never shows a broken image.

| File name | Where it appears |
| --- | --- |
| `images/portrait.jpg` | Home page, above "At a glance" |
| `images/universe-evolution.jpg` | Research › Visual tour (ESO image) |
| `images/cosmic-web.jpg` | Research › Visual tour (2dFGRS image) |
| `images/mwa.jpg` | Research › Visual tour (MWA telescope) |
| `images/reionization.jpg` | Research › Visual tour (EoR simulation) |

Landscape images around 1600 × 1200 pixels work best (the frames are 4:3).

## Adding a new paper

Copy one `<article class="paper">…</article>` block in `publications.html`, paste it under the right year and change the title, authors, journal and links. Add it to "Latest publications" in `index.html` as well if it is one of the three newest.

## Turning on GitHub Pages

1. This repository must be named `sukhdeepsinghgill.github.io`.
2. In the repository, open **Settings › Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, then branch **main** and folder **/ (root)**, and save.
