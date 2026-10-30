# Tex website

The website of [Tex](https://github.com/toniesteves/tex), a light LaTeX editor for Linux:
**https://www.toniesteves.com/tex-editor/**

The app's code, issues and releases live in [toniesteves/tex](https://github.com/toniesteves/tex). This repository holds
only the website, a single `index.html` served by GitHub Pages from the root of `main`.

## Preview locally

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Releases need no change here

The version, the `.deb` file name in the install command and the Versions list come from the
[releases of toniesteves/tex](https://github.com/toniesteves/tex/releases) when the page loads. Publishing a release with
its `.deb` attached is enough; the values written in `index.html` are only a fallback.

## Files

```text
index.html             the whole page: markup, styles and script
assets/icon.png        app icon (also the favicon source)
assets/favicon.png     64 px favicon
assets/screenshots/    screenshots of the app (project window, Git panel, the four themes)
assets/fonts/          Latin Modern, subset to Latin and a few math letters
```

## Licenses

The website is released under the [MIT License](LICENSE). Copyright © 2026 Toni Esteves.

The fonts keep their own licenses:

- **Latin Modern** (Roman, Mono and Math), by the GUST e-foundry, under the
  [GUST Font License](https://www.gust.org.pl/projects/e-foundry/licenses). The files in `assets/fonts/` are subsets of
  the TeX Live originals, converted to WOFF2.
- **Instrument Sans**, loaded from Google Fonts, under the
  [SIL Open Font License 1.1](https://openfontlicense.org).
