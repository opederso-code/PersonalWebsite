## Cursor Cloud specific instructions

This is a zero-dependency static portfolio website (single `index.html` file). There is no build system, no package manager, no linter, and no automated tests.

### Serving the site

Run a local HTTP server from the workspace root:

```
python3 -m http.server 8080
```

Then open `http://localhost:8080/` in a browser. The site features a typing animation on the hero page and a zoom transition to a projects section when the centered white square is clicked.

### Notes

- No `package.json`, `Makefile`, or build tooling exists; there is nothing to install or build.
- The only external resource is the Satoshi font loaded from `api.fontshare.com`. The site works without internet (falls back to system fonts).
- There are no lint checks, automated tests, or CI pipelines configured for this repository.
