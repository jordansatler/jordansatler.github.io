# jordansatler.github.io

Source for my personal website: [https://jordansatler.github.io](https://jordansatler.github.io)

## Built with

- [Jekyll](https://jekyllrb.com/) (static site generator), deployed via [GitHub Pages](https://pages.github.com/)
- Based on the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template (a fork of [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/))

## Repository layout

| Path | Contents |
| --- | --- |
| `_config.yml` | Site-wide settings (title, author, social links) |
| `_data/navigation.yml` | Top nav menu |
| `_pages/` | Top-level pages (about, CV, research, publications, talks, teaching) |
| `_portfolio/`, `_talks/` | Collection items, rendered to their own URLs |
| `_layouts/`, `_includes/`, `_sass/` | Theme internals |
| `files/` | Static downloads (e.g. CV PDF) |
| `images/` | Site images |
| `markdown_generator/` | Optional helpers to generate publication/talk markdown from TSV |

## Editing content

- **CV / About / Research**: edit the corresponding file in `_pages/`.
- **Publications**: edit `_pages/publications.md` (or regenerate from TSV via `markdown_generator/`).
- **Talks**: add a markdown file to `_talks/`.
- **CV PDF**: replace `files/Satler_cv.pdf`.

Push to `master` and GitHub Pages rebuilds automatically.

## Running locally

Requires Ruby 3.x and Bundler.

```bash
bundle install
bundle exec jekyll serve
```

Then open [http://localhost:4000](http://localhost:4000). The local server rebuilds on file changes.

## License

Site content (text in `_pages/`, `_talks/`, etc.) © Jordan Satler.
Theme code is MIT-licensed; see [LICENSE](LICENSE).
