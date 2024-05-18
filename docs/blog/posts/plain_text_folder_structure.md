---
draft: false
date: 2024-05-18
categories:
  - markdown
  - folder structure
---

#Plain Text Folder Structure

1. generate plain text folder structure

2. put it in a code block markdown

<!-- more -->

## Python code

```
```

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



