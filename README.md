# October 3 — Our Story ♡

A cinematic, 3D-style memory website for Santhosh & Yelina.

## GitHub Pages

This is now a **plain static GitHub Pages website**. It does not require React, Vite, npm, or GitHub Actions.

Use:

- **Settings → Pages**
- **Source:** Deploy from a branch
- **Branch:** `main`
- **Folder:** `/ (root)`

The entry point is `index.html`. `.nojekyll` is included.

## Media

The repository contains the relationship media in four existing folders:

- `October_3_Our_Story_MEDIA_PART_1_of_4/`
- `October_3_Our_Story_MEDIA_PART_2_of_4/`
- `October_3_Our_Story_MEDIA_PART_3_of_4/`
- `October_3_Our_Story_MEDIA_PART_4_of_4/`

The collection is **281 photos + 3 videos**. The website discovers the files directly from the repository tree, so the media does not need to be renamed or moved.

Video files currently in the collection:

- `video_20260328_160242.mp4`
- `us.mp4`
- `us_01.mp4`

## Website experience

- 3D-inspired cinematic hero
- glass navigation and depth effects
- one continuous slideshow for all supplied photos
- autoplay, pause-on-hover, swipe/drag and arrow-key controls
- 3D perspective photo frame and progress indicator
- three native HTML video players with proper controls
- memory recreation section
- romantic letter section
- responsive mobile layout

The slideshow uses the GitHub repository tree at runtime to discover the real media files, so future media additions can be picked up without rebuilding a framework project.

## Important

Do not restore the old React/Vite project or GitHub Actions workflow unless the deployment architecture is intentionally changed again.
