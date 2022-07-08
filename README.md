# Installation

Install `mkdocs-material`

```bash
pip install mkdocs-material
```

## Usage

Clone this repository and modify the markdown files under `docs/`.

For dev view launch

```bash
mkdocs serve
```

Or

```bash
python -m mkdocs serve
```



For publish this repository via GitHub you shall commit and push changes

```bash
git add .
git commit -m "changes"
git push
```

and then you can run following command

```bash
mkdocs build
mkdocs gh-deploy --force
```

Or

```bash
python3 -m mkdocs build
python3 -m mkdocs gh-deploy --force
```