# BackitSnappy — landing page

The marketing/landing page for [BackitSnappy](https://github.com/PrajwalAnkushrao8/BackitSnappy).
Plain static HTML/CSS, no build step, no dependencies.

## Before deploying

There's one placeholder screenshot slot left (the empty frame in the
Security section of `index.html`) — drop a real screenshot or screen
recording there before publishing.

## Deploying to GitHub Pages

1. Push this repo to GitHub.
2. In the repo's **Settings → Pages**, set Source to "Deploy from a branch,"
   branch `main`, folder `/ (root)`.
3. GitHub gives you a URL like `https://PrajwalAnkushrao8.github.io/backitsnappy-site/`
   within a minute or two.

That's it — no build step, no CI needed for a static two-file site like this.

## Local preview

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000.
