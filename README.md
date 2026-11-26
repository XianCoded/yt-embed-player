# yt-embed-player
# YT Embed Player

A lightweight, static YouTube video player hosted on GitHub Pages that allows passing any YouTube video ID or URL dynamically while properly handling `origin` and `referrerpolicy` headers to prevent embed playback errors.

## Live Demo

`https://<username>.github.io/yt-embed-player/`

## Usage

### 1. Load via URL Parameter
Append `?v=` (or `?id=`) followed by any 11-character YouTube video ID to the end of your GitHub Pages URL:

```text
https://<username>.github.io/yt-embed-player/?v=dQw4w9WgXcQ
```

### 2. Load via On-Page Input
1. Open the hosted page.
2. Paste either a full YouTube link (`://youtube.com...`, `youtu.be/...`, `://youtube.com...`) or an 11-character video ID into the search bar.
3. Click **Load Video**. The page URL updates automatically so you can bookmark or share it.

## Setup on GitHub Pages

1. Push `index.html` and `README.md` to the `main` branch of this repository.
2. Go to **Settings** > **Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Select the **`main`** branch and **`/ (root)`** folder, then click **Save**.
