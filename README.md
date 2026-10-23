# Toheeb Abdullahi · Portfolio

Single-page static site (no build step). Everything lives in `index.html`;
images sit in the folders next to it (`covers/`, `vcs/`, `te4k/`, `lvd4k/`, ...).

Run it locally with any static server:

```sh
python3 -m http.server 4173
```

The contact form posts to Formspree (`CF_ENDPOINT` in `index.html`).
