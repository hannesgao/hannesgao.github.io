# hannesgao.github.io

Personal page of Hannes Gao: https://hannesgao.github.io/

A single static page (`index.html`, `style.css`, `favicon.svg`) without JavaScript, cookies or
third-party resources. German and English content; the language switch is pure CSS.

GitHub Pages serves files with `Cache-Control: max-age=600`, so `index.html` references
`style.css?v=<hash>`: after changing the CSS, set `v` to the first 8 hex digits of its SHA-256
(`sha256sum style.css | cut -c1-8`).
