# Portfolio 2.0

Personal portfolio site for Vamsi Krishna Lekkala, Data Engineer and independent AI product builder. Work in progress.

Sections: journey, about, experience, work, credentials and contact, with a terminal-style boot intro before the hero.

## Stack

A single self-contained `index.html`: hand-written HTML, CSS and JavaScript, with images embedded as data URIs and fonts from Google Fonts. No framework, no build step, no dependencies.

## Run it

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000   # then open http://localhost:8000
```

## Deploy

Any static host works (GitHub Pages, Vercel, Netlify): publish the repo root. The file is about 4.4 MB because the images are inlined; moving them to separate files would make the first load faster.
