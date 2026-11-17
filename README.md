# ModelKit Companion shelf

The public shelf page for ModelKit Companion. A shelf link looks like
`https://glejr.github.io/modelkit-shelf/#<code>`; the code after the `#` never reaches GitHub.

One static file. It reads a single shelf by its code from the app's backend, using a publishable key
that is public by design (row-level security decides what can be read). No tracking, no cookies.

The source lives in the app repo at `web/shelf/index.html`; this repo is a copy for GitHub Pages.
