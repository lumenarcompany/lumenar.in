# lumenar.in

The Lumenar website. Static HTML and CSS; the hand-drawn sketches are generated at build time with rough.js, so the page ships no JavaScript.

```
npm ci
node build.js        # writes dist/
```

Pushes to `main` deploy to GitHub Pages (`.github/workflows/pages.yml`), served at https://lumenar.in.

Fonts: Lumenar Sans (Lumenar's own typeface) and Kalam (Indian Type Foundry, SIL Open Font License 1.1).
