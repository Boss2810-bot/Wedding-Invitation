# Rishabh & Srishty Wedding Invitation

A responsive wedding invitation website with event details, a live countdown, a photo gallery, and background music.

## Run locally

This is a static website and does not have a package manager or build step. From the project directory, run:

```powershell
python -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000) in a browser. If `python` is not available, use another static file server and serve this directory as its root.

## Project files

- `index.html` contains the page, event schedule, navigation, countdown, and audio behavior.
- `style.css` contains the responsive layout and visual styling.
- `countdown/circle.css` styles the circular countdown display.
- `img/` and `audio/` contain the existing invitation photos and background music.
