# fouillet-site

The source of [florianfouillet.com](https://florianfouillet.com), Florian Fouillet's personal site: one page of HTML and CSS with self-hosted fonts. No build step, and one script: Cloudflare Web Analytics' beacon, which counts visits without cookies (its token is public, in the page). No other outside request. Cloudflare Pages serves this folder as it is, from `main`, with the headers in `_headers`, whose content-security policy allows that beacon and nothing else.

## Preview

```sh
python3 -m http.server
```

Then open <http://localhost:8000>. The headers in `_headers` apply on Cloudflare Pages only.

## Licence

No licence is given for the text. The fonts, Newsreader and Didact Gothic, keep their own licence, the SIL Open Font License 1.1 (in `fonts/`).
