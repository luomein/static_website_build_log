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

#Table style and markdown

This syntax is commonly used in the extended markdown or 'Lightweight Markup Languages', e.g. GitHub Flavored Markdown (GFM).

<!-- more -->

## Reference

[Material for MkDocs Reference](https://squidfunk.github.io/mkdocs-material/reference/data-tables/)

[Extended Markdown](https://www.markdownguide.org/extended-syntax/)

## Configuration

### Additional lines in `mkdocs.yml`

[Download mkdocs.yml](https://github.com/luomein/static_website_build_log/blob/12317329e409eeb18d53fdb20020900802683e2e/mkdocs.yml)

```
markdown_extensions:
  - tables
```

## Markdown

* basic syntax

```
| m | n |
| - | - |
| m1 | n1 |
```

| m | n |
| - | - |
| m1 | n1 |

* column alignment

```
| left align | center | right align |
| :- | :-: | -: |
| m1 | n1 | o1 |
| m2 | n2 | o2 |
```

| left align | center | right align |
| :- | :-: | -: |
| m1 | n1 | o1 |
| m2 | n2 | o2 |


## Issues

### table width

[Force data table to use full width](https://github.com/squidfunk/mkdocs-material/discussions/3530)

!!! note "Configure in the extra css file"

    [Extra CSS Reference](https://luomein.github.io/static_website_build_log/blog/2024/05/11/extra-css/)
    ```
    .md-typeset__table {
        min-width: 100%;
    }

    .md-typeset table:not([class]) {
        display: table;
    }
    ```
