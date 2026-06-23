# My Creative Space – File Structure

```
creative-space/
├── index.html          ← Home / hub page (your original file)
├── drawings.html       ← Drawing canvas + image gallery
├── webpages.html       ← HTML live editor + saved projects
├── files.html          ← File uploader + viewer
├── lab.html            ← Try-Out Lab (4 mini experiments)
└── resources/
    ├── style.css       ← Shared styles for all pages
    └── README.md       ← This file
```

## Pages at a glance

| Page | What it does |
|---|---|
| `index.html` | Hub with cards linking to every section |
| `drawings.html` | Draw with a brush, erase, save as PNG, upload images to a gallery |
| `webpages.html` | Write HTML, preview it live, save/load projects (localStorage) |
| `files.html` | Drag-and-drop any file, preview images + text, download saved files |
| `lab.html` | Four experiments: Colour Mixer, Rhythm Machine, Gravity Balls, Word Generator |

## How to use

1. Open `index.html` in any modern browser — no server needed.
2. All links are relative, so keep the folder structure intact.
3. The `resources/style.css` file is shared by all pages; edit it to restyle everything at once.

## Customising

- **Colors / fonts** – edit the CSS variables at the top of `resources/style.css`
- **Add a new page** – copy any existing page, update the `<title>` and `<h1>`, then add a card for it in `index.html`
- **Saved projects** (webpages.html) use `localStorage`, so they persist between browser sessions on the same device
