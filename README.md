# unxml demos

Live site: **https://vivainio.github.io/unxml-demos/**

A [Zensical](https://zensical.org/) gallery showing [`unxml`](https://github.com/vivainio/unxml-rs)
— a CLI that turns verbose XML (schemas, stylesheets, rule sets) into a
compact, indentation-based pseudocode — rendering real-world documents: UBL
and Finvoice schemas, DocBook XSL stylesheets, EN16931 e-invoicing Schematron
rules, MSBuild targets, and more.

## Layout

- `docs/` — the Zensical site source (Markdown pages + generated demo pages)
- `examples/` — vendored source documents the demos are rendered from (see
  `examples/README.md` and `examples/gallery/README.md` for provenance/licenses)
- `scripts/generate-demos.py` — renders every demo from `examples/` via the
  `unxml` CLI; see the script's docstring for usage
- `.github/workflows/docs.yml` — CI: installs `unxml` from PyPI, runs the
  generator, builds the site with `zensical build`, and deploys to GitHub Pages
  on every push to `main`

## Regenerating locally

```sh
pip install unxml-rs
python3 scripts/generate-demos.py
zensical serve   # preview at http://localhost:8000
```

To preview an unreleased `unxml-rs` change instead of the PyPI version:

```sh
python3 scripts/generate-demos.py --unxml-bin ../unxml-rs/target/release/unxml
```
