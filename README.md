# Minh Phaleap · Portfolio

My personal portfolio, told as a story. Scrolling moves a camera through chapters, from my first line of code in 2024 to the projects I build now. One orange line runs through the whole story.

**Chapters:** Opening · The first line (2024) · Learning by building (2025) · The first real job (Asia Ready, MOPAC) · The team · On my own (F1 Store) · The AI chapter (Kai) · End credits

## Run it

It is a single static page: no build step and no dependencies.

```bash
python -m http.server 8000
```

Then open http://localhost:8000. Opening `index.html` straight from the folder also works, but the browser then blocks reading the portrait photo, so a silhouette shows instead.

## Files

```
index.html     the whole site: HTML, CSS and JavaScript
assets/        project screenshots and the portrait photo
```

## Built with

Plain HTML, CSS and JavaScript. CSS 3D transforms for the camera, a canvas for the story line and the pixel portrait. Fonts: Bebas Neue, Geist and Geist Mono from Google Fonts.
