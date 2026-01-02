# 🎵 cdn-playlist

Personal CDN (Content Delivery Network) for hosting music-related assets. This repository is used to serve files for my web projects via GitHub Pages.

## 📂 Folder Structure

* **/music**: Audio files (.mp3, .m4a)
* **/covers**: Album art or song covers (.jpg, .png, .webp)
* **/lyrics**: Song lyrics in JSON format (.json)

## 🚀 How to Use

To access the files, use the following URL format:

`https://fahilsum.github.io/cdn-playlist/[folder-name]/[file-name]`

### Example Links:
- **Audio:** `https://fahilsum.github.io/cdn-playlist/music/song-name.mp3`
- **Cover:** `https://fahilsum.github.io/cdn-playlist/covers/cover-art.jpg`
- **Lyrics:** `https://fahilsum.github.io/cdn-playlist/lyrics/lyrics.json`

## 🛠 Maintenance & Best Practices

1. **Keep it Clean:** Use lowercase and hyphens for filenames (e.g., `line-without-a-hook.mp3`) to avoid broken links in some browsers.
2. **Bypass Jekyll:** Ensure the `.nojekyll` file exists in the root directory so all assets are accessible.
3. **Cache Busting:** If you update a file but the changes don't show up, add a version query at the end of the URL (e.g., `song.mp3?v=1.1`).

## ⚠️ Disclaimer

The media files (audio and images) hosted in this repository are for **personal use and educational purposes only**. 

- **Copyright:** All rights to the music and artworks belong to their respective owners. 
- **No Commercial Use:** These assets are not intended for any commercial gain or distribution.
- **Takedown Request:** If you are the owner of any content hosted here and wish for it to be removed, please contact me via GitHub, and I will delete it immediately.

---
*Created and maintained by [Fahilsum](https://github.com/fahilsum)*
