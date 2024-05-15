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

## folder structure after deployed

```
.
├─ docs/
│  ├─ assets/
│  │  └─ images/
│  │     └─ test.html
│  └─ blog/
│     └─ posts/
│        └─ 2024/
│           └─ 05/
│              └─ 15/
│                 └─ link-to-relative-path
└─ mkdocs.yml

```


## assets link

!!! note "prerequisite"

    Need to set the `site_url` in `mkdocs.yml`

[link to `test.html` from this blog page](../../../../../assets/images/test.html)

`[link](../../../../../assets/images/test.html)`



