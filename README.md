# Python-Mkdocs-Demo
A demonstration on how to automatically create documentation.

Link to gh-pages: https://plasmatech8.github.io/Python-Mkdocs-Demo/

# Basics

1) Create mkdocs project
```
mkdocs new .
```
2) Add files to pages and change name:
```yaml
site_name: My Docs Woo
pages:
  - Home: 'README.md'
```

3. Edit pages
4. Create live server
```
mkdocs serve
```
5. Edit and revise
6. Commit and push source to github
7. Deploy to gh-pages (pushes site/ to gh-pages branch)
```
mkdocs gh-deploy
```

See https://edgarroman.github.io/techtalk-mkdocs/

# Advanced
## Themes
```yaml
site_name: Mkdocs overview
pages:
  - Home: 'README.md'
theme: readthedocs
```

## Extensions
pip install pymdown-extensions

```yaml
site_name: Mkdocs overview
pages:
  - Home: 'README.md'
markdown_extensions:
  - pymdownx.superfences
```

See https://facelessuser.github.io/pymdown-extensions/