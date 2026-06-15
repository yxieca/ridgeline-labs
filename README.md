# ridgeline-labs

Source for the Ridgeline Labs GitHub Pages site at
<https://yxieca.github.io/ridgeline-labs/>.

Built with Jekyll (the default GitHub Pages renderer). Content is
authored in Markdown with a custom layout in `_layouts/default.html`.

## Pages

| URL                              | Source                       |
|----------------------------------|------------------------------|
| `/`                              | `index.md`                   |
| `/privacy-policy.html`           | `privacy-policy.md`          |
| `/privacy-handyyi.html`          | `privacy-handyyi.md`         |
| `/solunar-trail-manual.html`     | `solunar-trail-manual.md`    |

The `.html` permalinks are stable URLs that ship inside the Android
apps and the Play Store listings; don't change them without updating
those references too.

## Local preview (optional)

```sh
bundle install
bundle exec jekyll serve
# open http://127.0.0.1:4000/ridgeline-labs/
```

## CI

`.github/workflows/jekyll-build.yml` runs `jekyll build` on every PR
and confirms that all four permalinked HTML files are produced.
