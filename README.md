# I'm Sorry 💗

A cute, gamified mobile-first apology page. She plays through 4 short, un-loseable mini
games (catch the hearts, memory match, pop the balloons, forgive-o-meter) and then unlocks
a final video message.

## Add your video

Drop your video file at `assets/video.mp4` (the page already looks for it). If it's
missing, the final screen shows a friendly placeholder instead of a broken player.

## Run locally

Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

then visit `http://localhost:8000`.

## Deploy as a shareable link (GitHub Pages)

1. Push this repo to GitHub (already done if you're reading this from the repo).
2. In the repo settings → **Pages**, set source to the `main` branch, root folder.
3. GitHub gives you a URL like `https://profnav18.github.io/iamsorry/` — that's the link
   to send on WhatsApp. It opens straight into the page, no login needed.

Progress is saved in the browser (`localStorage`), so if she closes the chat and taps the
link again later, it resumes where she left off instead of starting over.
