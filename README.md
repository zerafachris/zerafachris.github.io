# zerafachris.github.io

Redirect stub for the GitHub Pages user site. The real site lives in
[zerafachris/bio](https://github.com/zerafachris/bio) and is served at
<https://zerafachris.github.io/bio/>.

- `index.html` sends `https://zerafachris.github.io/` to `/bio/`.
- `404.html` sends any other root path `/foo` to `/bio/foo`.

GitHub Pages can't issue server-side redirects, so both use a meta refresh and/or
`location.replace`.
