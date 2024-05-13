---
draft: false
date: 2024-05-13
categories:
  - markdown
  - configuration
  - extra
  - folder structure
  - mkdocs.yml

---

#Math expression and markdown

There are `MathJax` and `KaTeX`. Two different libraries for displaying math content in browsers. They use different syntaxes and have different configuration options.

I use `MathJax` in my website. 

<!-- more -->

## Reference

[Material for MkDocs Reference](https://squidfunk.github.io/mkdocs-material/reference/math/#mathjax-mkdocsyml)

[PyMdown Arithmatex](https://facelessuser.github.io/pymdown-extensions/extensions/arithmatex/)

## Configuration

### Additional files

[Download mathjax.js](https://github.com/luomein/static_website_build_log/blob/12317329e409eeb18d53fdb20020900802683e2e/docs/javascripts/mathjax.js)

```
.
├─ docs/
│  └─ javascripts/
│     └─ mathjax.js
└─ mkdocs.yml

```


### Additional lines in `mkdocs.yml`

[Download mkdocs.yml](https://github.com/luomein/static_website_build_log/blob/12317329e409eeb18d53fdb20020900802683e2e/mkdocs.yml)

```
markdown_extensions:
  - pymdownx.arithmatex:
      generic: true

extra_javascript:
  - javascripts/mathjax.js
  - https://polyfill.io/v3/polyfill.min.js?features=es6
  - https://unpkg.com/mathjax@3/es5/tex-mml-chtml.js
```

## Markdown


| markdown | output |
| -------- | ------ |
| `$\{ x \in E \mid Φ(x) \}$` | $\{ x \in E \mid Φ(x) \}$ |





