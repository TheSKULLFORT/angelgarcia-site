# angelgarciadesign.com

Angel Garcia's portfolio. A floating 3D handheld that loads each project from a cartridge.

## What's where

| Path | What it is |
| --- | --- |
| `index.html` | Homepage: the 3D handheld, cartridge shelf, work index, credits, about, contact |
| `case-study.html` | One template for every case study page, at `/work/<slug>` |
| `content/projects.json` | The projects (one per cartridge). Edit in the CMS |
| `content/site.json` | Homepage text, games list, press, links. Edit in the CMS |
| `media/` | Uploaded images, GIFs and short videos |
| `.pages.yml` | Tells the CMS (app.pagescms.org) what's editable |
| `_redirects` | Sends `/work/anything` to the case study template |
| `studio-hdr.js` | Studio lighting for the 3D device |

## Editing

- **Content:** sign in at app.pagescms.org with GitHub, open this repository, edit, Save. Netlify publishes in about a minute.
- **Design:** the Figma file "Angel Garcia — Portfolio" holds the brand library and page designs. Ask Claude to apply Figma changes to the code.
