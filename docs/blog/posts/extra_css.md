---
draft: false
date: 2024-05-11
categories:
  - css
  - configuration
  - customization
  - extra
  - folder structure
  - mkdocs.yml
---

#Extra CSS

<!-- more -->

## Reference

[Material for MkDocs Reference](https://squidfunk.github.io/mkdocs-material/customization/?h=extra+css#additional-css)

## Configuration

### Additional files

[Download mathjax.js](https://github.com/luomein/static_website_build_log/blob/12317329e409eeb18d53fdb20020900802683e2e/docs/stylesheets/extra.css)


```
.
├─ docs/
│  └─ stylesheets/
│     └─ extra.css
└─ mkdocs.yml
```

### Additional lines in `mkdocs.yml`

[Download mkdocs.yml](https://github.com/luomein/static_website_build_log/blob/12317329e409eeb18d53fdb20020900802683e2e/mkdocs.yml)


```
extra_css:
  - stylesheets/extra.css
```


