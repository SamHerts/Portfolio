# Portfolio

Personal site for Samuel Herts: public projects and work history. Plain HTML and CSS,
no build step, styled to match Probagraph and EigenToken.

Preview locally:

    python3 -m http.server -d . 8000

## Editing

- **Projects** — one `<article class="card">` per repo in `index.html`.
- **Experience** — copy a `<article class="panel job">` block per job, newest first, and
  drop the `placeholder` class once it's filled in.

## Publishing

`.github/workflows/pages.yml` deploys on every push to `main`. One-time setup: repo
Settings → Pages → Source: "GitHub Actions". Name the repo `SamHerts.github.io` to serve
it at https://samherts.github.io/.
