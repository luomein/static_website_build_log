---
draft: false
date: 2024-05-15
categories:
  - markdown
  - folder structure
---

#Link to Relative Path

> [Only relative path will work, not absolute path.](https://github.com/mkdocs/mkdocs/discussions/3230)

<!-- more -->

## folder structure in source code

```
.
├─ docs/
│  ├─ assets/
│  │  └─ images/
│  │     └─ test.html
│  └─ blog/
│     ├─ index.md
│     └─ posts/
│        └─ link_to_relative_path.md
└─ mkdocs.yml

```


## folder structure after deployed

```
.
├─ assets/
│  └── images/
│      └─ test.html
├─ blog/
│  └─ 2024/
│     └─ 05/
│        └─ 15/
│           └─ link-to-relative-path/
│              └─ index.html
└─ index.html

```


## assets link

!!! note "prerequisite"

    Need to set the `site_url` in `mkdocs.yml`

[link to `test.html` from this blog page](../../../../../assets/images/test.html)

`[link](../../../../../assets/images/test.html)`



