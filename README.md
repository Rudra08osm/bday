# 🌟 Niyati's Starlight Birthday Surprise

A cinematic, mobile-first birthday surprise website for Niyati — featuring a WebGL star-tunnel, a glowing photo reveal, typewriter love letter, and optional background music.

---

## ✨ Open Locally (double-click, no server needed)

1. Open the `niyati-birthday` folder.
2. Double-click **`index.html`** in any browser (Chrome, Firefox, Edge, Safari).
3. Click **"Open 💫"** — that's it.

> **Note:** Some browsers block audio autoplay. If music doesn't start, tap the 🔊 button in the bottom-right corner after clicking Open. No audio file is included yet — see below.

---

## 🎵 How to Add Background Music

1. Get an `.mp3` file (e.g. "Tum Hi Ho", "Tera Ban Jaunga").  
   Keep it **under 5 MB**; `128 kbps` stereo is ideal.
2. Rename it exactly **`music.mp3`** (all lowercase).
3. Drop it into the **`assets/`** folder (replace any existing file).
4. The site auto-detects it — no code changes needed.

---

## 📸 How to Swap the Photo

1. Prepare your replacement image:
   - Format: **JPG** preferred (PNG works too)
   - Size: under **500 KB**, max **1600 px** wide
   - Rename it **`photo.jpg`**
2. Drop it into the **`assets/`** folder, overwriting the existing one.
3. Reload `index.html` — done.

> If the photo fails to load for any reason, the site shows a glowing 🤍 fallback frame so it never breaks.

---

## 🌐 Deploy for Free

### Option A — Netlify Drop (easiest, 30 seconds)
1. Go to **[netlify.com/drop](https://netlify.com/drop)**.
2. Drag the entire `niyati-birthday` folder (or the `niyati-birthday.zip`) onto the page.
3. Netlify gives you a free HTTPS link (e.g. `https://magical-stars-abc123.netlify.app`).
4. Share the link with Niyati!

### Option B — GitHub Pages (free, permanent)
1. Create a new **public** GitHub repo.
2. Push all files (`index.html`, `assets/`, `README.md`) to the `main` branch.
3. Go to **Settings → Pages → Source: `main` / `/ (root)`** → Save.
4. Your site will be live at `https://<username>.github.io/<repo-name>/`.

---

## 🎨 Customise the Message

Open `index.html` in any text editor, find the `var MESSAGE` block (search for `MESSAGE`), and edit the text between the backticks. The typewriter will animate whatever you write.

---

## 📁 File Structure

```
niyati-birthday/
├── index.html          ← single self-contained page
├── README.md           ← this file
└── assets/
    ├── photo.jpg       ← your photo (341 KB, pre-optimised)
    └── music.mp3       ← add your music here (not included)
```

---

*Made with 💫 endless love — Avik*
