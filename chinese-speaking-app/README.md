# 说吧 Shuō ba — Chinese Speaking Coach

A phone-friendly Mandarin conversation tutor powered by Google Gemini.
Speak Chinese, get a reply at your HSK level, and see syllable-by-syllable tone feedback with a graph of your own pitch.

## Files

| File | What it is |
|---|---|
| `index.html` | The whole app (HTML, CSS, JavaScript in one file) |
| `manifest.webmanifest` | Lets phones install it like an app |
| `apple-touch-icon.png`, `icon-192.png`, `icon-512.png` | Home-screen icons |

## Host it on GitHub Pages (no coding tools needed)

1. Sign in at github.com → **+** (top right) → **New repository**.
2. Name it `chinese-speaking-app`, set it to **Public**, click **Create repository**.
   (Free accounts need Public for Pages. Your API key is NOT in these files, so this is safe.)
3. On the new repo page click **uploading an existing file**.
4. Drag in **all the files from this folder** (not the folder itself) → **Commit changes**.
5. Go to **Settings → Pages**. Under *Build and deployment*: Source = **Deploy from a branch**, Branch = **main**, folder = **/ (root)** → **Save**.
6. Wait 1–2 minutes and refresh. Your link appears at the top:
   `https://YOUR-USERNAME.github.io/chinese-speaking-app/`

## Put it on your phone

- **iPhone:** open the link in **Safari** → Share → **Add to Home Screen**.
- **Android:** open in **Chrome** → ⋮ → **Add to Home screen** (or *Install app*).

Open it, go to **Settings**, paste your Gemini key from https://aistudio.google.com/apikey, tap **Test**, and allow the microphone when asked.

## Updating the app later

Repo → click `index.html` → pencil icon (or **Add file → Upload files** and drop the new `index.html`) → **Commit changes**. The live link updates within a minute or two. On your phone, close and reopen the app to get the new version.

## Privacy

Your API key, words, and practice history are stored only in your phone's browser (localStorage) and are sent only to Google's API. Nothing is stored in this repository.
