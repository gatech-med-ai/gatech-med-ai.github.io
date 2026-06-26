# GaTech MedAI Homepage

This repository is a [Sphinx](https://www.sphinx-doc.org/) site configured for [Read the Docs](https://readthedocs.org/).

## Local development

Install the documentation dependencies:

```sh
uv sync --group docs
```

Build the site:

```sh
uv run sphinx-build -b html docs docs/_build/html
```

Open `docs/_build/html/index.html` in a browser to preview the site.

## Deployment

Read the Docs uses `.readthedocs.yaml` and builds from `docs/conf.py`.
