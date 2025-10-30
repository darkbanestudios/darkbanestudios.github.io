# Darkbane Studios — Echoes of Eternity (GitHub Pages)

This repository contains the static website for **Darkbane Studios** (Irrdaroth).  
It is ready for **GitHub Pages** deployment from the `main` branch.

## Structure
```
.
├─ index.html
└─ assets/
   ├─ hero.jpg
   ├─ og.jpg
   ├─ darkbane_logo_ring.jpg
   ├─ fragments.jpg
   ├─ echoheart.jpg
   ├─ echoes_of_the_fallen.jpg
   ├─ ashes_of_tomorrow.jpg
   ├─ crown_of_cinders.jpg
   ├─ sanctum_of_sorrow.jpg
   ├─ veins_of_the_void.jpg
   ├─ weaver_of_stars.jpg
   └─ hollow_crown.jpg
```

## How to publish
1. Upload all files to your repository (`main` branch).
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/** (root)
4. Save — your site will be live in ~1–3 minutes.

## Customize
- Replace **FRAGMENTS_ID_HERE** in `index.html` with your YouTube video ID for *Fragments of Eternity*.
- Replace **PLAYLIST_ID** or use an artist embed in the Spotify iframe.
- Update Discord invite `https://discord.gg/YOURCODE` and Spotify artist link.
- Put your actual images into `/assets/` using the exact filenames in the structure above.

## Domain (optional)
- Add a DNS `CNAME` record for `www` → `yourname.github.io`
- In **Settings → Pages**, set your Custom Domain. GitHub will provision HTTPS automatically.
