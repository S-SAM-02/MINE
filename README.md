# October 3 — Our Story ♡

A cinematic, romantic memory website for Santhosh & Yelina.

## GitHub Pages

This repository is a **plain static HTML website**. It does not require React, Vite, npm, or GitHub Actions.

Use:

- **Settings → Pages**
- **Source:** Deploy from a branch
- **Branch:** main
- **Folder:** / (root)

The entry file is `index.html`, and `.nojekyll` is included.

## Current repository structure

```
MINE/
├── index.html
├── .nojekyll
├── README.md
├── media/
│   └── README.md
└── October_3_Our_Story_MEDIA_PART_*_of_4/
    └── relationship media
```

The website automatically checks the normal `media/` folder **and** the four existing media-part folders, including common `media/` and `public/media/` nested layouts. This means the current uploaded media does not need to be renamed immediately.

## Media

Expected collection:

- **281 photos**
- **3 videos**
- Total: **284 media files**

Video filenames:

```
us_01.mp4
video_20260328_160242.mp4
us.mp4
```

Keep original filenames.

### Recommended final organization

For the cleanest repository, eventually place all 284 files directly under:

```
media/
```

But the current website has fallback loading for the four existing media-part folders, so the site is not dependent on that cleanup.

## Website sections

- OUR STORY
- MEMORIES
- RECREATION
- LETTER

The navigation uses same-page anchors, so there is no SPA router and no refresh/404 routing problem.

## Design

The page is intentionally romantic and cinematic:

- glass navigation
- pink/violet glow
- 3D-inspired couple figures
- perspective/depth animation
- butterflies
- cinematic typography
- real memory gallery
- original video section
- personal letter

## Important

Do not restore the old React/Vite files unless you intentionally move back to a build-based deployment. The current version is designed specifically for simple GitHub Pages branch publishing.
