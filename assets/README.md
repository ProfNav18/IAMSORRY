# Assets

Put the final-reveal video here as:

```
assets/video.mp4
```

`index.html` already points to this exact path. Once the file is added (via GitHub's
"Add file → Upload files" button, or `git add`/`git push`), the final screen will play it
automatically — no code changes needed. Until then, the page shows a friendly placeholder
instead of a broken player.

Keep the filename exactly `video.mp4` (lowercase), or update the `<source src="...">` in
`index.html` to match whatever name you use.
