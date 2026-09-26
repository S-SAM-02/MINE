# October 3 — Our Story

Cinematic relationship-memory website for Santhosh & Yelina.

## Run locally

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Media setup

The website code is already configured to load media from:

```
public/media/
```

The complete media collection contains **284 files: 281 images + 3 videos**.

Because the full media collection is too large for a single reliable download, it has been split into **4 smaller ZIP packages**. Download **all four** and extract each ZIP into the **same project root**. Each ZIP contains files destined for `public/media/`.

After extraction, the structure must be:

```
october-3-our-story/
├── index.html
├── package.json
├── README.md
├── src/
│   ├── main.jsx
│   └── styles.css
└── public/
    └── media/
        ├── ...281 images...
        ├── us_01.mp4
        ├── video_20260328_160242.mp4
        └── us.mp4
```

**Important:** Do not rename the media files and do not move them out of `public/media/`. The React code already uses `/media/<filename>` paths.

## Media package names

1. `October_3_Our_Story_MEDIA_PART_1_of_4.zip`
2. `October_3_Our_Story_MEDIA_PART_2_of_4.zip`
3. `October_3_Our_Story_MEDIA_PART_3_of_4.zip`
4. `October_3_Our_Story_MEDIA_PART_4_of_4.zip`

Download all four before deploying so every referenced memory is available.

## Vercel

The project is Vite-based. After the media is placed under `public/media/`, connect the GitHub repository to Vercel and use:

- Build command: `npm run build`
- Output directory: `dist`

## Notes

- The site uses `Yelina` throughout the relationship-facing copy.
- Photos and videos are treated as supplied memories.
- Avatar/3D sections are artistic recreations.
- Media paths are local and begin with `/media/`.


## Upload the media from your Windows desktop with GitHub Desktop

1. Clone this repository from GitHub Desktop using the repository URL.
2. Do **not** use your unrelated `CALISTA-VITA-2026` local folder.
3. After cloning, open the cloned `october-3-our-story` folder.
4. Extract all 4 media ZIP packages into that folder so the final location is:
   `october-3-our-story/public/media/`
5. In GitHub Desktop, choose **Current repository → october-3-our-story**.
6. Enter a summary such as `Add relationship media`.
7. Click **Commit to main**, then **Push origin**.
8. GitHub Pages will automatically rebuild after the push.

### Important GitHub file-size limit

GitHub does not accept normal Git files larger than 100 MB. If one of the 3 videos is over 100 MB, do not try to push that video normally; it must be reduced/split or hosted separately. The ZIP files themselves should not be uploaded to the repository.

### GitHub Pages

The project now includes a Vite GitHub Pages configuration and an automatic Actions deployment workflow. After the first workflow completes, the site is published at:

`https://s-sam-02.github.io/october-3-our-story/`
