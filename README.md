# MATSim website source

This uses [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/), a Markdown-based static site generator.

- You can edit markdown files in the `docs` folder directly to update the site. Edits gladly accepted!
- Or follow instructions below to build it locally on your computer:

To add a news item, copy one of the pages in `docs/news`, rename to have the correct date and a useful filename, and edit the content header and news items as needed.

### Building locally

This site uses MkDocs which requires a recent install of Python.

- Clone the repo
- Run `pip install -r requirements.txt`
- Then you can run a local server with `mkdocs serve` so you can edit files and test/review changes before publishing
- Any changes you push to the master branch will be built and published automatically using Github Actions

Important files and folders:
- `mkdocs.yml` contains all of the site navigation, settings, and theme
- `docs` folder has all of the markdown content files
- `docs/news` contains all news/blog items. 
- `extra.css` has our matsim.org styling such as front page layout, colors, etc
- `overrides` has HTML templates for home page, gallery, news pages, etc

