# dvislobokov.github.io

Personal page of Denis Vislobokov — a single static `index.html`, no build step.

## Publishing on GitHub Pages

This is a **user site**, so the repository must be named exactly `dvislobokov.github.io`:

```sh
gh repo create dvislobokov/dvislobokov.github.io --public --source . --push
```

Then in the repository settings open **Settings → Pages** and set **Source** to **Deploy from a branch**, branch `main`, folder `/ (root)`.

The site will be available at <https://dvislobokov.github.io/>.

> The documentation portal deploys separately (from the `docs` repository) and lives under <https://dvislobokov.github.io/docs/> — the two do not conflict.
